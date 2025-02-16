
# TP : Introduction aux APIs RESTful avec OpenWeatherMap

Ce projet vise à fournir une compréhension pratique des principes fondamentaux des APIs RESTful et de l'utilisation du format JSON. Nous explorerons différentes bibliothèques de requêtes en JavaScript (request, fetch, axios) en consommant des données provenant de l'API : OpenWeatherMap.

## Objectifs

- Comprendre les principes de l'API RESTful
- Utiliser le format de données JSON
- Consommer des API en utilisant différentes bibliothèques : `request`, `fetch`, et `axios`

## Outils Utilisés

- **Node.js** : Environnement d'exécution JavaScript côté serveur
- **API OpenWeatherMap** : API pour obtenir les informations météorologiques
- **Bibliothèques** : `request`, `fetch`, `axios`

## 1. Prérequis

Avant d'exécuter le projet, assurez-vous d'avoir installé :

- **Node.js** : Téléchargez-le depuis [le site officiel](https://nodejs.org/).
- **npm** : Inclus avec Node.js

Vérifiez votre installation avec les commandes suivantes :

```bash
node -v
npm -v
```

## 2. Installation des Dépendances

Clonez le repository et installez les dépendances avec npm :

```bash
git clone https://url_du_repository.git
cd nom_du_dossier
npm install
```

Installez les dépendances nécessaires :

```bash
npm install request axios
```

## 3. Utilisation des APIs

### a) OpenWeatherMap API

#### Inscription et Clé API

1. Inscrivez-vous sur [OpenWeatherMap](https://openweathermap.org/).
2. Récupérez votre clé API.
3. Modifiez les fichiers `indexrequest.js`, `indexfetch.js` et `indexaxios.js` en remplaçant `API_KEY` par votre propre clé.

#### Exécution des Scripts

- Avec `request` :

  ```bash
  node indexrequest.js
  ```

- Avec `fetch` :

  ```bash
  node indexfetch.js
  ```

- Avec `axios` :

  ```bash
  node indexaxios.js
  ```



## 4. Explication des Paramètres OpenWeatherMap

Les scripts pour l'OpenWeatherMap API retournent les informations suivantes pour la ville de Sousse :

- Description météo
- Température (en °C)
- Humidité (en %)

Les requêtes sont effectuées avec les paramètres suivants :

- `units=metric` : Conversion des unités en Celsius
- `lang=fr` : Résultats en français

Cela permet d'afficher la météo en temps réel et d'obtenir des données de manière lisible pour les utilisateurs francophones.

