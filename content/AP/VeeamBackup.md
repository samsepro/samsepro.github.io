---
title: "Sauvegarde avec Veeam Backup ans Replication"
date: 2025-03-11T19:53:33+05:30
draft: false
author: "Samsidine"
tags:
  - Rich content
  - Sample
  - example
image: /images/backup.jpeg
description: ""
toc: 
Weight: 10
---

## I - Contexte

L’entreprise CUB possède de nombreuses agences. Chacune dispose de serveurs et il est impératif de procéder à des sauvegardes régulière de ces serveurs.

Afin de ne pas tout perdre en cas d’attaque par Cryptolocker/Ransomware il est impératif de mettre en place une stratégie de sauvegarde immuable.

## II - Les besoins

L’entreprise CUB a donc besoin :

- Mettre en place un serveur de sauvegarde sous Windows server avec VEEAM Backup and Replication
- Installer le serveur de sauvegarde dans le bon VLAN de l’entreprise CUB et prévoir un disque d’au moins 80 GiO pour l’installation de Veeam.
- Sauvegarder le serveur Windows sur le NAS (172.17.50.211 ou 172.17.50.212 ou 172.17.50.213 ou 172.17.50.214 selon votre bâtiment) avec les identifiants admin/btssio.
- Sauvegarder 1 serveur Linux sur le NAS.

## III - Procédure
Vous pouvez trouver la procédure au lien suivant:
