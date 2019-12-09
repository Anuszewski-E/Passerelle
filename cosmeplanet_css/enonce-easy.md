# Exercice HTML-CSS / SmoothMaker

## Introduction

Le but de cet exercice va être de créer un site web vitrine d'un bar à smoothies. Ce bar à smoothie propose sur son site une liste de recettes de smoothies, outre les informations vitrine habituelles.

Cet exercice global s'appuit sur le layout de Bootstrap et beaucoup de CSS custom. Ce sera l'occasion également de découvrir les variables CSS. Cette interface ne contient pas de JS (la map est une image statique, du moins pour ce module 😉).

## Énoncé

Intégrer la maquette des différentes pages.

Certains encarts se présentent sous la même forme sur différentes page, il ne faut pas hésiter à utiliser un CSS commun.

L'accès aux recettes favorites ne se fait qu'en étant connecté. Un clic sur "Recettes favorites" renvoie donc vers la page de connexion. 

## Méthodologie

Afin de bien aborder l'exercice, voici les étapes que nous vous recommandons de respecter :

1. Intégrer la page d'accueil en définissant un style particulier pour le header uniquement sur la homepage
2. Réaliser le responsive de la page d'accueil (excepté la navigation qu'on ne gèrera pas ici)
3. Intégrer la page **Smoothies** + reponsive
4. En se basant sur la page **Smoothies**, intégrer la page **Recettes**
5. Intégrer la page présentant une recette + responsive
6. Créer les interfaces de connexion et inscription + responsive
7. Créer la page **Le bar** + responsive

## Astuces

Créer des classes ne servant qu'à une seule chose (impacter la font-family, mettre en majuscule, etc...) que vous n'aurez plus qu'à rajouter dans le HTML au lieu de répéter ces propriétés CSS à de multiples reprises dans le fichier de style.

## Recommandations / Attention

Utiliser les variables CSS pour les valeurs des propriétés répétitives.

## Ressources

Utilisation de bootstrap et font-awesome

### Typographies

- Titres : Monserrat Extra Bold
- Sous-titre : Nixie One
- Contenu : Montserrat

## Théorie

Bootstrap ne va nous servir ici qu'à gérer le layout (container et affichage en colonne). Cela nous permet non seulement d'économiser du temps sur l'intégration de la structure de la page mais également sur la gestion du responsive, que Bootstrap intèger déjà par l'utilisation de ses préfixes de classes.

### Liens recommandés

Pour cet exercice, vous aurez besoin de :
- [Les variables CSS](https://developer.mozilla.org/fr/docs/Web/CSS/Using_CSS_custom_properties)

