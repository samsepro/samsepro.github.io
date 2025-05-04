---
title: "Infrastructure Haute Disponibilité"
date: 2025-02-25T19:53:33+05:30
draft: false
author: "Samsidine"
tags:
  - Rich content
  - Sample
  - example
image: /images/Haproxy.png
description: ""
toc: 
Weight: 9
---

## I - Contexte

L’entreprise CUB, comme toute entreprise moderne, repose de plus en plus sur des infrastructures informatiques pour ses opérations quotidiennes. Les interruptions de service ou les pannes peuvent avoir des conséquences graves sur la productivité, la satisfaction des clients et la réputation de l’entreprise.

## II - Mission 1
## Les besoins

Votre agence doit pouvoir faire face à une panne du serveur Active Directory car c’est un élément crucial dans votre infrastructure. Vous mettrez donc en place une redondance de votre controleur de domaine Active Directory.
## III - Mission 2 :
## Les besoins

- L’entreprise a besoin que vous mettiez en production ce site dans votre agence. Il est également impératif que ce site soit disponible quoi qu’il arrive et c’est pourquoi vous devrez mettre en place un système de haute disponibilité en insttallant ce site sur 2 conteneurs différents. Vous utiliserez également HAProxy sur votre pfsense pour garantir cette haute disponibilité et une répartition de charge entre les 2 conteneurs qui font tourner ce site.
- Le site doit pouvoir supporter une tolérance de panne. Donc vous devez faire une répartition de charge avec un reverse Proxy et utiliser un outil d’équilibrage de charge comme Docker Swarm et Kubernetes pour vos conteneurs Docker.

## IV - Mission 3 :
## Les besoins

Votre responsable vous demande de mettre en place une solution d’orchestration plus avancée. Vous devez donc remplacer votre stack Docker Swarm par Kubernetes. Sous Ubuntu et ses versions dérivés, il existe l’application microk8s qui permet d’installer Kubernetes de manière très simplifiée.

## V - Procédure
Vous pouvez trouver la procédure au lien suivant: 
