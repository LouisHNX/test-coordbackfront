# Projet : Mon Application React et Vite

Dans ce référentiel, vous trouverez :

- Le code source de l'application
- Un fichier de configuration ESLint pour React et Vite
- Un fichier de configuration Prettier pour le formatage du code

Malheureusement, je n'ai pas pu configurer SonarQube pour ce projet. Je dois admettre que je ne comprenais pas très bien ce que c'était et comment cela fonctionnait, et je n'ai pas eu le temps de creuser davantage

---

## Configuration du projet

Pour configurer le projet sur votre machine locale, suivez ces étapes :

1. Clonez le référentiel sur votre machine


2. Accédez au répertoire du projet :
cd your-repo


3. Installez les dépendances du projet en utilisant npm :
npm install


4. Démarrez le serveur de développement en utilisant Vite :
npm run dev


Cela devrait ouvrir l'application dans votre navigateur par défaut.

### Outils de linting

J'ai configuré ESLint et Prettier pour ce projet. Voici comment les utiliser :

#### ESLint

ESLint est un outil de linting pour JavaScript et JSX. J'ai créé un fichier de configuration personnalisé pour ce projet, qui inclut les règles recommandées par React et Vite.

Pour exécuter ESLint sur votre code, utilisez la commande suivante :
npx eslint . --ext .js,.jsx


Cela vérifiera tous les fichiers `.js` et `.jsx` dans le répertoire actuel et affichera les erreurs et les avertissements dans votre terminal.

#### Prettier

Prettier est un outil de formatage de code qui permet de maintenir un style cohérent dans votre projet. 

Pour exécuter Prettier sur votre code, utilisez la commande suivante :
npx prettier --write .


Cela formatera tous les fichiers dans le répertoire actuel en fonction des règles spécifiées dans le fichier de configuration.
