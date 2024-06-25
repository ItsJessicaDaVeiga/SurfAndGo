# SURF AND GO - En cours

## Description du projet

**SURF AND GO** est une application Android qui référence les meilleurs spots de surf du monde, développée dans le cadre d'un projet collectif. Cette application vise à fournir des informations détaillées sur les spots de surf, créer une communauté de surfeurs et offrir un référencement global des spots de surf.

## Contexte du projet

Ce projet a été réalisé par une équipe de 5 personnes dans le cadre d'un exercice de développement mobile et back-end. L'objectif était de découvrir le développement mobile Android et son interaction avec une API back-end.

### Consignes pour le front-end (Android)

- Création d'une application Android
- Utilisation de Java ou Kotlin avec Android Studio
- Conception UI avec une navigation simple depuis une liste
- Parsing des données et connexion à une API
- Exploration des patterns d'architecture, notamment MVVM
- Apprentissage du langage objet, des protocoles et de l'héritage

### Consignes pour le back-end (API REST en GO)

- Création d'une API REST en GO pour dynamiser l'application Android
- Optimisation des appels API pour éviter la surcharge et les ralentissements
- Gestion efficace des ressources serveur

## Fonctionnalités principales

- Informations détaillées sur les spots de plages :
  - Horaires des marées
  - Conditions de vent
  - Température de l'eau
  - Niveau recommandé de surf
  - Taille des vagues
  - Note Brice de Nice
  - Type de plage (cailloux ou sable)
  - Photos des plages
  - Plans et itinéraires
  - Informations sur la location de matériel
  - Commentaires des utilisateurs
  - Saison de surf (début et fin)
- Référencement global des spots de surf (national puis international)
- Création d'une communauté de surfeurs
- Géolocalisation
- Création de compte utilisateur
- Possibilité de poster un nouveau spot

## Technologies utilisées

- Kotlin avec Android Studio pour le développement frontend Android
- Go pour le développement de l'API REST backend
- API OpenWeather pour les données météorologiques

## Installation

1. Clonez ce dépôt : `git clone https://github.com/adatechschool/projet-collectif-mobile-surf_and_go.git`
2. Ouvrez le projet Android dans Android Studio
3. Configurez votre clé API OpenWeather dans le fichier de configuration approprié
4. Compilez et exécutez l'application sur un émulateur ou un appareil Android
5. Pour le backend, suivez les instructions d'installation de Go et lancez le serveur API

## Utilisation

[Ajoutez ici des instructions détaillées sur l'utilisation de l'application]

## Périmètre

- Application en français pour le MVP
- Compatible avec les mobiles et tablettes Android uniquement

## Documentation

Pour plus d'informations sur le développement avec Kotlin, consultez la [documentation officielle]: https://developer.android.com/kotlin?hl=fr
https://kotlinlang.org/docs/home.html

## API Reference

**Weather API - OpenWeather**

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

**Get item**

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


## Contribution

Ce projet a été réalisé dans le cadre d'un exercice collectif. Les contributions externes ne sont pas acceptées pour le moment.

## Auteurs et contact

- Jessica: https://github.com/ItsJessicaDaVeiga
- Timothée: https://github.com/TimotheeRoy
- Amélie: https://github.com/AmelieMariaM
- Nadège:https://github.com/npelcat
- Léa: https://github.com/Lea9723


Lien du projet : https://github.com/adatechschool/projet-collectif-mobile-surf_and_go
