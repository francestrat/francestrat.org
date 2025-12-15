FranceStrat

Site d’analyse stratégique des politiques européennes.
Projet éditorial indépendant, publié en open source et déployé sur GitHub Pages.

🎯 Objet du site

FranceStrat part d’un constat simple :

L’Union européenne n’est ni le problème ni la solution.
C’est un cadre de négociation.
Les pays qui défendent leurs intérêts y obtiennent des résultats.

Le site a pour objectif de :

expliquer les mécanismes européens de manière claire,

illustrer les analyses par des exemples concrets et chiffrés,

replacer la responsabilité politique au niveau national, sans caricature,

contribuer à un débat informé, non partisan.

🧭 Ligne éditoriale
Positionnement

Analyse stratégique, non militante

Approche factuelle, non idéologique

Responsabilité française au cœur de l’analyse

Thématiques prioritaires :

Énergie

Industrie

Agriculture

Normes

Commerce et souveraineté économique

Ton

posé et pédagogique

précis, sourcé

sans invective

sans slogans

Ce site ne défend aucun parti ni aucune personnalité politique.

🧱 Choix techniques

Le site est volontairement simple, robuste et pérenne :

Site statique

Contenus en Markdown

Génération via Astro

JavaScript uniquement lorsque nécessaire

Hébergement gratuit sur GitHub Pages

Aucun backend.
Aucune base de données.
Aucun tracking invasif.

📊 Données et graphiques

Les analyses s’appuient sur des données explicites et vérifiables.

Principe général

Les données sont stockées dans le dépôt (data/)

Les graphiques sont générés automatiquement au moment du build

Les graphiques sont exportés en SVG statiques

Chaque graphique affiche :

un titre

des axes avec unités

une légende

une source clairement indiquée

Aucune donnée n’est extrapolée sans mention explicite.

📁 Organisation du projet
/
├─ data/                 # Données (CSV / JSON)
├─ charts/               # Configurations de graphiques
├─ scripts/              # Scripts de génération
├─ public/
│  └─ charts/            # Graphiques SVG générés
├─ src/
│  ├─ content/           # Articles et dossiers (Markdown)
│  ├─ pages/             # Pages Astro
│  └─ layouts/
├─ astro.config.mjs
├─ package.json
└─ README.md

📝 Contenus éditoriaux
Articles

Chaque article vise à :

poser un problème précis,

présenter des faits et exemples concrets,

expliciter les mécanismes institutionnels,

proposer des pistes réalistes dans le cadre européen.

Les articles distinguent clairement :

faits établis

interprétations

hypothèses

📈 Sources

Les sources sont privilégiées parmi :

institutions publiques

autorités de régulation

rapports officiels

médias économiques reconnus

think tanks identifiés

Toute affirmation chiffrée doit être sourcée.

🚀 Déploiement

Le site est déployé automatiquement via GitHub Pages après build.

Commandes principales :

npm install
npm run charts
npm run dev
npm run build

🧠 Philosophie générale

FranceStrat se veut lisible, rigoureux et crédible
pour un lecteur exigeant : ingénieur, économiste, journaliste, décideur public.
