# Dishop Coding Challenge

> Bienvenue au Dishop Coding Challenge

## Aperçu

Pour relever ce défi, vous devrez écrire une simple application Web en [React](https://facebook.github.io/react/) et nous fournir les fichiers sources.

Le but de ce défi est d'évaluer vos **compétences et votre approche pour composer une simple application Web** à partir d'un ensemble d'écrans et d'un fichier JSON.

Ce défi devrait prendre environ 2 à 4 heures.

## Le défi

C'est assez simple. En utilisant les écrans fournis comme référence, vous devrez créer un ensemble de composants React. Vous devrez également utiliser un fichier JSON, filtrer ces données et utiliser les champs appropriés.

Bien qu'il s'agisse d'un exercice de base, nous chercherons **du code simple, bien conçu, performant et testé**.

Veuillez inclure un `README` avec des instructions de configuration et tous les tests ou autres documents que vous avez créés dans le cadre de votre solution.

Ajoutez également les informations suivantes à votre `README`:

- Comment avez-vous décidé des choix techniques et architecturaux utilisés dans le cadre de votre solution?
- Pouvez-vous apporter des améliorations à votre soumission?
- Que feriez-vous différemment si on vous accordait plus de temps?

## Détails

Vous devrez créer les 3 pages suivantes avec React:

- Une page "Accueil"
- Une page "Série"
- Une page "Films"

Veuillez créer des composants pour chaque partie de la page (par exemple, en-tête, contenu, pied de page, etc.).
Les assets sont fournis dans le dossier `assets`.

Les pages doivent également être utilisables sur les appareils mobiles et tablettes.

### Page "Accueil"

Reportez-vous à l'écran [screens/1-home.jpg](./screens/1-home.jpg).

Ce sera votre écran `index.html`.

Vous devrez afficher les composants qui pointent vers la page "Série" et la page "Films".

### Pages "Série" et "Films"

Reportez-vous aux écrans [screens/2-series.jpg](./screens/2-series.jpg) et [screens/3-movies.jpg](./screens/3-movies.jpg).

Pour chaque page, vous devrez récupérer le fichier JSON dans ./feed/sample.json, puis:

- Afficher les 21 premières `entries`
- Lorsque l'entrée a une valeur d'attribut «releaseYear»> = «2010»
- Trié par la valeur d'attribut `title` dans l'ordre alphanumérique croissant

Pour le filtre de page "Série" sur:

- Lorsque l'entrée a une valeur d'attribut `programType` égale à `series`

Pour le filtre de page "Films" sur:

- Lorsque l'entrée a une valeur d'attribut `programType` égale à `movie`

Les attributs que vous devez utiliser pour afficher les entrées sont:

- `title`
- `images` →`Poster Art` → `url`

Vous devrez également gérer les états de chargement et d'erreur lors de la récupération du fichier JSON:

- État "Chargement" [screens/1.1-loading.jpg](./screens/1.1-loading.jpg)
- État "Erreur" [screens/1.2-error.jpg](./screens/1.2-error.jpg)

### Mode expert

Pour relever ce défi, il vous est demandé en plus de l'application Web:

- Créer un serveur en [NodeJS](https://nodejs.org/en/) avec une API permettant de récupérer les données du [fichier JSON](./feed/sample.json).
- Ajouter une barre de recherche pour chercher un film ou une série par son nom.

## FAQ

### Quel langage, framework, outil de construction ... dois-je utiliser?

Vous pouvez utiliser ce que vous voulez tant que la solution est construite en utilisant [React](https://facebook.github.io/react/).

## Liens utiles

- [Bitbucket](https://bitbucket.org/) - Hébergement de code source, avec des dépôts privés gratuits pour les petites équipes.
- [Google Fonts - Raleway](https://fonts.google.com/?selection.family=Raleway)
- [React](https://facebook.github.io/react/)

## Autres notes

Veuillez envoyer tout autre code ou projet dont vous êtes fier et que vous souhaitez partager avec nous.

Tout commentaire sur le défi de codage une fois que vous avez terminé est également apprécié!
