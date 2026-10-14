# Contribuer au projet O26A ClubSportif

Merci de participer à l'amélioration du site du club de basket. Ce document décrit les bonnes pratiques à suivre pour travailler proprement et de manière cohérente avec ton coéquipier.

## 1. Objectif du projet

Le site est une vitrine statique destinée à présenter :

- l'accueil du club,
- les activités sportives,
- les différentes équipes,
- l'histoire et les valeurs du club,
- les informations de contact.

L'objectif est de garder un site clair, moderne, lisible et facile à maintenir.

## 2. Workflow de contribution

### Créer une branche

Avant de commencer un travail, crée une branche dédiée :

```bash
git checkout -b feature/nom-de-la-fonctionnalite
```

Exemples :

- `feature/amelioration-accueil`
- `feature/formulaire-contact`
- `feature/responsive-design`

### Modifier les fichiers

- Évite de modifier plusieurs sujets dans un même commit.
- Les changements doivent rester lisibles et bien structurés.
- Respecte la structure actuelle du projet.

## 3. Organisation des fichiers

- `dossiers.html/` : pages HTML du site
- `dossiers.css/` : styles CSS du projet
- `README.md` : documentation générale du projet
- `CONTRIBUTING.md` : règles de contribution

## 4. Bonnes pratiques

### HTML

- conserver une structure claire et cohérente,
- garder les noms de fichiers explicites,
- utiliser des titres hiérarchisés correctement,
- privilégier des balises sémantiques (`header`, `main`, `section`, `nav`, `footer`, etc.).

### CSS

- regrouper les styles par section ou par page,
- utiliser des noms de classes explicites,
- éviter les styles inutiles ou dupliqués,
- vérifier la compatibilité responsive.

### Design

- garder une identité visuelle cohérente,
- veiller à la lisibilité du texte,
- maintenir un contraste suffisant,
- garder un rendu propre sur mobile et desktop.

## 5. Vérification avant soumission

Avant de finaliser une modification :

1. vérifier que les fichiers HTML s'ouvrent correctement dans le navigateur,
2. contrôler le rendu visuel sur desktop et mobile,
3. vérifier qu'il n'y a pas de lien cassé,
4. tester les éléments modifiés pour éviter les régressions.

## 6. Règles de collaboration

- Communiquer clairement sur les changements à faire.
- Vérifier les modifications avant de les valider.
- Ne pas écraser le travail de l'autre sans accord.
- Éviter l'ajout de code inutile ou de fichiers parasites.
- Utiliser des noms de commit clairs et explicites.

Exemples de bons messages :

```bash
git commit -m "Ajout de la page d'accueil du club"
git commit -m "Amélioration du design responsive"
git commit -m "Mise à jour des cartes d'équipes"
```

## 7. Exemple de workflow de travail

```bash
git checkout -b feature/amelioration-contact
# modifications...
git add .
git commit -m "Amélioration du formulaire de contact"
git push origin feature/amelioration-contact
```

## 8. Questions ou idées

Si tu as une idée d'amélioration ou une proposition de fonctionnalité, ouvre une discussion claire avec ton coéquipier avant de commencer le développement. Cela permet de garder le site cohérent et évite les doublons de travail.

## 9. Récapitulatif

Pour contribuer efficacement :

- travaille sur une branche dédiée,
- garde le code propre et lisible,
- respecte la structure du projet,
- teste le rendu avant de valider,
- communique avec ton coéquipier pour une meilleure coordination.

Merci pour ta contribution !
