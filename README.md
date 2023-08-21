# Projet-Glacier

Le but de cet exercice est de maîtriser plusieurs étapes de la création de projet :

- l'analyse de la création d'une base de données (BDD)
- l'implémentation d'une BDD
- l'injection de données de test dans une BDD
- la création de wireframes de l'interface utilisateur
- la création d'une maquette fonctionnelle en HTML CSS de l'interface utilisateur

## Cahier des charges

En vous basant sur les besoins du client précisés ci-dessous, vous devez créer :

- un dictionnaire des données
- un Modèle Conceptuel de Données (MCD, méthode Merise)
- une BDD
- des données de test
- des wireframes
- des pages HTML CSS

## Besoins

Un client qui est glacier souhaite créer une application de gestion de stock.

Le client a besoin des fonctionnalités suivantes :

- créer des comptes utilisateurs : email, mot de passe
- créer des rôles : nom
- associer un compte utilisateur avec **des** rôles (inverse possible 1 rôle pour plusieurs utilisateurs)
- créer des congélateurs : nom (le nom indique l'emplacement), description
- associer un congélateur et **un** compte utilisateur (qui en sera responsable)
- créer des parfums : nom, description
- créer une glace : volume (en litres), date de production, date de sortie (c-à-d faire un soft delete)
- associer une glace et **un** parfum
- associer une glace et **un** congélateur

## Livrables

Le projet doit être livré sous la forme d'un repository git en ligne sur Github.

Le repository doit contenir les fichiers suivants :

- un fichier de tableur (`.xls`, `.ods` ou `.csv`) contenant le dictionnaire de données
- un fichier image (`.jpg`, `.png`) contenant le MCD
- des fichiers image (`.jpg`, `.png`) contenant les wireframes
- des fichiers SQL (`.sql`) contenant les données de test
- un fichier SQL (`.sql`) contenant la BDD
- des fichiers HTML et CSS (`.html`, `.css`) contenant les pages web
