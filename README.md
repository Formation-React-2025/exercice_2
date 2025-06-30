# Formation React 2025

## Exercice 2 - Création d'un composant avec props

### 1 - Initialisation du projet
Plusieurs possibilités :
- Continuer sur le même projet
- Télécharger le projet initialisé depuis le GitHub [Formation React 2025](https://github.com/orgs/Formation-React-2025/repositories) :
  - ```git clone https://github.com/Formation-React-2025/exercice_2.git```

### 2 - Création d'un composant avec des props
- Lancer la commande ```npm install prop-types@15.8.1```.

- Dans le package ```./src/features/exercices/pages/exercice-2```, créer le composant ```Exercice2Page``` dont le comportement est le même que le composant ```Exercice1Page``` aux différences suivantes :
  -	Le titre du header est maintenant reçu en props
  - Le titre est "Exercice 2 - Création d'un composant avec props"
  -	Le contenu correspond à la props ```children```

- Dans le fichier ```./src/App.jsx```, appeler le composant.

<u>Note :</u> par la suite, nous pourrons dupliquer ce composant dans ```./src/components/layout/page-layout/PageLayout.jsx``` afin de le réutiliser.

### 3 - Mise à jour de variable
- Dans le package ```./src/components/input/buttons/on-click-button```, créer un composant `OnClickButton` :
- Le composant initialise une variable locale à 0
- Le composant déclare une fonction dont l'exécution incrémente la variable
- La fonction doit afficher en console (`console.log(.)`) la valeur de la variable avant incrémentation et après incrémentation
- Le composant retourne un bouton, qui, lorsque l’on clique dessus, exécute la fonction.
- Le label du bouton est la variable

- Dans le composant `Exercice2Page`, appeler le composant `OnClickButton`, ouvrer la console du navigateur (`F12`) et cliquez sur bouton.
- Que constatez-vous ?
