# README

## Présentation du projet

Ce projet, réalisé par **Gong Yiqiao** et **Bai Yue**, vise à mettre en place un **système de navigation en temps réel** sur le robot **TurtleBot 3 Burger**, basé sur le framework **ROS**.

Les objectifs principaux sont de :

- Mettre en œuvre le **SLAM** (Simultaneous Localization and Mapping) dans un environnement intérieur pour générer une carte 2D précise.  
- Permettre la navigation autonome du robot à partir de la carte générée, incluant l’évitement d’obstacles et la planification de trajectoire en temps réel.

## Fonctionnalités principales

1. **Collecter les données LiDAR et construire une carte 2D (SLAM).**  
2. **Assurer la navigation autonome du TurtleBot 3** (détection et évitement d’obstacles, planification de chemin).

## Contenu du dépôt


- **Rapport** : Présente l’ensemble du projet, dont l’installation, la configuration et les tests.  
- **Partie du code** : Contient les fichiers de configuration et scripts liés au SLAM et à la navigation.  
- **Vidéo de démonstration finale** : Montre le robot en action (dans la TAG version/2025/2/12)
- **Code officiel** : Comme une partie du code provient directement des tutoriels officiels de TurtleBot3, il n’est pas inclus dans cette branche. Vous pouvez vous référer aux documentations ou dépôts officiels pour l’obtenir.  

## Utilisation

- Vous pouvez vous référer aux indications du **rapport** pour installer l’environnement, effectuer la cartographie et lancer la navigation.

## Remarques

- Les **fichiers de configuration ROS** (Cartographer, navigation, etc.) sont déjà adaptés au TurtleBot 3 Burger.  
- Les scripts et configurations dédiés à **Ubuntu 18 / 20** ainsi qu’aux versions **ROS Melodic / Noetic** sont détaillés dans le rapport.  
- Certains éléments (configurations, scripts) proviennent de tutoriels ou de dépôts officiels, et ne figurent donc pas directement dans ce dépôt.

## Auteurs et contacts

- **Auteurs** : Gong Yiqiao, Bai Yue  
- Pour toute question ou suggestion, vous pouvez nous contacter aux adresses suivantes :  
  - `gongyiqiao@outlook.com`  
  - `BaiYueAlice@outlook.com`
```
