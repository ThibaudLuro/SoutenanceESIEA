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
Préciser que j'ai choisi l'esiea pour sa pédagogie et mon attrait déjà présent pour l'informatique.

Préciser que j'ai rejoint Holis pour le côté jeune entreprise et tout à faire.

Ca m'a plu et l'entreprise était contente de moi donc je suis resté en alternance
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

Aujourd'hui le monde de l'industrie peine encore à se digitaliser (beaucoup de tâches manuelles et chronophages qui pourraient être automatisées)

Les entreprises ayant transitionné vers des solutions digitales ont observé une augmentation de leur productivité de 15 à 25 %. D'aprés une étude de la société McKinsey & Company, nommée "The future of manufacturing: How digital technology is transforming the industry"

Un des outils vendu par la société pour laquelle je travaille a augmenté de 30% la productivité (étude menée par le client de la solution)

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

J'ai choisi cette problématique car parfaite adéquation avec mon expérience professionnelle jusqu'à présent

Une grande partie de ce qui m'attire en informatique est le fait de savoir que sa réalisation est utile à quelqu'un
-->



---
growHue: 40
grow: right
class: flex flex-col items-start justify-center
---

## Oppotunités découlant de la problématique

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
- Une industrie plus efficace peut mener à des produits de meilleure qualité à des coûts réduits, rendant ainsi les biens et services plus accessibles.

Planète : 
- Les technologies digitales peuvent contribuer à une production plus durable en optimisant l'utilisation des ressources, en réduisant les déchets et en minimisant l'empreinte carbone des processus industriels.
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
Applications web à la différence d'un site web qui permet simplement de donner des informations, images texte à l'image d'un blog

L'application web va offrir du contenu plus dynamique et permettre des interractions plus complexes et des tâches plus spécifiques (manipulation de données, communication en temps réel) comme une messagerie gmail ou un outil de comptabilité.

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
Utile pour réunion avant entrée sur site afin de localiser les éléments nécessitant un contrôle

Suivi de l'état de santé de son site industriel de manière visuel en répertoriant les différents dommages aux éléments 3D
-->

---
class: grid grid-cols-[auto_640px] gap-4 items-center justify-center
grow: left
---

<div flex="~ col gap-4">
<div text-4xl>Premis DM</div>
<div op50 v-click>Contrôle de <code>l'intégrité</code> et <code>cohérance</code> des données</div>
</div>

<img src="/premis.png" class="border border-2 border-gray-300 shadow-lg" alt="Premis DM Image">

<!--
Intégrité des données : Cette turbine est-elle liée à la bonne section du site industriel

Cohérence : L'état d'un tuyau ne peut pas être déclaré comme bon lorsqu'il a été vérifié pour la dernière fois il y a 5 ans

Sujet de mon alternance donc références à cette application web au cours de la présentation
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
<div>Base de données (SQL) <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 80% </h4></div>

<div>Framework d'application web (React) <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 85% </h4></div>
<div>API rest (Node + Express JS) <h4 transition duration-400 :class="$clicks >=7 ? 'op50 block' : 'op0'"> Maîtrisé 90% </h4></div>
</div>
</v-clicks>

</div>
</div>

<!--
Communication entre membres de l'équipe mais aussi avec les parties prenantes (client qui est interne à l'entreprise)

Gestion de projet pour assurer un suivi de l'avancement et garder des objectifs clairs et atteignables

Gestion du temps pour utiliser son temps de travail efficacement

Base de données pour stocker les données des applications

Framework pour réaliser la partie avec laquelle l'utilisateur va directement intéragir (partie qui a besoin des données)

Backend : Partie qui délivre les données (transit entre la base de données et le front)

Compétenance la plus faible aujourd'hui pour moi c'est communication, je ne fais pas toujours le premier pas meme si je m'oblige de plus en plus à le faire. Réticence ausssi d'aller voir le client par peur de poser des questions bêtes par exemple.

Mes compétencenes les plus fortes : Gestion du temps et Api

Représente mon éventail de compétences me permettant d'exercer mon activité professionnelle et de réaliser des produits capables de répondre à la problématique

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
Souhait de survoler mes compétences humaines car ce sont elles indirectement qui permettent de répondre à la problématique de par les enjeux qu'elles couvrent et ce qu'on va voir de suite.
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
Compétence centrale dans mon profil.

C'est celle qui permet de garder le projet dans la bonne direction.

Développement dans les temps et en adéqauation avec le besoin utilisateur
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
Pour PremiDM nous sommes passés par plusieurs systèmes de gestion de projet de par le statu de startup mais aujourd'hui fonctionnement en sprint (expliquer)

Réunions hebdomadaires sur l'état de l'avancement et le reste à faire. Partage des difficultés si besoin d'aide

Là où c'est intéressant c'est que Gestion seul du projet

C'est aujourd'hui moi qui transforme le besoin client en fonctionnalité et qui en estime de temps nécessaire pour transofmrer ce besoin en foncitonnalité

Nous utilisons l'outil Notion un outil complet permettant la prise de notes comme la possibilité de faire suivre des tâches dans un tableau d'avancement.

C'est un outil que j'utilise meme dans mes projets personnels pour la définition d'objectifs et la prise de note en général.
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
Pour pouvoir respecter les délais des tâches qui a été définie dans la partie gestion de projet et éviter des situations de stress, une bonne gestion de son temps de travail permet d'être le plus efficace possible tout en faisant attention à garder du recul sur ce qui est fait sans avancer comme on dit avec la tête dans le guidon.
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

Définition d'objectifs quotidier ca m'aide à rester concentré et motivé

Place les tâches les plus complexes en haut du panier pour avoir le plus d'énergie possible

Cela m'a permis de répondre aux attentes de mes supérieurs en entreprise mais aussi de les dépasser en livrants des résultats dans des délais serrés


Méthode pomodoro je l'utilise plus dans un contexte persoonnel pour la réalisation de mes projets

Permet de me concentrer intensément sans distractions qui sont plus présentes chez moi qu'en entreprise

Travailler de manière structurée et efficace pendant une période X de temps

Avec un rythme sain favorisant les pauses régulières.
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
Essentielle dans une équipe de développement pour avancer dans la même direction
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
Même si nous ne travaillons pas sur les même projets il est essentiel de communicquer entre nous

En échangeant régulièrement, on peut identifier les obstacles potentiels tôt et trouver des solutions ensemble.

De plus la plupart des projets sont étroitements liés de par le secteur visé qui est similaire donc parfois fonctionnalités ou comportements similaires dans les différentes solutions donc éviter de refaire quelque chose de déjà fait

Cela permet également de célébrer les succès et de maintenir une bonne dynamique de groupe.
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
Avec pour pilier les compétences humaines présentées précedemment, l'associtaion des compétences techniques va nous permettre de répondre à notre problématique

S'attarder sur les compétences techniques car c'est celles qui vont nous permettre de répondre au mieux à la problématique
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
Commencé à travailler sur Premis DM vers la fin de mon stage.

C'est moi qui suit à l'origine du projet et qui ai pensé en partie son architecture. 

De base volonté d'un projet fonctionnel (MVP) montrable à des potentiels clients pour juger l'intérêt

Le défi a été de transitionner d'un projet fonctionnel à robuste (sujet toujours d'actualité)

Principal défi et sujet qui va être au centre des prochaines explications c'est le travail avec de très forts volumes de données (données de tout un site industriel) (millions de lignes de données)

Comment faire en sorte qu'une application web puisse être toujours utilisable et utile aux acteurs du secteur industriel peu importe le nombre de données nécessaire à son fonctionnement
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
Compétence essentielle pour un web développeur 

découvert avec la technologie angular à l'école 

Approfondie en entreprise avec la technologie React

Aujourdhui je passe tout le temps par cette technologie
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
Rappel des défis à franchir pour servir le monde de l'industrie
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
Programme informatique utilise de la mémoire vive pour fonctionner et quand les tâches qu'il a à réaliser sont trop énergivores, la mémoire sature et le programme plante

Problème qu'on a eu sur notre première version fonctionnelle à l'arrivée de volumes de données plus conséquents que ce que l'on connaissait

Du réfléchir à des solutions moins communes que les implémentations classiques de React. 

Après m’être renseigné sur le sujet j’ai proposé à mon maître d’apprentissage l’implémentation de Workers qu’il a tout de suite acquiescée. 
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

Boulanger principal qui s'occupe de la plupart des tâches : prendre les commandes, faire le pain, servir les clients, etc.

Tellement de clients qu'il est difficile pour le boulanger de tout gérer à la fois. 
Il doit prendre les commandes, préparer les pains, cuire les pains, et tout ça en même temps. Cela peut devenir très lent et les clients doivent attendre longtemps.

Le Worker
Pour aider le boulanger, tu engages un assistant (le worker). 
Cet assistant peut faire des tâches spécifiques de manière autonome. Pétrir la pâte ou de surveiller les pains dans le four. 
Ainsi, le boulanger peut se concentrer sur les tâches plus importantes ou prendre plus de commandes.

Dans le contexte d'une application web, un worker est un peu comme cet assistant. Quand ton application a des tâches lourdes ou chronophages (Extraction de données de fichiers Excel), elle peut les déléguer à un worker. Le worker s'occupe de ces tâches en arrière-plan pendant que l'application principale continue de répondre rapidement aux utilisateurs.

</div> -->


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
L'implémentation de Workers est arrivée comme une solution ingénieuse. Corrigeant le problème et fluidifiant grandement le processus d'import.

L'adoption de cette approche a marqué un tournant dans le développement de Premis. Mettant en lumière la possibilité de mettre en place des solutions semblables au sein de l'application web. 

L’application était à ce moment-là fonctionnelle et performante pour le volume de données que nous connaissions.

Temps d'import divisé par 4 

Aujourd'hui le système a encore été repris par mon maître d'apprentissage basculant cette manipulation côté backend avec un sytème de streaming des fichiers (lecture de ceux-ci par morceaux)

Ce qui montre que même si cela fonctionnait bien dans un but prévisionnel il était possible d'arriver à une solutio nencore plus fiable en poussant la réflexion encore plus loin. Ce qui n'a pas été le cas à ce moment-là de par un manque d'expérience et de conscience des possible.
</div> -->

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
Dans ma quête de recherche de gouleau d'étranglement 

Premier point Temps de chargement long de certaines pages ce qui est regrétable car fait perdre du temps

Deuxième point : Navigation lente dans de longues listes de données (temps de chargement qui n'est pas fluide et désagrable à l'utilisation)

le lazy loading consiste à charger les choses seulement quand on en a besoin, ce qui permet de gagner du temps et de la place lorsque vous avez une page avec beaucoup de contenu

le infinite scrolling permet de gérer et de visualiser de grandes quantités d'informations de manière efficace, en ne montrant que ce qui est nécessaire au fur et à mesure.

Application beaucoup plus fluide et surprend les clients lors de démonstration par rapport aux outils qu'ils connaissent où la moindre action prend beaeucopu de temps. 

Le fait de diviser les tâches de n'appeler les données que lorsqu'elles sont réellement nécessaires c'est ça qui contribue à la réalisation d'une application web robuste capable de servir à l'industrie permettant d'améliorer la productivité des entreprises du secteur. Le but est de leur faire gagner du temps avec l'utilité de nos outils donc aspect super important.

Mais ces résultats ne proviennet pas uniquement de ce côté du développement d'application web mais aussi grandement du côté Backend la partie submergée de l'iceberg
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
On va parler ici du côté API et BDD

Compétence essentielle pour un développeur d'app web

découvert avec la technologie Java et MySQL à l'école 

Approfondie en entreprise avec la technologie Node via ExpressJS et PostgreSQL

Côté API compétence la plus forte actuellement

J'utilise tout le temps Express amintenant et des bdd sql comme des non sql mongdb pour des projets perso

Mais on va surtout parler d'express et de postgresql au service de l'industrie ici
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
Rappel des défis à franchir pour servir le monde de l'industrie
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
Programme informatique utilise de la mémoire vive pour fonctionner et quand les tâches qu'il a à réaliser sont trop énergivores, la mémoire sature et le programme plante

Problème qu'on a eu sur notre première version fonctionnelle à l'arrivée de volumes de données plus conséquents que ce que l'on connaissait

Rappel des checks de cohérence et d'intégrité

Algorithme côté bakckend qui s'en charge et qui fait les checks ligne de données par ligne de données

Exécute une série d'action pour vérifier : 
- La taille des chaines de charactères 
- Exécution de requetes en base de données pour vérifier présence de donnée sur une partie du site industriel
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
Stockage en cache pour les check

Surtout utile pour les requetes en base de données c'est tres couteux donc ca permet de garder ces résultats pour les exploiter pour les autres lignes

Caching simple mais ambitions de passer sur un service plus complexe d'ici peu de temps tels que Redis

Batch partout dans le bakcend pour le tratement de données (ligne par ligne)

Aujourd'hui l'implémentation permet d'éviter des crash mémoire mais on est face à un nouveau problème c'est la lenteur d'exécution.

Ouverture possiblie split des tâches via des workers pour séparer les différents algo de checks 

ou alors option discutés avec mon matire d'apprentissage, l'adoption de micro services avec un langage bas niveau donc plus proche de la machine (worker plus poussé avec beaucoup plus de controle sur tout ce qui va etre gestion de la mémoire)

Je parle d'ouverture car c'est un sujet qui est toujours d'actualité l'amélioration de l'application et l'amener vers une solution robuste. Dès la semaine prochaine je vais travailler sur ce genre de points.

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
Il faut que je vous parle de quelque chose dont je ne suis pas fier mais qui a eu lieu

Sur la version de démonstration il y avait des failles de sécurité côté backend et notamment des failles sql (expliquer)

Ce n'était pas un concep avec lequel j'étais familier alors que ca fait partie des failles de sécruité les plus basiques

Ce ne nous a pas causé de tort car l'application n'était pas en production mais ca cette expérience m'a permis de mieux comprendre le sujet et anticiper ce genre de problèmes à l'avenir

Ce problème est présent de par une fonctionnalité dans l'application qui est sous la forme de requete personnalisée et qui permet à l'utilisateur de récupérer des données utiles pour lui lié à son site industriel.

Ce systeme passait par une requete à l'api qui si modifiée avec n'importe quel nom de colonne ou table à la place aurait pu permettre la récupération de données auquel l'utilisateur n'est pas censé avoir accès.
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
  Côté back j'ai pu empêcher la récupération de ces données en limitant le champ de possibilités des colonnes et tables possibles de récupérer.

  De plus j'ai utilisé des systèmes connus de sanitanisation de données telles que l'échappement pour indiquer à la base que certaines parties de la requete ne doivent pas être interprétées comme du code mais comme du texte pur et dur

  L'utilisation de requetes préparées aussi appelées prepared statements ont permis de limiter ce genre de problème au global dans l'applcation en même temps que d'améliorer les performances de la requete puisque celle-ci est entre guillement connue de la base et où l'utilisateur ne peut en aucun cas la modifier.

  Sur un projet personnel et pour un cas différent ici pour se protéger des attaques ddos (expliquer) j'ai mis en place une protextion capable de détecter si un meme utilisateur a une utilisation suspecte de l'application ici s'il fait beaucoup de requete dans un temps limité. 

  Projet de l'implémenter dans Premis DM c'est toujours un plus

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
Dernier aspect permettant d'arriver à une application capable de servir le milieu de l'industrie c'est la scalabilité (le fait d'anticiper et d'avoir une marge de manoeuvre avant l'arrivée d'utilisteurs supplémentaires par exemple)

Trop de données en base de données qui ont fait que la base ne délivrait les données souhaitées que très lentement (plusieurs minutes pour afficher une table de données jusqu'à plusieurs dizaines de minutes

En partie du au fait que la bdd n'était pas du tout optimisée. Aucune mise en place spécifique
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
1ère étape repérer ces gouleau d'étranglement 

La première réflexion a été le fait qu'une partie des données de l'application ne sont utilisées uniquement en lecture seule (pas de modif ou quoi) et que ces données dépendant d'autres trables.

Cepednant des tables étaient construites pour assurer l'accès à ces données là ce qui allourdi la base de données.

C'est à ce moment-là que j'ai mis en place des vues (expliquer)

BDD beaucoup plus légère

Plus de recherches par la suite et prise de connaissance sur l'indexation 

Expliquer indexation avec l'exemple du livre pour chercher une info rapidement

Indexation sur les colonnes servant de liens entre les tables (aussi appelées foreign key) donc accélération des recherches

Indexation a énormément grandi la puissance de récupération de données permettant de récupérer des données 10x plus rapidement

Commandes internes au systèmes postgresql pour l'analyse de base de données permettant de faire une analyse automatique de l'ordre d'exécution des requetes les plus optimisées

Aujourd'hui cela fonctionne bien mais dans une optique de prévision comme le veut la scalabilité 

Se pencher sur du sharding de la base (séparation en plusieurs parties pour assurer une réduction de la charge de travail et une meilleure scalabilité)
 -->

---
growHue: 60
grow: right
class: flex flex-col items-start justify-center
---

# Ma Légitimité

<div mt5 v-click>
<span>Gestion du projet Premis DM en <span v-mark.underline.purple="1">autonomie</span></span>
</div>

<div mt5 v-click>
<span>Possible adoption de la solution au niveau <span v-mark.underline.red="2">international</span></span>
</div>

<!--
J'aimerai maintenant préciser que c'est grâce à tout ce qu'on a vu que ce soit côté backend et côté frontend qu'aujourd'hui l'application web PremisDM se rapproche d'une solution robuste capable de répondre aux besoins actuels du monde de l'industrie

Comment et avec quelle légitimité je peux vous affirmer que ces méthodes fonctionnent et qu'elles répondent à la problématique c'est à dire que ces méthodes sont capables d'arriver à des solutions capables d'améliorer l'efficacité du secteur industriel 

Expliquer la confiance qu’à l’entreprise en moi pour me confier une application web à gérer en grande partie seul en m’occupant moi même des interactions clients 

Je manage les personnes m'aidant sur le projet.

Solution présentée à un géant de l'industrie et en discussion pour être adopté à un niveau mondial donc faire lien avec la problématique

Afin transformer les méthodes de travail de cette entreprise industrielle pour améliorer l'efficacité et la compétitivité
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
Envie de continuer mon activité au sein d'holis consulting

Passion pour le développement et une fascination des possibilités ouvertes par la profession

Aujourd'hui utilisation de mon temps libre dans cette direction en espérant un jour développer une activité le plus loin possible

Plusieurs projets à mon actif mais présentation des 3 les plus pertinents
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
Développé pendant le semestre où on apprenait android

Envie de pousser le projet au bout mais jamais été sur les store car objectifs flous avec mon ami (commanditaire) et jamais réussi à se mettre daccord
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
<div op50 w-80 v-click>Mauvaise stratégie Marketing</div>
</div>

</div>

<img src="/yournight.png" absolute left-170 rounded-lg w-60 mt--10 />



<!--
Pendant l'été d'il y a deux ans

8 mois de dev

Vouloir sortir un projet trop fini presque parfait sans avoir réellement testé un intérêt

Loupé sur la stratégie marketing car moi même j'ai douté de la perspicacité du projet
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
Site web communautaire sans business plan derrière (pas de rémunération)

Juste une volonté d'améliorer mes compétences en marketing et de faire un site pouvant servir à des gens et moi le premier
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
Stratégie marketing via twitter car plateforme populaire auprès de l'audience visée par la solution

illustration de l'intérêt de la communauté

Encourageant pour la suite et confiant de mes capacités à arriver au bout d'un projet plus concret
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
That's all for my talk, thank you, and happy hacking!
-->