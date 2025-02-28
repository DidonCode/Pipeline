<div align="center" style="display: flex; align-items: center; gap: 15px;">
    <img src="./docker/web/images/logos/logoButify.png" width="100" alt="Butify Logo">
    <div style="display: flex; flex-direction: column; gap: 5px; text-align: left;">
        <span style="margin: 0; color: #EE964B; font-weight: bold;">Butify</span>
        <span style="margin: 0; color: white; font-weight: normal;">Plateforme de musique</span>
    </div>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-orange">
  <img src="https://img.shields.io/badge/Status-Online-success">
</p>

## Installation:

    npm install

## Commandes:

    npm run start     : Démarre le projet
    npm run build     : Compile le projet
    npm run stop      : Arrête le projet

## Test:

    npm run test

## Mobile:

   Suivre le tutoriel => ./mobile

## Lien d'accès avec Docker:

### Documentation

 - [Documentation API](http://localhost:8084/docs/api/index.html)

 - [Documentation Mobile](http://localhost:8084/docs/mobile/index.html)

### Web

 - [Web (page de connexion)](http://localhost:8080/web/login.php)

 - [Web (page personnel)](http://localhost:8080/web/home)

### Admin

 - [Admin (page de connexion)](http://localhost:8080/web/admin/login.php)

### Autre

 - [Phpmyadmin](http://localhost:8083)

## Base de donnée:

Utilisation de l'interface pour le [SCRIPTING (Docker)](http://localhost:8080/web/scripting/index.php). Où importer le fichier ./docker/example.sql dans la base de données.

## Information de connexion:

### Admin (example.sql):

    admin@admin.com
    butify

### Tous les autres comptes (Scripting):

    Voir les adresses mail dans la base de données
    butify
