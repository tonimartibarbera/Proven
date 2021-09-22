<!-- .slide: class="intro" -->
# M05.UF1.NF1.A1
# Requisits de software 
### CFGS DAW-BIO
<small>Pedro Durán / <pduran5@xtec.cat></small>

---

# Requisits de software

- Els requisits del software sovint es classifiquen com a **requisits funcionals (RF)** o **requisits no funcionals (RNF)**.

---

# Requisits funcionals (RF)

- Són declaracions dels serveis que proveirà el sistema, com hauria de reaccionar a determinades entrades i com hauria de comportar-se en situacions particulars.

- En alguns casos, el requeriments funcionals també poden expressar explícitament el que el software no ha de fer.

--

# Requisits funcionals (RF)

- Els RF descriuen el que hauria de fer el sistema i depenen:
    - del tipus de software que s'està desenvolupant
    - dels usuaris que utilitzaran el software
    - de l'enfocament general que s'adopti al escriure els requisits

--

- Exemple de RFs d'aplicació per guardar informació de pacients que reben un tractament de salut mental:
    - **RF1.** L'usuari podrà cercar les llistes de cites de totes les clíniques.
    - **RF2.** El sistema generarà cada dia, per cada clínica, un llistat dels pacients que s'espera atendre aquell dia.
    - **RF3.** Cada membre del personal que utilitzi el sistema serà identificat de manera exclusiva pel seu número d'empleat de 8 dígits.

--

# Requisits funcionals (RF)

- Aquests requisits d'usuari defineixen funcionalitats específiques que s'han d'incloure al software.

- Els RFs poden fer referència a diferents nivells de detall (RF1 vs RF3).

--

# Requisits funcionals (RF)

- Idealment, l'especificació de RFs s'un software hauria de ser:
    - **completa**: tots els serveis i informació requerida per l'usuari hauria d'estar definida.
    - **coherent**: els requisits no han de ser contradictoris.

---

# Requisits no funcionals (RNF)

- Són aquells requeriments que no es refereixen directament a les funcions específiques que lliura el sistema, sinó a les propietats emergents d'aquest.

- Poden ser restriccions sobre els serveis o funcions oferides pel software. S'inclouen les restriccions temporals, restriccions al procés de desenvolupament i restriccions imposades pels estandards.

--

- Els RNFs solen especificar o restringir les característiques del conjunt del sistema. Poden relacionar-se amb propietats del sistema com poden ser:
    - la **fiabilitat**
    - el **temps de resposta**
    - **l'ús de memòria**

- Alternativament, poden definir restriccions a la implementació del sistema, com poden ser:
    - capacitat dels dispositius d'E/S
    - representació de les dades utilitzada en les interfícies amb altres sistemes.

--

- Exemple de RNFs d'aplicació per guardar informació de pacients que reben un tractament de salut mental:
    - **Requisit de producte:**
        - **RNF1.** L'aplicatiu estarà disponible per totes les clíniques en l'horari de DL a DV de 8h30 a 17h30.
    - **Requisit organitzatiu:**
        - **RNF2.** Els usuaris hauran d'identificar-se amb el seu carnet de l'autoritat sanitària.
    - **Requisit extern:**
        - **RNF3.** El sistema haurà d'implementar la normativa ISO 9001:2015

--

| Propietats | Mesura |
| - |:-:|
| **Velocitat** | Transaccions processades/segon |
|| Temps de resposta usuari-event |
|| Temps de refresc de la pantalla |
| **Tamany** | MB/GB i format distribució |
| **Facilitat d'ús** | Temps de formació |

--

| Propietats | Mesura |
| - |:-:|
| **Fiabilitat** | Probabilitat de no disponibilitat |
|| % d'aparició d'errors |
|| Disponibilitat |
| **Robustesa** | Temps de reinici després d'una fallada |
|| % de corrupció de dades després d'una fallada |
| **Portabilitat** | Nº de S.O. soportats |

--

<img src="/img/RNFs.png" />