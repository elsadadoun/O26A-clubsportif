# O26A ClubSportif

Site vitrine d'un club de basket pour présenter les activités, les équipes, les valeurs du club et les informations de contact.

#MEMBRE DU GROUPE

ABOUBAKAR KOULIBALY
OVOUNDARD Nissi Rich


## Aperçu du projet

Ce projet est une landing page statique développée en HTML et CSS. Il permet de :

- présenter l'accueil du club,
- afficher les activités proposées,
- détailler les différentes équipes,
- présenter le club et sa philosophie,
- offrir un formulaire de contact.

## Structure du projet

```text
O26A-clubsportif/
├── README.md
├── CONTRIBUTING.md
├── dossiers.css/
│   ├── css.css
│   └── equipes.css
├── dossiers.html/
│   ├── page-accueil.html
│   ├── activites.html
│   ├── equipes.html
│   ├── apropos.html
│   └── contact.html
└── .gitignore
```

## Pages disponibles

- Accueil : `dossiers.html/page-accueil.html`
- Activités : `dossiers.html/activites.html`
- Équipes : `dossiers.html/equipes.html`
- À propos : `dossiers.html/apropos.html`
- Contact : `dossiers.html/contact.html`

## Prérequis

- Un navigateur web moderne
- (Optionnel) Python 3 pour lancer un petit serveur local

## Démarrage rapide

### Option 1 : ouvrir directement le site

Ouvrez simplement le fichier `dossiers.html/page-accueil.html` dans votre navigateur.

### Option 2 : lancer un serveur local

Depuis la racine du projet :

```bash
python -m http.server 8000
```

Puis ouvrez :

```text
http://localhost:8000/dossiers.html/page-accueil.html
```

## Stack technique

- HTML5
- CSS3
- Design responsive
- Aucune dépendance externe requise pour le fonctionnement de base

## Personnalisation

Les styles globaux sont dans `dossiers.css/css.css` et les styles spécifiques aux équipes dans `dossiers.css/equipes.css`.

Pour modifier le contenu du site :

- modifier les titres, textes et sections dans les fichiers HTML,
- ajuster les couleurs, la mise en page ou les composants dans les fichiers CSS.

## Contribution

Le projet est conçu pour être évolutif et collaboratif. Merci de suivre le guide dans [CONTRIBUTING.md](CONTRIBUTING.md) avant de proposer des changements.

## À propos

Ce site a été créé pour présenter l'identité visuelle et les activités d'un club de basket. Il sert de base pour des évolutions futures comme :

- ajout d'un vrai formulaire fonctionnel,
- intégration de photos et logos du club,
- amélioration du design mobile,
- ajout de sections événementielles ou de sponsors.

## Licence

Aucune licence spécifique n'est définie pour le moment. Le projet est actuellement utilisé comme support de développement et de démonstration.
