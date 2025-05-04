---
title: "Supervision réseau avec Zabbix"
date: 2024-01-23T19:53:33+05:30
draft: false
author: "Samsidine"
tags:
  - Rich content
  - Sample
  - example
image: /images/zabbix.png
description: ""
toc: 
Weight: 8
---

## I. Contexte de travail

L’entreprise CUB possède de nombreuses machines virtuelles (les serveurs DNS dans les différentes zones, le serveur Web, le pare-feu) ainsi que des équipements réseaux (switchs CISCO). il est important pour la DSI d’avoir un tableau de bord permettant de voir en temps réel l’état des machines et des équipements réseaux

## II. Les besoins 

Il vous est demandé de mettre en place une solution de supervision du réseau (Switchs Cisco) et des machines virtuelles.

- La machine doit être intégré dans la bonne zone du lan de votre agence.
- La machine doit être accessible depuis son nom DNS : zabbix.lan.agence.cub.org
- Zabbix doit être installé en français.
- La machine doit utiliser le résolveur du lan comme serveur DNS.
- On doit avoir un tableau de bord qui permettent de voir l’état de tous les systèmes en temps réel.
- On doit recevoir les alertes sur Discord.

## III. Procédure 

Vous pouvez trouver la procédure au lien suivant:
