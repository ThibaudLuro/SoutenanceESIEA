---
layout: cover
title: Soutenance Thibaud Luro
---

<h1 flex="~ col">
<div text-2xl origin-top-left transition duration-500 op50>
  <span>Bonjour et Bienvenue </span>
</div>
<div mt1 text-5xl>Soutenance de fin d'études</div>
</h1>

<div abs-br mx-10 my-11 flex="~ col gap-4 items-end" text-left>
  <span>ESIEA</span>
  <div text-xs opacity-75 mt--4>11 Juillet 2024</div>
  <!-- <img src="/frontend-nation.svg" w-35 /> -->
</div>

<!--

-->

---
layout: center
class: text-center
---

<div text-2xl transition duration-500 :class="$clicks <= 0 ? 'scale-150 translate-y-15' : 'op50'">
  <span>Qui Suis-Je ?</span>
</div>

<div mt1 text-4xl forward:delay-300 v-click>Thibaud Luro</div>
<div mt4 text-2xl forward:delay-300 op80 v-click>Étudiant en S10 à l'ESIEA Dax</div>
<div mt1 text-2xl forward:delay-300 op80 v-click>Filière Ingénierie du logiciel</div>


---
title: Timeline horizontale
---

# Mon Parcours

<div mt-8>
  <div v-click="1">
    <div op80>2019</div>
    <div text-2xl>Baccaluaréat Scientifique</div>
    <div op80>Spécialité Mathématiques option S.V.T</div>
  </div>
  <div mt4 text-right v-click="2">
    <div op80>2019 - 2024</div>
    <div text-2xl>ESIEA</div>
    <div op80>Expert en ignénierie logiciel</div>
  </div>
  <div mt4 v-click="3">
    <div op80>2022</div>
    <div text-2xl>Stage Holis Consulting</div>
    <div op80>6 mois en tant que développeur web full stack</div>
  </div>
  <div mt4 text-right v-click="4">
    <div op80>2022 - 2024</div>
    <div text-2xl>Alternance Holis Consulting</div>
    <div op80>2 ans en tant que développeur web full stack</div>
  </div>
</div>


<!--
1/ Pédagogie par projets et intérêt pour l'informatique

2/ Holis pour le côté jeune et tout à faire.

3/ Ca m'a plu et l'entreprise était contente de moi
-->

---
growHue: 40
layout: cover
title: Soutenance Thibaud Luro
---

<h1 flex="~ col">
<div text-2xl origin-top-left transition duration-500 :class="$clicks <= 0 ? 'scale-150' : 'op50'">
  <span>Problématique</span>
</div>
<div mt1 text-4xl forward:delay-300 v-click>Comment la digitalisation peut-elle transformer les méthodes de travail dans l'industrie pour améliorer l'efficacité ?</div>
</h1>

<!--
1/ peine encore à se digitaliser (beaucoup de tâches manuelles et chronophages qui pourraient être automatisées)

2/ Les entreprises ayant transitionné vers des solutions digitales ont observé une augmentation de leur productivité de 15 à 25 %. D'aprés une étude de la société McKinsey & Company

3/ Un des outils vendu par la société pour laquelle je travaille a augmenté de 30% la productivité (étude menée par le client de la solution)

-->


---
growHue: 40
grow: right
class: flex flex-col items-start justify-center
---

## Ma position par rapport à la problématique

<div mt5 v-click>
  S'inscrit dans mon expérience professionnelle
</div>

<div mt4 relative>
<span v-click>Utilité des réalisations</span>
</div>

<!--

1/ J'ai choisi cette problématique car parfaite adéquation avec mon expérience professionnelle jusqu'à présent

2/ Une grande partie de ce qui m'attire en informatique est le fait de savoir que sa réalisation est utile à quelqu'un
-->



---
growHue: 40
grow: right
class: flex flex-col items-start justify-center
---

## Opportunités découlant de la problématique

<div mt5 v-click>
<span font-bold text-blue>Pour moi</span> : Travail sur projets innovants et techniques
</div>

<div mt4 v-click>
<span font-bold text-yellow>Pour la société</span> : Services à moindre coût
</div>

<div mt4 v-click>
<span font-bold text-green>Pour la planète</span> : Production plus durable
</div>

<!--

Opportunités pour moi :
- Me permet de travailler sur des projets techniques et innovants

Société : 
- Efficacité => coûts réduits

Planète : 
- Optimisation => Moins de production de co2
- Moins d'erreurs humaines => Moins catastrophe éco
-->

---
layout: center
class: text-center
growX: 50
growY: 100
---

<h1 important-text-5xl>Contexte</h1>

<div text-white:50 text-2xl v-click>
Mon expérience
<span text-lightblue italic v-mark.blue.underline.delay300="1">professionnelle</span> 
jusqu'à présent
</div>

<!--

-->


---
class: text-2xl
grow: right
title: Make things easier!
---

# Expérience <span font-hand text-lightblue scale-110 ml3 inline-block>Professionnelle</span>

<div flex="~ gap-2 items-center" text-lightblue mt-15 v-click>
  <span>HOLIS CONSULTING</span>
</div>

<div grid="~ cols-[max-content_min-content_auto] items-center gap-6" py8 px3>
  <div flex="~ gap-2 items-center" relative v-click>
    <div w-35px h-45px border="l b gray/30" left-0 bottom-15px absolute />
    <div text-purple i-ph-magnifying-glass-duotone text-2xl ml-12/>
    <span>Création</span>
  </div>
  <div i-ph-arrow-right-duotone op50 v-click />
  <div v-after>Février 2020 À Pau en Nouvelle Aquitaine</div>

  <div flex="~ gap-2 items-center" relative v-click>
    <div w-35px h-56px border="l b gray/30" left-0 bottom-15px absolute />
    <div text-green i-ph-book-bookmark-duotone text-2xl ml-12/>
    <span>Effectif</span>
  </div>
  <div i-ph-arrow-right-duotone op50 v-click />
  <div v-after>Quinzaine de salariés</div>

  <div flex="~ gap-2 items-center" relative v-click>
    <div w-35px h-56px border="l b gray/30" left-0 bottom-15px absolute />
    <div text-amber i-ph-currency-circle-dollar-duotone text-2xl ml-12/>
    <span>Chiffre d'affaires</span>
  </div>
  <div i-ph-arrow-right-duotone op50 v-click />
  <div v-after>1.5 Millions d'euros en 2023</div>
</div>

<!--

-->

---
growX: 100
growY: 80
---

### Secteurs d'Activité

<div>
<h1>Principaux secteurs</h1>

<div flex justify-around mt35>

<div v-click flex="~ col items-center gap-2">
<div text-6xl text-yellow i-ph-hard-hat-fill />
<h3 w-40 text-center>Ingénierie d'inspection</h3>
</div>

<div v-click flex="~ col items-center gap-4">
<div text-6xl text-purple i-ph-desktop-fill />
<h3 w-60 text-center>Développement de solution digitales</h3>
</div>

</div>

</div>


<!--

-->

---
growX: 100
growY: 80
---

### Secteurs d'Activité

<div>
<h1>Ingénierie d'inspection</h1>
<img src="/SiteIndustrielNoBg.png" rounded-lg w-120 mt-10 />
</div>

<div absolute left-120 top-30 transition duration-800 translate-x-30 translate-y-15 scale-120>

<v-clicks>

- Prestations d'ingénierie d'inspection

- Contrôle d'éléments sur site

- Majorité du chiffre d'affaire

</v-clicks>
</div>


<!--
1/ Secteur important car lié à mes activités

2/ Représentation site indus

3/ Exemple durée de vie tuyau
-->

---
growX: 100
growY: 80
---

### Secteurs d'Activité

<div>
<h1>Développement de solutions digitale</h1>
<div w-100>
```vue
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
```

</div>
</div>

<div absolute left-120 top-30 transition duration-800 translate-x-15 translate-y-30 scale-120>

<v-clicks>

- Moderniser le milieu de l'inspection

- Eviter les erreurs humaines

- Automatiser les tâches chronophages

</v-clicks>
</div>


<!--

-->

---
layout: center
class: text-center
growX: 50
growY: 0
---

<h1 important-text-5xl>Utilité des solutions d'Holis</h1>

<h3 v-click text-white:50>S'adressant à des <b text-white:75 font-bold>ingénieurs</b> travaillant depuis des <b text-white:75 font-bold>bureaux</b></h3>

<!--
1/ Expliquer App Web
-->

---
class: grid grid-cols-[640px_auto] gap-6 items-center justify-center
grow: right
---

<img src="/alis.png" class="border border-2 border-gray-300 shadow-lg" alt="Premis DM Image">

<div flex="~ col gap-4" text-right>
<div text-4xl>Alis</div>
<div op50 v-click>Modélisation d'un <code>site industriel</code> en 3D</div>
</div>

<!--
1/ Représentation 3D du site industriel du client

2/ Réunion avant entrée sur site afin de localiser les éléments nécessitant un contrôle

3/ Suivi de l'état de santé de son site industriel de manière visuel en répertoriant les différents dommages aux éléments 3D
-->

---
class: grid grid-cols-[auto_640px] gap-4 items-center justify-center
grow: left
---

<div flex="~ col gap-4">
<div text-4xl>Premis DM</div>
<div op50 v-click>Contrôle du <code>format</code> et <code>cohérance</code> des données</div>
</div>

<img src="/premis.png" class="border border-2 border-gray-300 shadow-lg" alt="Premis DM Image">

<!--
1/ Moins visuelle mais sujet de mon alternance donc REFERENCES plus tard

2/ Format des données : Nb char nom tuyau (normes des industrie)

2/ Cohérence : Turbine représentée dans le bon secteur du site industriel


-->

---
grow: right
class: text-center
title: What Makes a Good Tool?
clicks: 7
---

<div transition duration-800 :class="$clicks < 2 ? 'translate-y-45' : ''" relative>

# Quelles sont les compétences <span v-mark.linethrough.red.delay200="{at:1,roughness:6,seed:146}" transition inline-block :class="$clicks >= 1 ? 'op50' : ''"> requises</span> ?

<div font-hand bold absolute rotate--4 left-150 top-10 text-3xl text-purple2 delay-300 v-click>Essentielles</div>

</div>

<h4 text-left transition duration-400 absolute bottom-5 :class="$clicks >= 6 ? 'op70' : 'op0'">Classées par niveau de maîtrise croissant</h4>

<div flex justify-around gap-20 mt25>
<div relative transition duration-400 forward:delay-600>
<v-clicks>

<h3 font-semibold>Humaines</h3>

<div flex="~ col gap-4" mt4>
<div>Communication <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 60% </h4></div>
<div>Gestion de projet <h4 transition duration-400 :class="$clicks >= 7 ? 'op50 block' : 'op0'"> Maîtrisé 90% </h4></div>
<div>Gestion du temps <h4 transition duration-400 :class="$clicks >= 7 ? 'op50 block' : 'op0'"> Maîtrisé 95% </h4></div>
</div>
</v-clicks>
</div>

<div relative transition duration-400 forward:delay-600>
<v-clicks>

<h3 font-semibold>Techniques</h3>

<div flex="~ col gap-4" mt4>
<div>Base de données (PotsgreSQL) <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 80% </h4></div>

<div>Framework d'application web (React) <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 85% </h4></div>
<div>API rest (Express JS) <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 90% </h4></div>
</div>
</v-clicks>

</div>
</div>

<!--
2/ Communication entre membres de l'équipe mais aussi avec les parties prenantes (client qui est interne à l'entreprise)

3/ Gestion de projet pour assurer un suivi de l'avancement et garder des objectifs clairs et atteignables

4/ Gestion du temps pour utiliser son temps de travail efficacement

5/ Base de données pour stocker les données

6/ Framework pour réaliser la partie avec laquelle l'utilisateur va directement intéragir (partie qui a besoin des données)

7/ Backend : Transit entre la base de données et le front

8/ Expliquer pourcentages

9/ Compétenance la plus faible communication (premier pas)

10/ Mes compétencenes les plus fortes 

11/ Représente mon éventail de compétences me permettant d'exercer mon activité professionnelle et de réaliser des produits capables de répondre à la problématique

-->


---
growX: 50
growY: 130
class: flex flex-col items-center justify-center
title: Nuxt
---

<h1 forward:delay-400 text-center important-text-5xl font-600 important-leading-1.1em>Plus de détails<br><span>Sur mes compétences</span></h1>

<!--

-->

---
layout: center
class: text-center
growHue: 70
growX: 50
growY: 0
---

<h1 important-text-5xl>Comptétences <span font-bold>Humaines</span></h1>

<h3 v-click text-white:50>Leur <b text-white:75 font-bold>utilistation</b> dans le cadre de notre <b text-white:75 font-bold>problématique</b></h3>

<!--
1/ Répondent indirectement à la problématique
-->

---
layout: center
class: text-center
growHue: 120
growX: 50
growY: 0
---

<h1 important-text-5xl>1/ Gestion de Projet</h1>

<h3 v-click text-white:50>Compétence humaine permettant de <span text-pink font-bold v-mark.highlight.pink.op5.delay200="1" inline-block p3 mx--2>"mener à bien"</span> un projet</h3>

<!--
1/ Compétence centrale dans mon profil.

2/ C'est celle qui permet de garder le projet dans la bonne direction.

3/ Développement dans les temps et en adéqauation avec le besoin utilisateur
-->

---
grow: bottom
growHue: 120
---

# Gestion de projet

<div text-white:50 mt5 mb5>
Fonctionnement pour le projet PremisDM
</div>

<v-clicks>
Fonctionnement en sprints

- Réunions hebdomadaires

- Utilisation de l'outil Notion

</v-clicks>

<img src="/notion.png" absolute bottom-0 left-0 ml-20 w-200 transition duration-400 :class="$clicks >= 1 ? 'op100' : 'op0'">

<!--
1/ Pour PremiDM nous sommes passés par plusieurs systèmes de gestion de projet mais aujourd'hui fonctionnement en sprint (expliquer)

2/ Réunions hebdomadaires sur l'état de l'avancement et le reste à faire. Partage des difficultés si besoin d'aide

3/ Là où c'est intéressant c'est que Gestion seul du projet

4/ C'est aujourd'hui moi qui transforme le besoin client en fonctionnalité et qui en estime de temps nécessaire pour transofmrer ce besoin en foncitonnalité

5/ Nous utilisons l'outil Notion un outil complet permettant la prise de notes comme la possibilité de faire suivre des tâches dans un tableau d'avancement.
</div> -->


---
layout: center
class: text-center
growHue: 170
growX: 50
growY: 0
---

<h1 important-text-5xl>2/ Gestion du Temps</h1>

<h3 v-click text-white:50>Compétence humaine permettant d' <span text-orange font-bold v-mark.highlight.orange.op5.delay200="1" inline-block p3 mx--2>"optimiser"</span> ses ressources</h3>

<!--
1/ Pour pouvoir respecter les délais des tâches qui a été définie dans la partie gestion de projet et éviter des situations de stress

2/ Une bonne gestion de son temps de travail permet d'être le plus efficace possible 

3/ Tout en faisant attention à garder du recul sur ce qui est fait sans avancer comme on dit avec la tête dans le guidon.
-->

---
grow: bottom
growHue: 170
---

# Gestion du temps

<div text-white:50 mt5>
Comment je gère mon temps de travail
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<h3 v-click="1">
  Définition d'objectifs quotidiens 
</h3>
<h3 v-click="2">
  Méthode Pomodoro
</h3>

<div v-click="1" text-sm>

Vision claire des tâches à accomplir

- Alignés avec les priorités

</div>

<div v-click="2" text-sm>

Technique d'organisation du temps de travail en cycle

- 25 minutes de temps de travail pour 5 mintutes de pause

</div>
</div>

<!-- 

1/ Rester concentré et motivé

2/ Place les tâches les plus complexes en haut du panier pour avoir le plus d'énergie possible

3/ Cela m'a permis de répondre aux attentes de mes supérieurs en entreprise mais aussi de les dépasser en livrants des résultats dans des délais serrés


4/ Méthode pomodoro je l'utilise plus dans un contexte personnel pour la réalisation de mes projets

5/ Permet de me concentrer intensément sans distractions qui sont plus présentes chez moi qu'en entreprise

6/ 25min puis 5min répétées X fois

7/ Fonctionne très bien sur moi
 -->

---
layout: center
class: text-center
growHue: 220
growX: 50
growY: 0
---

<h1 important-text-5xl>3/ Communication</h1>

<h3 v-click text-white:50>Compétence humaine permettant de <span text-lime font-bold v-mark.highlight.lime.op5.delay200="1" inline-block p3 mx--2>"transmettre"</span> efficacement des informations</h3>

<!--
1/ Essentielle dans une équipe de développement pour avancer dans la même direction
-->

---
grow: bottom
growHue: 220
---

# Communication

<div text-white:50 mt5 mb5>
L'importance de la communication dans les projets
</div>

<v-clicks>
  Échanges avec le pôle développement de la société

- Partage des difficultés et des succès

- Eviter de refaire des fonctionnatlités déjà développées
</v-clicks>

<!--
1/ Même si nous ne travaillons pas sur les même projets

2/ En échangeant régulièrement, on arrive à identifier les obstacles potentiels tôt et trouver des solutions ensemble.

3/ De plus la plupart des projets sont étroitements liés de par le secteur visé qui est similaire

4/ Evite de refaire des fonctionnalités

5/ Cela permet également de célébrer les succès et de maintenir une bonne dynamique de groupe.
-->

---
layout: center
class: text-center
growHue: 150
growX: 50
growY: 0
---

<h1 important-text-5xl>Comptétences <span font-bold>Techniques</span></h1>

<h3 v-click text-white:50>Leur <b text-white:75 font-bold>utilistation</b> dans le cadre de notre <b text-white:75 font-bold>problématique</b></h3>

<!--
1/ S'attarder sur les compétences techniques car c'est celles qui vont nous permettre de répondre au mieux à la problématique

2/ Permettent des développer des solutions utiles à l'industrie
-->


---
growHue: 150
grow: right
---

# Les défis à relever

<p>Afin de délivrer une application web <b>simple, efficace et utile</b></p>

<div absolute left-29 top-35 w-80 transition duration-800 v-click="1" :class="$clicks <= 3 ? 'translate-x-50 translate-y-10 scale-150' : '' ">
  <img src="/breaking-changes-floors.png" absolute inset-0 op75>
  <div font-hand absolute left-0 top-39>Application fonctionnelle</div>
  <div font-hand absolute right-0 top--6 transition duration-800>Application robuste</div>
  <img src="/breaking-changes-stairs-right.png" absolute inset-0 v-click="3">
  <img src="/breaking-changes-stairs-left.png" absolute inset-0 v-click="2">
</div>

<div absolute left-15 bottom-10 transition duration-800 :class="$clicks <= 3 ? 'translate-x-20 translate-y--13  scale-120' : '' ">
<div flex="~ gap-2 items-center" text-yellow3 mt-8 mb2 text-xl v-click="2">
  <div i-ph-escalator-down-duotone text-2xl scale-x--100 />
  <span>Aspect FrontEnd</span>
</div>

<v-clicks at="5">

- Garder une utilisation fluide et rapide pour l'utilisteur
- Réussir à proposer une interface claire et simple

</v-clicks>
</div>

<div absolute left-120 top-30 transition duration-800 :class="$clicks <= 3 ? 'translate-x-35 translate-y-35 scale-120' : '' ">
<div flex="~ gap-2 items-center" text-blue mt-8 mb2 text-xl v-click="3">
  <div i-ph-escalator-up-duotone text-2xl />
  <span>Aspect BackEnd</span>
</div>

<v-clicks at="7">

- Délivrer efficacement de grands volumes de données
- Sécuriser l'accès aux données
- Assurer la scalabilité

</v-clicks>
</div>

<!--
1/ Comment répondre aux besoin de l'industrie avec une app web

2/ MVP montrable à des potentiels clients pour juger l'intérêt

3/ C'est moi qui suit à l'origine du projet et qui ai pensé en partie son architecture. 

4/ Le défi a été de transitionner d'un projet fonctionnel à robuste (sujet toujours d'actualité)

5/ Princiapl défi : travail avec de forts volumes de données

6/ Enoncer aspects à travailler pour répondre au besoin énoncé plus tôt

7/ Dérouler les étapes

8/ Expliquer sécurité et scalabilité
-->


---
layout: center
class: text-center
growHue: 200
growX: 50
growY: 0
---

<h1 important-text-5xl>1/ Développement FrontEnd React</h1>

<h3 v-click text-white:50>Compétence technique permettant de réaliser une <span text-yellow font-bold v-mark.highlight.yellox.op5.delay200="1" inline-block p3 mx--2>"Interface Utilisateur"</span></h3>

<!--
1/ Découvert avec la technologie angular à l'école 

2/ Approfondie en entreprise avec la technologie React
-->


---
grow: right
growHue: 200
---

# FrontEnd React

<div text-white:50 mt3 mb6>
Les <b text-white:75 font-bold>défis</b> impliquant la mise en application de la compétence par rapport à notre problématique :
</div>

<div flex="~ col gap-4" pt6>

<div text-xl text-white:50 v-click>
Travail avec de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Garder une utilistaion fluide et rapide pour l'utilisteur
  </div>
</div>

</div>

<!--
1/ Défis auquel j'ai du faire face personnellement
-->

---
grow: bottom
growHue: 200
---

# FrontEnd React

<div text-white:50 mt5 mb5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div>
Problème de surcharge mémoire

</div>
<div flex="~ gap-2 items-center" mt4 v-click><div i-ph-arrow-bend-down-right-duotone op50 />Extraction de données à partir de fichiers excel</div>

<div text-6xl flex="~ gap-8 items-center" mt25 ml80 transition duration-400 :class="$clicks >= 1 ? 'op100' : 'op0'">

<div i-ph-microsoft-excel-logo-fill />

<div i-ph-arrow-right-fill />

<div i-ph-database-bold />

</div>

<!--
1/ Expliquer fonctionnalité Excel

2/ Besoin de mémoire vive qui sature si trop énergivore

3/ Problème à l'arrivée de données test par client

4/ Du réfléchir à des solutions moins communes que les implémentations classiques de React.

4/ Proposition de l’implémentation de Workers qu’il a tout de suite acquiescée. 
-->


---
grow: bottom
growHue: 200
---

# FrontEnd React

<div text-white:50 mt5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div grid="~ flex justify-center gap-x-2" mt5>
<div flex="~ gap-2" v-click="1">
  <div i-logos-npm-icon />
  Mise en place de workers
</div>

<div v-click="1">

  <img
    src="/worker.jpg" w-150 transition duration-500 class="origin-[35%_50%]"
  />

</div>
</div>

<!--
1/ Une instance princiaple s'occupe de toute l'extraction

2/ Avec workers délégation de ce travail à de nouvelles instances

3/ Les workers communiquent avec l'instance principale pour signaler l'avancement de la tâche

4/ Parallélisme, ils fonctionnent meme temps

5/ Détruits pour économiser de la mémoire
 -->


---
grow: bottom
growHue: 200
---

# FrontEnd React

<div text-white:50 mt5 mb5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<v-clicks>
Mise en place de workers

- Performances de l'application

- Plus aucune surcharge mémoire

</v-clicks>

<!--
1/ Corrigeant le problème de mémoire et fluidifiant grandement le processus.

2/ Temps d'opération divisé par 4 (outils d'analyse de moi)

3/ Aujourd'hui le système a encore été repris par mon maître d'apprentissage basculant cette manipulation côté backend avec un sytème de streaming des fichiers (lecture de ceux-ci par morceaux)

4/ Possibilité de mieux mais pas eu la vision aussi large de par manque d'expérience et conscience des possibles

5/ Surtout permis de mettre en lumière la mise en place d'optimisations similaires dans l'app
 -->

---
grow: bottom
growHue: 200
---

# FrontEnd React

<div text-white:50 mt5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<div v-click="1" op80 mb2>
  Affichage lent de certaines pages
</div>

<div v-click="2"  op80 mb2>
  Navigation non fluide
</div>

<h3 v-click="3">
  Lazy Loading
</h3>
<h3 v-click="4">
  Infinite Scrolling
</h3>

<div v-click="3" text-sm>

Chargement des données uniquement lorsque celles-ci sont nécessaires

- Temps de chargement des pages moindre

</div>
<div v-click="4" text-sm>

Chargement des données au scroll (dans une liste de données ou tableau)

- Temps de chargement initial moindre

- Contrer la surcharge mémoire

</div>
</div>

<div absolute bottom-10>
<span text-2xl v-click="5">Addtionner</span> <span v-click="5" op50> ces bonnes pratiques permet d'arriver à une solution robuste</span>
</div>

<!-- 
1/ Liste de tous les points bloquants

2/ Premier point Temps de chargement long de certaines pages ce qui est regrétable car fait perdre du temps

3/ Deuxième point : Navigation lente dans de longues listes de données (saccadé / désagrable à l'utilisation)

4/ le lazy loading expliquer

5/ Infinite scrolling (explqieur)

6/ Temps d'affichage initail jusqu'à 1 minute (inconcevable)

7/ Maintenant en milisecondes

8/ Addition

9/ Phase d'optimisation quasi terminée front mais surtout côté back
 -->

---
layout: center
class: text-center
growHue: 250
growX: 50
growY: 0
---

<h1 important-text-5xl>2/ Développement BackEnd</h1>

<h3 v-click text-white:50>Compétence technique permettant <span text-green font-bold v-mark.highlight.green.op5.delay200="1" inline-block p3 mx--2>"Le transit et le stockage de Données"</span></h3>

<!--
1/ On va parler ici du côté API et BDD

2/ Découvert avec la technologie Java et MySQL à l'école 

3/ Approfondie en entreprise avec la technologie ExpressJS et PostgreSQL
-->

---
grow: right
growHue: 250
---

# BackEnd

<div text-white:50 mt3 mb6>
Les <b text-white:75 font-bold>défis</b> impliquant la mise en application de la compétence par rapport à notre problématique :
</div>

<div flex="~ col gap-4" pt6>

<div text-xl text-white:50 v-click>
Travail avec de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Délivrer efficacement ces données (rapidement et sans surcharge mémoire)
  </div>
</div>

<div text-xl text-white:50 v-click>
Délivrer les données de manière <span flex="inline gap-1 items-center" text-red translate-y-0.6><div i-ph-lock-key-fill />sécurisée</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    S'assurer de la provenance de requêtes
  </div>
</div>

<div text-xl text-white:50 v-click>
Anticiper en mettant l'accent sur la <span flex="inline gap-1 items-center" text-orange translate-y-0.6><div i-ph-chart-bar />scalabilité</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Prendre du recul afin de prévoir de futurs problèmes
  </div>
</div>

</div>

<!--
1/ Défis auxquels j'ai fait face à l'aide de mes compétences
-->



---
grow: right
growHue: 250
---

# BackEnd API Express

<div text-white:50 mt5 mb5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div>
Problème de surcharge mémoire

</div>
<div flex="~ gap-2 items-center" mt4 v-click><div i-ph-arrow-bend-down-right-duotone op50 />Exécution des checks de données</div>

<div text-6xl flex="~ gap-8 items-center" mt25 ml55 transition duration-400 :class="$clicks >= 1 ? 'op100' : 'op0'">

<div i-ph-database-bold />

<div i-ph-arrow-right-fill />

<div i-ph-cpu />

<div i-ph-arrow-right-fill />

<div i-ph-check />

</div>

<!--
1/ Rappel de la notion de check

2/ 
Algo back qui Exécute une série d'action pour vérifier : 
- La taille des chaines de charactères 
- Exécution de requetes en base de données pour vérifier présence de donnée sur une partie du site industriel

3/ Rappel utilisation mémoire

4/ Problème de mémoire avec arrivée de nouvelles données
-->


---
grow: bottom
growHue: 250
---

# BackEnd API Express

<div text-white:50 mt5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<h3 v-click="1">
  Stockage en cache
</h3>
<h3 v-click="2">
  Batch processing
</h3>

<div v-click="1" text-sm>

Conservation temporaires de données récurrentes

- Accès rapide

- Économie de coûts

</div>

<div v-click="2" text-sm>

Gestion des données par lots

- Gestion de la charge mémoire

- Fiabilité du processus

</div>
</div>

<!-- 

1/ Beaucoup de requetes similaires

2/ Stockage des résulats dans le cache pour rapidité

3/ Caching simple mais ambitions de passer sur un service plus complexe d'ici peu de temps tels que Redis

4/ Batch partout dans le bakcend (opérations crud) pour le tratement de données (ligne par ligne)

5/ Système concu pour gérer gran nb données

6/ Fiabilité : Moins de surpirse toujouts meme nb lignes

7/ Aujourd'huipas de pb mémoire mais un nouveau problème c'est la lenteur d'exécution.

8/ Pas encore mis en place mais ouverture sur l'adoption de micro services avec un langage bas niveau donc plus proche de la machine (worker plus poussé avec beaucoup plus de controle sur tout ce qui va etre gestion de la mémoire)

-->


---
grow: right
growHue: 250
---

# BackEnd API Express

<div text-white:50 mt5 mb5>
Mise en application de la compétence pour assurer la <span flex="inline gap-1 items-center" text-red translate-y-0.6><div i-ph-lock-key-fill />sécurité</span>
</div>

<div>
Failles de sécurité sur la version de démonstration

</div>
<div flex="~ gap-2 items-center" mt4 v-click><div i-ph-arrow-bend-down-right-duotone op50 />Failles SQL permettant la récupération de données sensibles</div>

<div text-6xl flex="~ gap-8 items-center" mt25 ml55 transition duration-400 :class="$clicks >= 1 ? 'op100' : 'op0'">

<div i-ph-call-bell />

<div i-ph-arrow-right-fill />

<div i-ph-skull />

<div i-ph-arrow-right-fill />

<div i-ph-folder-simple-lock-duotone />

</div>

<!--
1/ Il faut que je vous parle de quelque chose dont je ne suis pas fier mais qui a eu lieu

2/ Sur la version de démonstration failles sql connues dans le milieu (expliquer)

3/ Ce ne nous a pas causé de tort car l'application n'était pas en production

4/ Rappel sur l'imporance de la sécurité

5/ Fonctionnalité Custom Request avec modification du contenu alors récupération de n'importe quelle donnée de la base
-->


---
grow: bottom
growHue: 250
---

# BackEnd API Express

<div text-white:50 mt5>
Mise en application de la compétence pour assurer la <span flex="inline gap-1 items-center" text-red translate-y-0.6><div i-ph-lock-key-fill />sécurité</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<h3 v-click="1">
  Sanitisation des Données 
</h3>
<h3 v-click="2">
  Bouclier anti DDOS
</h3>

<div v-click="1" text-sm>

Valider et Filtrer les Entrées

- Empêcher un utilisateur d'obtenir certaines informations

</div>

<div v-click="2" text-sm>

Limiter le débit

- Éviter une extinction du système

</div>
</div>

<!-- 
1/ Contrer le problème avec Sanitisation

2/ 3 points :

- Réduction possibilités en liimitant colonnes et tables

- Echappement (texte et pas code)

- Prepared statements (non modifiable et connues de la base) => Aide à la performance

3/ Plus de problème de sécurité classique et connu

4/ Protection DDOS sur un projet personnel avec pour projet de le ramener dans PREMIS

5/ Grand nombre de requêtes dans un laps de temps très court qui provoque extinction du système

6/ Bloquer les requetes de l'ip procédant à l'attaque

 -->

---
grow: right
growHue: 250
---

# BackEnd BDD PostgreSQL

<div text-white:50 mt5 mb5>
Mise en application de la compétence pour assurer la <span flex="inline gap-1 items-center" text-orange translate-y-0.6><div i-ph-chart-bar />scalabilité</span>
</div>

<div>
Base de données peu performante

</div>
<div flex="~ gap-2 items-center" mt4 v-click><div i-ph-arrow-bend-down-right-duotone op50 />Gouleau d'étranglement</div>

<div text-6xl flex="~ gap-8 items-center" mt25 ml80 transition duration-400 :class="$clicks >= 1 ? 'op100' : 'op0'">

<div i-ph-database />

<div i-ph-arrow-right-fill />

<div i-ph-prohibit-bold />

</div>

<!--
1/ Dernier aspect scalabilité

2/ Après donénes bdd peu performante (10 min de récup de data pour une table)

3/ En partie du au fait que la bdd n'était pas du tout optimisée. Aucune mise en place spécifique
-->


---
grow: bottom
growHue: 250
---

# BackEnd BDD PostgreSQL

<div text-white:50 mt5>
Mise en application de la compétence pour assurer la <span flex="inline gap-1 items-center" text-orange translate-y-0.6><div i-ph-chart-bar />scalabilité</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<h3 v-click="1">
  Utilisation de vues
</h3>
<h3 v-click="2">
  Indexation en base de données
</h3>

<div v-click="1" text-sm>

Optimiser la récupération de données

- Base de données plus légère

</div>

<div v-click="2" text-sm>

Points de repères pour la base de données

- Accéder aux données plus rapidement

</div>
</div>

<!-- 
1/ 1ère étape repérer ces gouleau d'étranglement

2/ Création de tables inutes car uniquement utilisée en lecture

3/ Remplacement par des vues (expliquer)

4/ BDD beaucoup plus légère

5/ Récupération plus rapide car optimisation de ces requetes

6/ Indexation exemple avec libre et marque page

7/ Indexation sur les FK

8/ Aujourd'hui base de données 50x plus rapide que la première version fonctionnelle

9/ Fonctionne bien aujourd'hui mais pour prévoir le futur je vais commencer à imaginer la possibilité de shard la bdd (déouper en morceaux)
 -->

---
growHue: 60
grow: right
class: flex flex-col items-start justify-center
---

# Ma Légitimité

<div mt5 v-click>
<span>Potentiels clients surpris de la <span v-mark.underline.red="1">rapidité</span></span>
</div>

<div mt5 v-click>
<span>Gestion du projet Premis DM en <span v-mark.underline.purple="1">autonomie</span></span>
</div>

<div mt5 v-click>
<span>Possible adoption de la solution au niveau <span v-mark.underline.yellow="2">international</span></span>
</div>

<!--

1/ Ajd Premis parfait avec data de petit à moyen site indus

2/ Pas optimal pour de grand site industriels

3/ Après démo client la rapidité des apps est toujours relevère

4/ Confiance de l'entreprise en moi pour me laisser gérer le projet

5/ Je manage les personnes m'aidant sur le projet.

6/ Discussions internes chez un géant de l'industrie

7/ Ajd je me sens légitime de réaliser des solutions capables de transformer les méthodes de travail dans l'indus afin d'améliorer l'efficacité des sociétés les adoptant

8/ En espérent permettre une efficacité entrainant une baisse de prix profitable à la société

9/ Et une production plus durable pour la planète de par l'optimisation des processus
-->

---
grow: bottom
---

# Mon projet professionel à court et moyen terme

<div text-white:50 v-click="3" :class="$clicks > 3 && 'hidden'">
Envie de développer une activité parallèle</div>

<div text-white:50 v-click="5">
Plusieurs <span v-mark.box.teal.delay400="5" text-teal mx1>"étapes"</span> avant de lancer ma microentreprise</div>

<div absolute w-50 h-100 left-34 top-70 v-click>
  <img
    src="/me.png" absolute w-35 left-0 top-0 transition duration-500 class="origin-[35%_50%]"
    :class="$clicks === 3 ? 'scale-x--100' : $clicks > 3 ? 'forward:delay-400' : ''"
  />
  <img src="/progressive-mark-question.png" absolute w-12 left--8 top--12 v-click="[3,4]">
  <img src="/progressive-mark-bulb.png" absolute w-20 left-23 top--16 forward:delay-800 v-click="4" >
</div>

<div absolute w-230 right-0 top-13>
  <img
    src="/progressive-floors.png" duration-400
    v-click
    :class="$clicks >= 4 ? 'duration-700 forward:delay-200 op10' : ''"
  />
  <img src="/progressive-stairs.png" duration-400 absolute left-0 top-0 v-click="4">
</div>

<!--
1/ Envie de continuer mon activité au sein d'holis consulting (compétences)

2/ Passion pour le développement et une fascination des possibilités ouvertes par la profession

3/ Aujourd'hui utilisation de mon temps libre pour création d'une activité parallèle

4/ Plusieurs projets à mon actif mais présentation des 3 les plus pertinents

5/ Représente les étapes vers la construction d'un projet solide
-->


---
growX: 100
growY: 80
---

### Mon projet professionel à court et moyen terme

<div>
<h1>CliffJumpSpots</h1>
<img src="/cliff.webp" rounded-lg w-90 mt-10 />
</div>

<div absolute left-120 top-30 transition duration-800 translate-x-30 translate-y-15 scale-120>


<div flex="~ col gap-4" text-right>
<div text-2xl>Application Mobile Android</div>
<div w-80 v-click>Répertorier des emplacements propices à la pratique du Cliff Jump</div>
<div op50 w-80 v-click>Projet qui n'a pas eu de conclusion</div>
</div>

</div>


<!--
1/ Développé pendant ma deuxième année à l'esiea

2/ Epliquer le principe

3/ Objectif non clair avec ommanditaire vision floue de la mission (prjet jamais abouti)
-->

---
growHue: 80
growX: 100
growY: 80
---

### Mon projet professionel à court et moyen terme

<div>
<h1>YourNight</h1>
</div>

<div absolute left-0 top-30 transition duration-800 translate-x-25 translate-y-15 scale-120>

<div flex="~ col gap-4" text-left>
<div text-2xl>Application Mobile Android et IOS</div>
<div w-80 v-click>Faciliter l'organisation de soirées entre amis</div>
<div op50 w-80 v-click>Non test de l'intérêt</div>
</div>

</div>

<img src="/yournight.png" absolute left-170 rounded-lg w-60 mt--10 />



<!--
1/ Frustré donc définition clair d'objectifs

2/ Expliquer utilité

3/ Débuté il y a deux ans et 8 mois de dev

4/ Vouloir sortir un projet trop fini presque parfait sans avoir réellement testé un intérêt

5/ Non réussite à la fidélisation des utilisateurs
-->


---
growX: 100
growY: 80
---

### Mon projet professionel à court et moyen terme

<div>
<h1>KarmineNews</h1>
<img src="/karminenews.png" rounded-lg w-120 mt-10 />
</div>

<div absolute left-120 top-30 transition duration-800 translate-x-30 translate-y-15 scale-120>


<div flex="~ col gap-4" text-right>
<div text-2xl>Site Web</div>
<div w-80 v-click>Toutes les actualités du club esport Karmine Corp</div>
<div op50 w-80 v-click>Dans un unique but d'améliorer mes compétences en Marketing</div>
</div>

</div>


<!--
1/ Nouveau projet avec volonté de corriger les nouvelles erreurs

2/ Pas de businnes plan (projet communautaire)

2/ Expliquer le principe

3/ Test du marché avec un MVP sorti en 1 semaine
-->


---
grow: top-right
class: flex items-center justify-center
---

<div relative>
  <Tweet id="1797290752893947989" ml--45 mt-4 flex justify-center items-center transition class="important:[&_iframe]:w-80 important:[&_iframe]:rounded-13px" :class="$clicks > 1 ? 'op50 duration-600' : ''"/>

  <Tweet id="1797322399953682889" absolute top-15 left-5 class="important:[&_iframe]:w-100 important:[&_iframe]:rounded-13px important:[&_iframe]:shadow-xl" v-click />
</div>

<!--
1/ Campagne twitter car communauté sur ce réseau social

2/ obtention d'un intérêt de la communauté

3/ 10 à 20aine d'utilisateurs quotidiens

4/ Encourageant pour la suite et confiant de mes capacités à arriver au bout d'un projet plus concret
-->


---
layout: intro
class: text-center pb-5
growX: 50
growY: 120
---

# Merci de m'avoir écouté

Avez-vous des questions ?

<!--

-->