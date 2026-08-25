<h1 align="center">🌤️ WordPress météo</h1>

<p align="center">Plugin WordPress pédagogique affichant la météo d'une ville dans l'administration.</p>

<p align="center">
  <img src="https://img.shields.io/badge/WordPress-Plugin-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress plugin" />
  <img src="https://img.shields.io/badge/PHP-7%2B-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/OpenWeatherMap-API-EF6C00?style=flat-square" alt="OpenWeatherMap API" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript" />
</p>

## À propos

Ce plugin explore les mécanismes WordPress de base : création d'une page de réglages, enregistrement d'options, ajout d'assets et appel d'une API météo externe.

## Fonctionnalités

- choix d'une ville ;
- choix de l'unité de température ;
- récupération des données OpenWeatherMap ;
- affichage dans les notifications de l'administration ;
- autocomplétion des villes avec l'API Adresse du gouvernement.

## Installation locale

1. Copier le dossier dans wp-content/plugins.
2. Remplacer le placeholder de clé OpenWeatherMap dans meteo.php par une clé locale.
3. Activer le plugin depuis l'administration WordPress.
4. Ouvrir la page de réglages du plugin.

La clé d'API historique a été retirée du dépôt public. Une clé personnelle est nécessaire pour tester les appels météo.

## Contexte

Exercice de formation consacré au développement de plugins WordPress, aux hooks PHP et aux appels d'API. Il n'est pas destiné à une utilisation en production sans durcissement de la configuration.

## Auteur

[Christopher Semard](https://github.com/christophersemard)
