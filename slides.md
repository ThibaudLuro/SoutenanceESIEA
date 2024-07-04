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
layout: cover
title: Soutenance Thibaud Luro
---

<h1 flex="~ col">
<div text-2xl origin-top-left transition duration-500 :class="$clicks <= 0 ? 'scale-150' : 'op50'">
  <span>Problématique</span>
</div>
<div mt1 text-4xl forward:delay-300 v-click>Comment la digitalisation peut-elle transformer les méthodes de travail dans l'industrie pour améliorer l'efficacité et la compétitivité ?</div>
</h1>

<!--

J'ai choisi cette problématique car parfaite adéquation avec mon expérience professionnelle jusqu'à présent

Une grande partie de ce qui m'attire en informatique est le fait de savoir que sa réalisation est utile à quelqu'un

Aujourd'hui le monde de l'industrie peine encore à se digitaliser (beaucoup de tâches manuelles et chronophages qui pourraient être automatisées)

Les entreprises ayant transitionné vers des solutions digitales ont observé une augmentation de leur productivité de 15 à 25 %. D'aprés une étude de la société McKinsey & Company, nommée "The future of manufacturing: How digital technology is transforming the industry"

Un des outils vendu par la société pour laquelle je travaille a augmenté de 30% la productivité (étude menée par le client de la solution)

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
<span text-blue italic v-mark.blue.underline.delay300="2">professionnelle</span> 
jusqu'à présent
</div>

<!--

-->


---
class: text-2xl
grow: right
title: Make things easier!
---

# Expérience <span font-hand text-blue scale-110 ml3 inline-block>Professionnelle</span>

<div flex="~ gap-2 items-center" text-indigo mt-15 v-click>
  <div i-ph-hammer-duotone text-2xl />
  <span>HOLIS CONSULTING</span>
</div>

<div grid="~ cols-[max-content_min-content_auto] items-center gap-6" py8 px3>
  <div flex="~ gap-2 items-center" text-blue relative v-click>
    <div w-35px h-45px border="l b gray/30" left-0 bottom-15px absolute />
    <div i-ph-magnifying-glass-duotone text-2xl ml-12/>
    <span>Création</span>
  </div>
  <div i-ph-arrow-right-duotone op50 v-click />
  <div v-after>Février 2020 À Pau en Nouvelle Aquitaine</div>

  <div flex="~ gap-2 items-center" text-lime relative v-click>
    <div w-35px h-56px border="l b gray/30" left-0 bottom-15px absolute />
    <div i-ph-book-bookmark-duotone text-2xl ml-12/>
    <span>Effectif</span>
  </div>
  <div i-ph-arrow-right-duotone op50 v-click />
  <div v-after>Quinzaine de salariés</div>

  <div flex="~ gap-2 items-center" text-amber relative v-click>
    <div w-35px h-56px border="l b gray/30" left-0 bottom-15px absolute />
    <div i-ph-currency-circle-dollar-duotone text-2xl ml-12/>
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

### SECTEURS D'ACTIVITÉ

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

### SECTEURS D'ACTIVITÉ

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

-->

---
class: grid grid-cols-[640px_auto] gap-6 items-center justify-center
grow: right
---

![](/nuxt-tutorial.png){.my--10}

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

![](/nuxt-devtools.png){.my--10}

<!--
Intégrité des données : Cette turbine est-elle liée à la bonne section du site industriel

Cohérence : L'état d'un tuyau ne peut pas être déclaré comme bon lorsqu'il a été vérifié pour la dernière fois il y a 5 ans

Sujet de mon alternance donc références à cette application web au cours de la présentation
-->

---
grow: right
class: text-center
title: What Makes a Good Tool?
clicks: 12
---

<div transition duration-800 :class="$clicks < 2 ? 'translate-y-45' : ''" relative>

# Quelles sont les compétences <span v-mark.linethrough.red.delay200="{at:1,roughness:6,seed:146}" transition inline-block :class="$clicks >= 1 ? 'op50' : ''"> requises</span> ?

<div font-hand bold absolute rotate--4 left-150 top-10 text-3xl text-lime1 delay-300 v-click>Essentielles</div>

</div>

<h4 text-left :class="$clicks >= 6 ? 'op50' : 'op0'">Classées par niveau de maîtrise croissant</h4>

<div flex justify-between mt20>
<div relative transition duration-400 forward:delay-600>
<v-clicks>

Humaines :

- Communication <h4 :class="$clicks >=7 ? 'op50 block' : 'hidden'"> (Maîtrisé 60%) </h4>

- Gestion de projet <h4 :class="$clicks >= 8 ? 'op50 block' : 'hidden'"> (Maîtrisé 90%) </h4>
- Gestion du temps <h4 :class="$clicks >= 9 ? 'op50 block' : 'hidden'"> (Maîtrisé 95%) </h4>
</v-clicks>
</div>

<div relative transition duration-400 forward:delay-600>
<v-clicks>

  Techniques :

- Base de données (SQL) <h4 :class="$clicks >=10 ? 'op50 block' : 'hidden'"> (Maîtrisé 80%) </h4>

- Framework d'application web (React) <h4 :class="$clicks >=11 ? 'op50 block' : 'hidden'"> (Maîtrisé 85%) </h4>
- API rest (Node + Express JS) <h4 :class="$clicks >=12 ? 'op50 block' : 'hidden'"> (Maîtrisé 90%) </h4>
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

Compétenance la plus faible aujourd'hui pour moi c'est communication, je ne fais pas toujours le premier pas meme si je m'oblige de plus en plus à le faire

Mes compétencenes les plus fortes : Gestion du temps et Api

-->


---
growX: 50
growY: 130
class: flex flex-col items-center justify-center
title: Nuxt
---

<div text-center absolute left-1 right-1 transition-all duration-400 op75 ease-in-out :class="$clicks === 0 ? 'scale-250 bottom-50%' : 'bottom-5'">
<span op50>https://</span>thibaudluro.com
</div>

<div i-logos-nuxt-icon text-5em mt--10 />
<h1 v-click forward:delay-400 text-center important-text-5xl font-800 important-leading-1.1em>Plus de détails<br><span text-hex-00dc82>Sur mes compétences</span></h1>
<div v-click text-xl op75>
Et leur utilité dans le cadre de notre problématique
</div>

<!--

-->

---
layout: center
class: text-center
growX: 50
growY: 0
---

<h1 important-text-5xl>Comptétences Techniques</h1>

<h3 v-click text-white:50>Leur <b text-white:75 font-bold>utilistation</b> dans le cadre de notre <b text-white:75 font-bold>problématique</b></h3>

<!--
S'attarder sur les compétences techniques car c'est celles qui vont nous permettre de répondre au mieux à la problématique
-->


---
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

Travail avec de très forts volumes de données (données de tout un site industriel)
-->


---
layout: center
class: text-center
growX: 50
growY: 0
---

<h1 important-text-5xl>1/ Développement FrontEnd React</h1>

<h3 v-click text-white:50>Compétance technique permettant de réaliser une <span text-blue font-bold v-mark.highlight.blue.op5.delay200="1" inline-block p3 mx--2>"Interface Utilisateur"</span></h3>

<!--

-->


---
grow: right
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

<div text-xl text-white:50 v-click>
Compléxité du milieu de <span flex="inline gap-1 items-center" text-purple translate-y-0.6><div i-ph-puzzle-piece-duotone />l'industrie</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Réussir à proposer une interface claire et simple
  </div>
</div>

</div>

<!--

-->

---
grow: bottom
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
La Boulangerie et le Boulanger
Dans ta boulangerie, il y a le boulanger principal (ton application principale) qui s'occupe de la plupart des tâches : prendre les commandes, faire le pain, servir les clients, etc.

Les Heures de Pointe
Parfois, il y a tellement de clients qu'il est difficile pour le boulanger de tout gérer à la fois. Il doit prendre les commandes, préparer les pains, cuire les pains, et tout ça en même temps. Cela peut devenir très lent et les clients doivent attendre longtemps.

Le Worker
Pour aider le boulanger, tu engages un assistant (le worker). Cet assistant peut faire des tâches spécifiques de manière autonome. Par exemple, tu pourrais lui demander de seulement pétrir la pâte ou de surveiller les pains dans le four. Ainsi, le boulanger peut se concentrer sur les tâches plus importantes ou prendre plus de commandes.

Fonctionnement
Tâche Assignée : Quand il y a une tâche spécifique (comme pétrir la pâte), le boulanger dit à l'assistant de le faire.
Travail en Parallèle : L'assistant travaille en parallèle avec le boulanger. Pendant que l'assistant pétrit la pâte, le boulanger peut préparer d'autres commandes ou faire autre chose.
Efficacité : Cela rend l'ensemble de la boulangerie plus efficace car les tâches ne s'empilent pas toutes sur le boulanger principal. Les clients sont servis plus rapidement.
Application Web
Dans le contexte d'une application web, un worker est un peu comme cet assistant. Quand ton application a des tâches lourdes ou chronophages (comme générer un rapport complexe, traiter une grande quantité de données, etc.), elle peut les déléguer à un worker. Le worker s'occupe de ces tâches en arrière-plan pendant que l'application principale continue de répondre rapidement aux utilisateurs.

En résumé, un worker aide à répartir le travail pour que ton application (ou ta boulangerie) fonctionne de manière plus fluide et efficace, même quand il y a beaucoup de choses à faire en même temps.

Implémentation : 
Enormes volumes de données pour pouvoir fonctionner
j’ai dû mettre en place des solutions moins communes que les implémentations classiques de React. 
Après m’être renseigné sur le sujet j’ai proposé à mon maître d’apprentissage l’implémentation de Workers qu’il a tout de suite acquiescée. 
L'implémentation de Workers est arrivée comme une solution ingénieuse à un problème de performance critique que nous avons rencontré lors du développement de Premis. En travaillant sur ce projet au sein de Holis Consulting, le traitement et l'analyse de données massives, extraites de fichiers Excel, étaient au cœur de l'application. 
Cependant, lors de tests avec des volumes de données importants, nous avons été confrontés à un obstacle majeur : le front-end de l'application, malgré une conception initialement robuste, la mémoire était rapidement saturé et se retrouvait en état de crash en raison de surcharge. L'adoption de cette approche a marqué un tournant dans le développement de Premis. En déléguant le lourd traitement des données des fichiers Excel à des Workers, j’ai non seulement résolu le problème de surcharge de mémoire mais j’ai également amélioré significativement les performances de l'application. L’application était à ce moment-là fonctionnelle et performante pour le volume de données que nous connaissions.
</div> -->


---
grow: bottom
---

# FrontEnd React

<div text-white:50 mt5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<div flex="~ gap-2 items-center" v-click="1">
  <div i-logos-npm-icon />
  Lazy Loading
</div>
<div flex="~ gap-2 items-center" v-click="2">
  <div i-logos-vue />
  Virtual Scrolling
</div>

<div v-click="1">

```json
{
  "scripts": {
    "dev": "nuxt dev",
    "build": "nuxt build"
  },
  "devDependencies": {
    "nuxt": "^3.10.0"
  }
}
```

</div>
<div v-click="2">

```vue
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
```

</div>
</div>

<div mt10>
<span text-2xl v-click="3">Addtionner</span> <span v-click="3" op50> ces bonnes pratiques permet d'arriver à une solution robuste</span>
</div>

<!-- 
La Fête et le Buffet
Pour cette fête, tu prévois un énorme buffet avec plein de plats différents. Mais si tu sors tous les plats en même temps, cela prendrait beaucoup de place sur la table, et certains plats pourraient même refroidir ou se détériorer avant que les invités ne les mangent.

Le Lazy Loading
Au lieu de tout sortir d'un coup, tu décides de sortir les plats au fur et à mesure que les invités en ont besoin. Par exemple, tu ne sors les desserts que lorsque les invités ont fini de manger les plats principaux. C'est ce qu'on appelle le "lazy loading".

Fonctionnement
Initialement : Quand les invités arrivent, tu sors seulement quelques plats principaux, pas tout le buffet.
Au Fur et à Mesure : Quand tu vois qu’un plat est presque vide, tu sors un autre plat du frigo ou du four pour le remplacer. Pareil pour les desserts, tu attends que les invités demandent avant de les sortir.
Efficacité : Cela permet de garder la table bien organisée et de s'assurer que les plats sont toujours frais quand les invités les prennent.
Application Web
Dans une application web, le lazy loading fonctionne de manière similaire. Plutôt que de charger tout le contenu d'une page web en une seule fois (ce qui peut être long et ralentir le site), l'application charge d'abord le contenu essentiel. Ensuite, au fur et à mesure que l'utilisateur fait défiler la page ou demande plus de contenu, l'application charge les éléments supplémentaires à ce moment-là.

En résumé, le lazy loading consiste à charger les choses seulement quand on en a besoin, ce qui permet de gagner du temps et de la place, que ce soit pour une fête avec un buffet ou une page web avec beaucoup de contenu.


La Bibliothèque et les Livres
Ta bibliothèque est immense, avec des milliers de livres. Si tu devais tous les sortir et les poser sur le sol pour les voir en même temps, cela prendrait beaucoup de place et deviendrait très difficile à gérer.

Le Virtual Scrolling
Au lieu de tout sortir, tu utilises un système intelligent. Quand tu te promènes dans la bibliothèque, les livres apparaissent seulement quand tu en as besoin. Par exemple, quand tu arrives dans une nouvelle allée, seulement les livres de cette allée apparaissent, et les livres des allées précédentes disparaissent.

Fonctionnement
Initialement : Tu ne vois qu'une petite partie des livres, ceux qui sont juste devant toi.
Défilement : À mesure que tu te déplaces dans la bibliothèque, les livres que tu quittes disparaissent et ceux que tu approches apparaissent.
Efficacité : Cela te permet de voir et de gérer uniquement les livres nécessaires à un moment donné sans être submergé par tous les livres à la fois.
Application Web
Dans une application web, le virtual scrolling fonctionne de manière similaire. Imagine que tu navigues sur une longue liste de contacts ou d'articles. Plutôt que de charger et d'afficher toute la liste en une seule fois (ce qui pourrait ralentir ton ordinateur ou ton téléphone), l'application ne charge et n'affiche qu'une portion de la liste, celle que tu vois à l'écran. Au fur et à mesure que tu fais défiler vers le bas, les anciens éléments disparaissent et les nouveaux éléments apparaissent.

En résumé, le virtual scrolling permet de gérer et de visualiser de grandes quantités d'informations de manière efficace, en ne montrant que ce qui est nécessaire au fur et à mesure, que ce soit dans une immense bibliothèque ou sur une longue page web.
 -->

---
layout: center
class: text-center
growX: 50
growY: 0
---

<h1 important-text-5xl>2/ Développement BackEnd</h1>

<h3 v-click text-white:50>Compétance technique permettant <span text-green font-bold v-mark.highlight.green.op5.delay200="1" inline-block p3 mx--2>"Le transit et le stockage de Données"</span></h3>

<!--

-->


---
grow: right
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
Délivrer les données de manière <span flex="inline gap-1 items-center" text-purple translate-y-0.6><div i-ph-puzzle-piece-duotone />sécurisée</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    S'assurer de la provenance de requêtes
  </div>
</div>

<div text-xl text-white:50 v-click>
Anticiper en mettant l'accent sur la <span flex="inline gap-1 items-center" text-purple translate-y-0.6><div i-ph-puzzle-piece-duotone />scalabilité</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Prendre du recul afin de prévoir de futurs problèmes
  </div>
</div>

</div>

<!--

-->


---
grow: bottom
---

# BackEnd

<div text-white:50 mt5>
Mise en application de la compétence pour de forts volumes de <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />données</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<div flex="~ gap-2 items-center" v-click="1">
  <div i-logos-npm-icon />
  Stockage en cache
</div>
<div flex="~ gap-2 items-center" v-click="2">
  <div i-logos-vue />
  Files d'attente
</div>

<div v-click="1">

```json
{
  "scripts": {
    "dev": "nuxt dev",
    "build": "nuxt build"
  },
  "devDependencies": {
    "nuxt": "^3.10.0"
  }
}
```

</div>
<div v-click="2">

```vue
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
```

</div>
</div>

<div mt10>
<span text-2xl v-click="3">Addtionner</span> <span v-click="3" op50> ces bonnes pratiques permet d'arriver à une solution robuste</span>
</div>


---
grow: bottom
---

# BackEnd

<div text-white:50 mt5>
Mise en application de la compétence pour assurer la <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />sécurité</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<div flex="~ gap-2 items-center" v-click="1">
  <div i-logos-npm-icon />
  Protocole JWT
</div>
<div flex="~ gap-2 items-center" v-click="2">
  <div i-logos-vue />
  Bouclier anti DDOS
</div>

<div v-click="1">

```json
{
  "scripts": {
    "dev": "nuxt dev",
    "build": "nuxt build"
  },
  "devDependencies": {
    "nuxt": "^3.10.0"
  }
}
```

</div>
<div v-click="2">

```vue
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
```

</div>
</div>

<div mt10>
<span text-2xl v-click="3">Addtionner</span> <span v-click="3" op50> ces bonnes pratiques permet d'arriver à une solution sécurisée</span>
</div>


---
grow: bottom
---

# BackEnd

<div text-white:50 mt5>
Mise en application de la compétence pour assurer la <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />scalabilité</span>
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<div flex="~ gap-2 items-center" v-click="1">
  <div i-logos-npm-icon />
  Files d'attentes
</div>
<div flex="~ gap-2 items-center" v-click="2">
  <div i-logos-vue />
  Indexation en base de données
</div>

<div v-click="1">

```json
{
  "scripts": {
    "dev": "nuxt dev",
    "build": "nuxt build"
  },
  "devDependencies": {
    "nuxt": "^3.10.0"
  }
}
```

</div>
<div v-click="2">

```vue
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
```

</div>
</div>

<div mt10>
<span text-2xl v-click="3">Addtionner</span> <span v-click="3" op50> ces bonnes pratiques permet d'arriver à une solution scalable</span>
</div>



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
<img src="/SiteIndustrielNoBg.png" rounded-lg w-120 mt-10 />
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

Envie de pousser le projet au bout mais abandon par un manque de motivation
-->

---
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

<img src="/SiteIndustrielNoBg.png" absolute left-120 rounded-lg w-120 mt-10 />



<!--
Pendant l'été d'il y a deux ans

8 mois de dev

Vouloir sortir un projet trop fini presque parfait sans avoir réellement testé un intérêt

Loupé sur la stratégie marketing car moi même j'ai douté de la perspicacité du projet
-->


---
growHue: 80
growX: 100
growY: 80
---

### Mon projet professionel à court et moyen terme

<div>
<h1>KarmineNews</h1>
<img src="/SiteIndustrielNoBg.png" rounded-lg w-120 mt-10 />
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
growHue: 90
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

---
growX: 50
growY: 130
class: flex flex-col items-center justify-center
title: Vue
---

<div text-center absolute left-1 right-1 transition-all duration-400 op75 ease-in-out :class="$clicks <= 0 ? 'scale-250 bottom-50%' : 'bottom-5'">
<span op50>https://</span>vuejs.org
</div>

<div i-logos-vue text-5em mt--10 />
<h1 v-click forward:delay-400 text-transparent text-center important-text-5xl font-800 important-leading-1.2em style="background: -webkit-linear-gradient(315deg,#42d392 25%,#647eff);-webkit-background-clip: text;">The Progressive<br>JavaScript Framework</h1>
<div v-click text-xl op75>
"A framework that can grow with you and adapt to your needs."
</div>

<!--
Let's take some real world examples of how progressive works in our daily tools.

If you go to the official Vue documentation, vuejs.org. [click] You see the headline describe itself as the progressive JavaScript framework. And inside the docs, [click] there's a statements mention that Vue is a framework that can grow with you and adopt with your needs.

I have heard people saying that one of the main selling points of Vue is that Vue is very easy to learn and get started. And more than that, I also see Vue is awesome because it can be used in basically everywhere thanks to the progressive approach it takes.
-->

---

# Progressive on Integrations

Vue offers multiple ways to use, for different level of integrations:

<div pt3 />

<v-clicks>

- CDN without build tools

- As Web Components
- Single-page application (SPA)
- Static site generation (SSG)
- Server-side rendering (SSR)
- Native targeting
- Vue Vapor Mode <sup op50 italic font-serif>Coming soon</sup>

</v-clicks>

<!--
Vue is progressive on integrations. Vue provides multiple builds and offers many ways to use in different scenarios.

[click] Like you can use Vue with a single line of CDN import, and enhance your web apps even in a static HTML file without any build tools.

[click] You can also use Vue components as Web components so that's it can coexist with the other frameworks. Vice versa you can also import web components within Vue applications.

[click] When we have build tools set up, we can build Vue applications with Vue single file components that colocate necessary context inside a single file. To build interactive single page application with ease.

[click] With tools like VitePress, it allows you to have efficient static side generation that ships minimal JavaScript while retains a great developer experience.

[click] With tools like Nuxt, we could have server-side rendering with Vue to maximize the end-user experience as well as better SEO results.

[click] Native targeting it also possible via Ionic or NativeScripts.

[click] And then we have the upcoming Vapor mode, which allows components to opt-in a more performance VNode-less render engine to optimize even further in performance critcal scenarios.
-->

---
layout: center
class: text-center
title: Levels of Integrations
---

<h1 important-text-5xl>Levels of Integrations</h1>

<h3 v-click text-white:50>Cover different scenarios, coexist with other techs, <span text-1.4em font-hand text-blue v-mark.highlight.delay400="{at:1,color:'#60a5fa20'}">easy to adopt</span></h3>

<!--
Vue's approach provides the progressive on the levels of integrations.

Allows it to cover the needs for different scenarios, or even coexist with other technologies. [click] This means even you have a large codebase using other stacks but want to use Vue, you can still adopt some parts of you app to use Vue first, and gradually migrate each part slowly. As far as I know, for example, [Wikimedia also picked Vue](https://lists.wikimedia.org/hyperkitty/list/wikitech-l@lists.wikimedia.org/thread/SOZREBYR36PUNFZXMIUBVAIOQI4N7PDU/) and started enhancing with Vue.

In the end, the goal is to make our tool easy to adapt for different levels of needs so we could serve a wilder range of the users.
-->

---
growX: 50
growY: 130
class: flex flex-col items-center justify-center
title: Nuxt
---

<div text-center absolute left-1 right-1 transition-all duration-400 op75 ease-in-out :class="$clicks === 0 ? 'scale-250 bottom-50%' : 'bottom-5'">
<span op50>https://</span>nuxt.com
</div>

<div i-logos-nuxt-icon text-5em mt--10 />
<h1 v-click forward:delay-400 text-center important-text-5xl font-800 important-leading-1.1em>The Intuitive<br><span text-hex-00dc82>Vue Framework</span></h1>
<div v-click text-xl op75>
"To make web development intuitive and performant with a great Developer Experience"
</div>

<!--
And then, let's talk about Nuxt.

If we go to nuxt.com, [click] we will see it's titled as "The Intuitive Vue Framework". And in the docs, it mentions [click] Nuxt's goal is "To make web development intuitive and performant with a great Developer Experience".

And that brings us to the next section, "Progressive on Onboarding".
-->

---
grow: bottom
---

# Progressive on Onboarding

<div v-click text-white:50 mt5>
This is <b text-white:75>all you need</b> to start with Nuxt:
</div>

<div grid="~ cols-2 gap-x-2" mt5>
<div flex="~ gap-2 items-center" v-click="2">
  <div i-logos-npm-icon />
  package.json
</div>
<div flex="~ gap-2 items-center" v-click="3">
  <div i-logos-vue />
  app.vue
</div>

<div v-click="2">

```json
{
  "scripts": {
    "dev": "nuxt dev",
    "build": "nuxt build"
  },
  "devDependencies": {
    "nuxt": "^3.10.0"
  }
}
```

</div>
<div v-click="3">

```vue
<script setup>
const msg = ref('Hello, Nuxt!')
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
```

</div>
</div>

<div mt10>
<span text-2xl v-click="4">Intuitive</span> <span op50 v-click="5"> - Minimal knowledge required, and easy to discover new features</span>
</div>

<!--
If you have ever tried Nuxt's starter template - you will find it's surprisingly easy to start a Nuxt app. [click]

All you need is to have `nuxt` installed as your dev dependencies [click], and create a simple Vue component file as `app.vue`. [click]

And that's it, that's all you need to get start with Nuxt. Even to someone who never tried Vue or Nuxt, it's probably not hard to tell what this will render, or how to modify it, as long as they get the basic idea of what is HTML.

[click] I think Nuxt's "Intuitive" here [click] means that you can get started with very minimal knowledge. While also, it should be fairly easy to enable more features as needed.
-->

---

# Progressive on Features

<div v-click text-white:50 mt3 mb6>
Starts <b text-white:75 font-bold>minimal</b> and <b text-white:75 font-bold>grows</b> with users:
</div>

<!--
<div v-click mt-20 mb-4 op75>
By the minimal starting interface, Nuxt allows you to start with a minimal setup and grow with the features you need.
</div>

<div flex="~ gap-4" text-white:75>
<v-clicks>

  <div flex="~ gap-1 items-center">
    <div i-ph-circle-wavy-check-duotone text-xl text-lime />
    Server-side Rendering
  </div>

  <div flex="~ gap-1 items-center">
    <div i-ph-circle-wavy-check-duotone text-xl text-lime />
    Deploys Everywhere
  </div>

  <div flex="~ gap-1 items-center">
    <div i-ph-circle-wavy-check-duotone text-xl text-lime />
    Ecosystem of Nuxt / Vue / Vite
  </div>

  <div flex="~ gap-1 items-center">
    <div i-ph-circle-wavy-check-duotone text-xl text-lime />
    Serverless APIs
  </div>

</v-clicks>
</div>
-->

<div flex="~ col gap-6">

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-circles-three-plus-duotone text-2xl />
    <span font-bold>Have some components?</span>
  </div>
  <span v-click op75 ml4>Put them in <code>components/</code> and use anywhere</span>
</div>

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-signpost-duotone text-2xl />
    <span font-bold>Need routing?</span>
  </div>
  <span v-click op75 ml4>Create a <code>pages/</code> directory and Vue router is set up for you.</span>
</div>

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-cloud-arrow-up-duotone text-2xl />
    <span font-bold>Deploy your site?</span>
  </div>
  <span v-click op75 ml4 flex="~ items-center gap1">It <span text-green>Just works™</span> with zero-config powered by <img src="/nitro.svg" h-1.3em /><span text-purple>Nitro</span></span>
</div>

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-cloud-duotone text-2xl />
    <span font-bold>Need some server logic?</span>
  </div>
  <span v-click op75 ml4>Create a <code>server/api/</code> directory to make serverless endpoints.</span>
</div>

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-file-ts-duotone text-2xl />
    <span font-bold>Want TypeScript?</span>
  </div>
  <span v-click op75 ml4>Oh, you can just use it!</span>
</div>

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-puzzle-piece-duotone text-2xl />
    <span font-bold>PWA, SEO, i18n, RSS, etc?</span>
  </div>
  <span v-click op75 ml4>We have great modules ecosystem to use in a few clicks.</span>
</div>

<div flex="~ gap-2 items-center">
  <div flex="~ gap-2 items-center" v-click>
    <div i-ph-cat-duotone text-2xl />
    <span font-bold>Curious about more?</span>
  </div>
  <span v-click op75 ml4 flex="~ items-center gap1">We have <div i-logos-nuxt-icon text-xl inline-block/><span text-green>Nuxt DevTools</span> to inspect and analyze the internals</span>
</div>

</div>

<!--
Then let's talk about one other aspect that Nuxt is good at - Progressive on features.

So we know that Nuxt works with a bare minimal starter, be also we know a real-world application won't be that simple. We need a lot capability to accomplish various needs, and also a way for us to organize the codebase in an managable way.

[click] Nuxt is the framework that can grows with your need!

[click] To say, if you want to some components to separate and reuse your logic, [click] in Nuxt you can just create components files under the components directory, and they will be auto-discoverabale across your project.

[click] And then if you our app needs the capability to serve multiple pages and do the navigations, [click] you can create the `pages/` directory. The components under it will be register automatically to your router based on their filename. One of the other great part is that until you do this, `vue-router` or related code were never ships to your production app before you actually using it.

[click] Say our app is now ready to go, we want to deploy the site to somewhere. There are quite many deploy platform you can choose from, and usually you will need to learn a bit how to deploy X framework on Y platform, etc. [click] But with Nuxt, they will just works on all major hosting services with zero config, thanks for the automatic deploy presets powered by Nitro.

[click] It's common for an web app to have some server logics and API end points. [click] In Nuxt you can simply create function modules under `server/api` directory, witha a very similar convention like the pages for routing. Nitro will deploy them in the serverless functions based on your hosting services and we have the end-to-end type safety on developement.

[click] Talking about type safety, if later you learned TypeScript and want to use it with in Nuxt - [click] no problem, you can directly use them as Nuxt already understand it.

[click] For more features like Progressive Web Apps, Search engine optimization, internationallizations, etc. [click] Nuxt provides a rich module ecosystem that you can integrate them within a few clicks.

[click] And finally, in case you are interested in more features Nuxt provides, [click] we also built Nuxt DevTools for you to inspect the internals or analyze your apps.

All those features are opt-in, meaning that if you don't need a certain feature, you don't even need to learn it. And once you find it useful later, you can always grab it back easily.
-->

---
class: grid grid-cols-[auto_640px] gap-4 items-center justify-center
grow: left
---

<div flex="~ col gap-4">
<div text-4xl>Nuxt DevTools</div>
<div op50 v-click>Help features discovery<br>and understanding</div>
</div>

![](/nuxt-devtools.png){.my--10}

<!--
To help with the features discovery, we made Nuxt DevTools as we just mentioned.

For example, DevTools provides a modules tab, that you can have a quick overview of how many modules you have installed, with links to their documentations or the source code repo. It also offers you a nice UI for you to search through all the modules across the community, and you can ask DevTools to automatically download them and install for you with a single click.

[click] DevTools is built to help features discovery and understanding, to assist you crafting even more awesome applications.
-->

---
class: grid grid-cols-[640px_auto] gap-6 items-center justify-center
grow: right
---

![](/nuxt-tutorial.png){.my--10}

<div flex="~ col gap-4" text-right>
<div text-4xl>Nuxt Tutorial</div>
<div op50 v-click>Help onboarding<br>and learning</div>
</div>

<!--
On top of the documentation site Nuxt has, in the past months we started to build an interactive tutorial playground. Some of you here probably have watched my live streaming on building it, thank you for working together with me btw.

So Nuxt Tutorial allows beginners to have a more linear, step-by-step learning experience. So they can start playing with Nuxt more easier without the need to install or setup.

[click] This is another case that we are trying to get the progressive onboard experience even smoother.
-->

---
layout: center
class: text-center
---

<h1 important-text-5xl>Grow with Users</h1>

<h3 v-click><span op50>Expose concepts & powers </span><span text-lime font-hand text-4xl v-mark.underline.lime.delay400="1">progressively</span></h3>

<!--
In short, the point here is that we should grow with users and not putting too much stuff upfront at one.

[click] Make learning easier to starts with, and expose new concpets and powers progressively along the way.
-->

---
growHue: 100
class: flex flex-col items-center justify-center
---

<div text-center absolute left-1 right-1 transition-all duration-400 op75 ease-in-out :class="$clicks === 0 ? 'scale-250 bottom-50%' : 'bottom-5'">
<span op50>https://</span>vitejs.dev
</div>

<div i-logos-vitejs text-5em mt--10 mb2 />
<h1 v-click forward:delay-400 text-center important-text-5xl font-800 important-leading-1.1em>Next Generation<br><span text-purple>Frontend Tooling</span></h1>
<div v-click text-xl op75>
"We work closely with projects in the ecosystem to minimize regressions on each release"
</div>

<!--
And then, let's take one more example, Vite.

[click] Vite titled itself as the next generation frontend tooling. I am prettry sure no one would question that.

[click] In the "Vite philosophy" section, the docs mentions that "Vite works closely with projects in the ecosystem to minimize regressions on each release".

Vite is on major version 5 right now. And during the past 4 years, we basically keep the pace of release 1 major version per year to keep up the JavaScript ecosystem and the evolving standards.

Some of you probably have been through that periods where we do major releases. The last one with Vite 5 and was released on November last year.

It's not a secret that Vite's major releases have very smooth migration paths. We received many comments mentions about their successful migrations cases.
-->

---
growHue: 60
grow: right
class: flex flex-col items-start justify-center
---

## A Typical Vite Plugin

<div mt5 v-click>
<div flex="~ gap-2 items-center">
  <div i-logos-npm-icon />
  package.json
</div>

```json
{
  // ...
  "peerDependencies": {
    "vite": "^2.9.0 || ^3.0.0 || ^4.0.0 || ^5.0.0"
  }
}
```

</div>

<div mt4 relative>
<span v-click>The plugin keeps working from <span v-mark.underline.purple="3">Vite 2 to Vite 5</span></span>
<img src="/vite-3years.png" absolute left-65 top-10 rotate-10 w-33 alt="3 years in between" v-click />
</div>

<!--
If you look into the Vite plugins you are using, you will find many of their `package.json` follow a similar pattern like this:

[click] Vite appears in the `peerDependencies`  with the version range from Vite 5 all the way down to Vite 2.

[click] This means that the plugin keeps working from Vite 2 to Vite 5 perfectly without the need to even drop support of the previous Vite versions.

[click] Not to mention there is 3 years of time in between, for such an active tool like Vite.

Vite team has put a lot of care in it to make this possible. We care a lot about every changes we made, that we even work out the idea of "Ecosystem CI" that runs the test of major downstream frameworks on almost every pull requests to make sure they has the minimal impact to the ecosystem. This practice has been later adopted to Vue, Nuxt and many other frameworks.

And that brings up one other aspect of progressive.
-->

---
grow: right
---

# Progressive on Breaking Changes

<p v-click="3">Two ways of make breaking changes easier</p>

<div absolute left-29 top-35 w-80 transition duration-800 v-click="1" :class="$clicks <= 3 ? 'translate-x-50 translate-y-10 scale-150' : '' ">
  <img src="/breaking-changes-floors.png" absolute inset-0 op75>
  <div font-hand absolute left-0 top-39 text-2xl>v1.0</div>
  <div font-hand absolute left-23 top-12 text-2xl v-click="7" text-yellow>v1.x</div>
  <div font-hand absolute right-0 top--6 text-2xl transition duration-800 :class="$clicks >= 10 ? 'translate-x--22 translate-y-25 text-blue' : ''">v2.0</div>
  <div font-hand absolute right-0 top--6 text-2xl text-orange v-click="10">v3.0</div>
  <img src="/breaking-changes-stairs-right.png" absolute inset-0 v-click="3">
  <img src="/breaking-changes-stairs-left.png" absolute inset-0 v-click="2">
</div>

<div absolute left-15 bottom-10 transition duration-800 :class="$clicks <= 3 ? 'translate-x-20 translate-y--13  scale-120' : '' ">
<div flex="~ gap-2 items-center" text-yellow3 mt-8 mb2 text-xl v-click="2">
  <div i-ph-escalator-down-duotone text-2xl scale-x--100 />
  <span>Forward Compatibility</span>
</div>

<v-clicks at="5">

- Compatible with the [future]{.text-yellow.font-bold} versions
- Introduce the `experimental` or `future` flags
- Make future behavior opt-in today
- (e.g. `@vue/composition-api`, `vue v2.7`, [Nuxt Bridge](https://github.com/nuxt/bridge))

</v-clicks>
</div>

<div absolute left-120 top-30 transition duration-800 :class="$clicks <= 3 ? 'translate-x-35 translate-y-35 scale-120' : '' ">
<div flex="~ gap-2 items-center" text-blue mt-8 mb2 text-xl v-click="3">
  <div i-ph-escalator-up-duotone text-2xl />
  <span>Backward Compatibility</span>
</div>

<v-clicks at="9">

- Compatible with the [previous]{.text-blue.font-bold} versions
- Deprecate first, print warnings, remove later
- (e.g. `@vue/compat`, `@nuxt/kit`)

</v-clicks>
</div>

<!--
Progressive on Breaking Changes.

I guess probably no one likes breaking changes. But somehow breaking changes are also quite important for the codebase to stay healthy and more maintainable in the long run. It help us to fix imperfectness of our previous design, with a better context we have today. While it's had to avoid introducing them, I believe maybe there would be some ways to make it the transition smoother and easier for the users to adopt.

[click] Taking the experience we had in Vue and Vite, I see there are two major ways to achieve that. Here we bring back the graph we had before, refering to the jump between major versions 1 and 2.

[click] One way of make breaking changes progressively is to do Forward Compatibility, [click] and the other is Backward Compatibility. Let me explain. [click]

[click] Forward Compatibility is about to compatible with versions in the future, like to say if you know what's the new features you going to have in the next breaking change, you bring the features back to the current version in a non-breaking way.

[click] In practice, often we will introduce flags such as `experimental` or `future` for users [click] to explicitly opt-in those changes if they want to try the new stuff, while the mainstream of the users can still be on the current version without breakages.

[click] In Vue, we have the example of `@vue/composition-api` plugin back in Vue 2, which provide the capability of using Vue 3's composition API for Vue 2 apps before they can migrate to Vue 3.

And later we have Vue v2.7, 2 years after Vue 3.0 has released, to have composition API support bake in, and align more with Vue 3's behaviour and feature sets.

For Nuxt, we introduced Nuxt Bridge, to briging the changes betwen Nuxt 2 and 3.

[click] Then it's take about Backforward compatibility, which you might heard this more often. It's about to be compactible with the previous versions.

[click] A common practice is that we will mark a certain feature as deprecated, that will print warnings upon usage. And eventually removed later in the next major version or so. This also means it's better to do smaller and a bit more frequent major releases to make the migration easier.

[click] Talking about examples, in Vue we have the compatibility build, that use Vue 3 as the fundation but with additional flags to simulate the legacy Vue 2 behaviour. That you can migrate once a feature. On Nuxt we have Nuxt Kit that allows module aurthor to build modules that would in both Nuxt 2, Bridge and Nuxt 3. etc.
-->

---
layout: center
class: text-center
growX: 50
growY: 0
---

<h1 important-text-5xl>Allow Coexistence</h1>

<h3 v-click text-white:50>Provide <span text-orange v-mark.underline.orange.delay400.op75="1">"middle stages"</span> for migration, coexist of legacy & new</h3>

<!--
From my understand, I think the progressive of breaking changes is fundamentally allowing the co-existence.

[click] When we make changes, we should provide the "middle stages" for ppl to take a rest on migration, allowing the coexistence of both legacy and new. So the work can be done progressively, and reduce the chance of breakages.
-->

---
grow: right
---

<!--

# Extensible Plugins System

- Allows community to progressively enhance the tool and enrich the ecosystem -->

# Recap

<div flex="~ col gap-1" pt6>

<div text-xl text-white:50 v-click>
Progressive on <span flex="inline gap-1 items-center" text-lime translate-y-0.6><div i-ph-book-bookmark-duotone />Onboarding</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Making it easy to understand and get started
  </div>
</div>

<div text-xl text-white:50 v-click>
Progressive on <span flex="inline gap-1 items-center" text-purple translate-y-0.6><div i-ph-puzzle-piece-duotone />Integrations</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Fits in different scenarios, easy to adopt
  </div>
</div>

<div text-xl text-white:50 v-click>
Progressive on <span flex="inline gap-1 items-center" text-yellow translate-y-0.6><div i-ph-lightbulb-filament-duotone />Features</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Starts minimal and grows with users
  </div>
</div>

<div text-xl text-white:50 v-click>
Progressive on <span flex="inline gap-1 items-center" text-rose translate-y-0.6><div i-ph-warning-octagon-duotone />Breaking Changes</span>
</div>
<div flex="~ gap-2 items-center" mb3 ml37 v-click>
  <div i-ph-arrow-bend-down-right-duotone op50 />
  <div>
    Provide middle stages for migration
  </div>
</div>

</div>

<!--
So, to recap today's topic, we have talked the progressiveness on different aspects of building a tool.

[click] The first is about progressive on onboarding, [click] we should make the tool easy to learn and understand, for more people to start benefited from the tool we build.

[click] And then we talked about the progressive on integration [click] for our tool to cover different scenarios, and easy to adopt.

[click] Then we have the progressive on features, it's pretty common that we want to make our very powerful but that could be overhelming for the users to starts with. [click] So, taking the progressive approach would allows us to start minimal and grow with the users.

[click] And then finally, we have progressive on breaking changes, [click] to provide middle stages to make migrations step by step.
-->

---
layout: center
class: text-center
growX: 50
growY: 0
---

<h1 important-text-5xl>Progressive Paths</h1>

<h3 v-click text-white:50>Enables users the capability of <span text-lime font-bold v-mark.highlight.lime.op5.delay200="1" inline-block p3 mx--2>"Divide and Conquer"</span></h3>

<!--
There are much more aspects of progressiveness that we didn't have time to talk about today, but my goal today is to bring this idea of "Progressive Path" to you.

It might not seems to be a very cool or unusual stuff that people would get excited about, but I think it is playing a very important role to our daily software development. And we should think about it more often when building stuff, not only for open source projects, but also probably also for your products, or the ways of doing stuff in general.

[click] To finish my talk with one sentence, I'd say "To provide the progressive paths, is to enable users the capability of 'Divide and Conquer' towards the goals they have".

I hope you enjoy and find it useful.
-->

---
layout: intro
class: text-center pb-5
growX: 50
growY: 120
---

# Thank you!

Slides on [antfu.me](https://antfu.me)

<!--
That's all for my talk, thank you, and happy hacking!
-->
