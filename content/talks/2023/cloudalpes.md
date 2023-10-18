---
title: "D’un modèle d'IA dans un notebook à un service temps réel: architecturons!"
conference: "Cloud Alpes"
slideskey: "g7C1ZxKnjJeHU6"
videokey: "ClF21mgoj7U?si=d8OtQgGJ2vzMHSUB"
date: 2023-09-06T14:53:19+02:00
language: Français
tags: ["architecture", "ML"]
---

## Abstract

Bonne nouvelle, mon data-scientist a fini de travailler sur son modèle. Celui-ci donne les résultats attendus, il est sérialisé comme il faut... il ne reste plus qu'à le déployer!
Oui, mais comment ?

Dans cette présentation, vous verrez un exemple de conception pas à pas d'une application dédiée au déploiement de modèles d'IA avec une api HTTP very low latency. Nous partirons du "modèle" comme une brique boite noire et construirons l'architecture du système autour. Nous verrons notamment :

- La différence entre le preprocessing fait par le data scientist en mode traitement batch et le preprocessing en mode traitement au fil de l'eau nécessaire pour le déploiement
- Des astuces pour améliorer la latence
- Des architectures possibles pour gérer l'ingestion des données
- … et d'autres idées pour passer de la data science en POC à un vrai déploiement en production.

A la fin de ce talk, vous aurez les clefs pour que la conception d'une telle application se passe de façon sereine, et sans mauvaise surprise une fois la mise en production faite. Peut-être que nous arriverons même à réconcilier data science et data engineering ? 

## Recording and slides