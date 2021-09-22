<!-- .slide: class="intro" -->
# M05. Entorns de Desenvolupament 
### CFGS DAW-BIO
<small>Pedro Durán / <pduran5@xtec.cat></small>

---

# UF1. NF1. Cicles de vida, metodologies i IDEs
## A1. Cicles de vida i metodologies

---

## Desenvolupament de programari

*   Tota **aplicació informàtica** ha seguit un **procediment** planificat i desenvolupat detall per detall **per a la seva creació**:

    *   Analitzar les necessitats.
    *   Dissenyar una solució.
    *   Desenvolupar el programari.
    *   Dur a terme les proves.
    *   Implantar el programari.

---

## Concepte de programa informàtic

*   Un **programa informàtic** és un conjunt d'esdeveniments ordenats de manera que se succeeixen de forma seqüencial en el temps, un darrere l'altre.

*   Per **executar un programa** s'entén fer que l'ordinador segueixi totes les seves ordres, des de la primera fins a la darrera.

--

## Codi font i compilació

* Un cop s'ha acabat d'escriure el programa, el conjunt de fitxers de text resultants, on es troben les instruccions, es diu que contenen el **codi font**.

* La **compilació** és la traducció del codi font en fitxers en format binari que contenen les intruccions en un format que el processador pot entendre.

--

## Codi objecte i codi executable

* El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però aquest encara no pot ser executat per l'ordinador.

* El **codi executable** és la traducció completa a codi màquina, duta a terme per l'enllaçador (o **linker**). El codi executable és interpretat directament per l'ordinador.

--

## Linker i llibreria

* El **linker** és l'encarregat d'inserir al codi objecte les funcions de les llibreries que són necessàries per al programa generant un arxiu executable.

* Una **llibreria** és una col·leció de codi predefinit que facilita la tasca del programador a l'hora de codificar un programa.

--

## Procés de transformació codi font a executable

![](/img/ic10m05u1_01.png)

---

## Fases del desenvolupament dels sistemes d'informació
### Metologia Mètrica v3.0

* Desenvolupada pel Ministeri d'Administracions Públiques.

* Es tracta d'una metodologia per la **planificació**, **desenvolupament** i **manteniment** de **sistemes d'informació** d'una organització.

--

## Fases principals Mètrica v3.0

![](/img/ic10m05u1_14.png)

--

## Fase 1. Estudi de viabilitat del sistema

* Analitzar un conjunt concret de necessitats, utilitzant criteris relacionats amb aspectes **econòmics, tècnics, legals i operatius**.

* Els resultats de l'estudi de viabilitat del sistema constituiran la base per prendre la decisió de seguir endavant o abandonar el projecte.

--

## Fase 2. Anàlisi del SI

* Aconseguir **l'especificació detallada** del sistema d'informació, per mitjà d'un catàleg de requisits i d'una sèrie de models.

* Primer es descriu el SI, es delimita el seu abast, es genera un catàleg de requisits generals i es descriu el sistema mitjançant uns models inicials d'alt nivell.

--

## Fase 2. Anàlisi del SI

* Es recullen els **requisits funcionals** que el SI ha de cobrir.

* S'identifiquen els **requisits no funcionals**, és a dir, les **facilitats** que ha de proporcionar el sistema, i les **restriccions** a què estarà sotmès.

* S'elaboren **models de casos d'ús** i **de classes** i es defineixen les **interfícies d'usuari**.

--

## Fase 3. Disseny del SI

* Obtenir la definició de l'arquitectura del SI i de l'entorn tecnològic que li donarà suport.

* Es generen les especificacions per a la construcció del SI:
    * Els **components del sistema** (mòduls/classes) i **estructura de dades**
    * Els procediments de **migració**
    * La definició i revisió del **pla de proves**
    * L'especificació dels requisits **d'implantació**

--

## Fase 4. Construcció del SI

* Té com a objectiu la **construcció i prova** dels diferents **components del SI**.

* Es desenvolupen els **procediments d'operació i de seguretat**, i s'elaboren els **manuals** d'usuari final i d'explotació.

--

## Fase 5. Implantació i acceptació del SI

* Té com a objectiu el **lliurament** i **l'acceptació** del sistema, i també donar el pas a **producció del sistema**.

* Un cop revisada l'estratègia d'implantació, s'estableix el **pla d'implantació** i es detalla **l'equip** que el portarà a terme.

---

## Metodologies Agile

<iframe width="900" height="500" src="https://www.youtube.com/embed/mCvIg01KnZ0?rel=0;autoplay=0" frameborder="0" allowfullscreen data-autoplay></iframe>

---

## Metodologia SCRUM

<iframe width="900" height="500" src="https://www.youtube.com/embed/PlLHc60egiQ?rel=0;autoplay=0" frameborder="0" allowfullscreen data-autoplay></iframe>