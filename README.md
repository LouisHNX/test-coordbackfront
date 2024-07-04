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
# Mon projet Vite et React

Bienvenue dans mon projet Vite et React ! Dans ce projet, j'utilise les technologies suivantes :

- [Vite](https://vitejs.dev/) : un outil de construction rapide pour les applications web modernes.
- [React](https://reactjs.org/) : une bibliothèque JavaScript pour la construction d'interfaces utilisateur.
- [TypeScript](https://www.typescriptlang.org/) : un sur-ensemble de JavaScript qui ajoute des fonctionnalités de typage statique.

## Linting et Pre-commit

Ce projet utilise des linters pour vérifier la qualité du code et des hooks de pre-commit pour s'assurer que le code est conforme aux règles de linting avant d'être enregistré dans le référentiel Git.

### Linters

Les linters suivants sont utilisés dans ce projet :

- [eslint](https://eslint.org/) : vérifie la syntaxe, le style et les erreurs logiques dans le code JavaScript.
- [prettier](https://prettier.io/) : formatte automatiquement le code JavaScript pour qu'il soit conforme à un style prédéfini.
- [stylelint](https://stylelint.io/) : vérifie la syntaxe et le style dans les fichiers CSS.
- [htmlhint](https://htmlhint.com/) : vérifie la syntaxe et les bonnes pratiques dans les fichiers HTML.

### Pre-commit

Les hooks de pre-commit suivants sont utilisés dans ce projet :

- `trailing-whitespace` : supprime les espaces blancs en fin de ligne.
- `end-of-file-fixer` : s'assure que le fichier se termine par un saut de ligne.
- `check-yaml` : vérifie la syntaxe des fichiers YAML.
- `check-json` : vérifie la syntaxe des fichiers JSON.
- `check-toml` : vérifie la syntaxe des fichiers TOML.
- `eslint` : exécute eslint sur les fichiers JavaScript et JSX.
- `prettier` : exécute prettier sur les fichiers JavaScript, JSX, CSS, SCSS et Vue.
- `stylelint` : exécute stylelint sur les fichiers CSS et SCSS.
- `htmlhint` : exécute htmlhint sur les fichiers HTML.

### Utilisation

Pour utiliser les linters et les hooks de pre-commit dans ce projet, vous devez d'abord installer les dépendances nécessaires en utilisant la commande suivante :

npm i

Ensuite, vous pouvez exécuter les linters en utilisant la commande suivante :

npm run lint

Cette commande exécutera prettier sur les fichiers appropriés et corrigera les erreurs de formatage.

Enfin, lorsque vous enregistrez des modifications dans le référentiel Git, les hooks de pre-commit seront exécutés automatiquement. Si des problèmes de linting sont détectés, vous devrez les corriger avant de pouvoir enregistrer les modifications.

## Démarrage du projet

Pour démarrer le projet, vous pouvez utiliser la commande suivante :

npm run dev

Cette commande lancera le serveur de développement Vite et ouvrira l'application dans votre navigateur web.