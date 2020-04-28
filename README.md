# TPI 2020

Voici le README.md pour le projet TPI de la météo pour les sites de TX Group.

## Prérequis

Installez [https://nodejs.org/](Node.js).

## Installation

Tout d'abord, lancez la commande

```bash
npm install
```

pour installer les packages nécessaires.

Pour lancer le site web en mode développement (ou pour le tester)

```bash
npm run dev
```

Et ouvrez le lien [http://localhost:3000](http://localhost:3000) avec votre navigateur pour voir le résultat.

Vous pouvez commencer par modifier la page `pages/index.js`. La page se met à jour automatiquement vous quand vous la modifierez.

## Version Production

Lancez

```bash
npm build # minifie, optimise le code

npm start # même chose que npm run dev sauf qu'il lance le site en mode production
```

## Tests unitaires

Lancez

```bash
npm test

# ou

npm test:coverage
```

Pour exécuter les tests unitaires et voir le pourcentage de la couverture des tests.
