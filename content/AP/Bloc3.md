---
title: "Projet Stormshield"
date: 2025-02-23T19:53:33+05:30
draft: false
author: "Samsidine"
tags:
  - Rich content
  - Sample
  - example
image: /images/storm.png
description: ""
toc: 
Weight: 15
---

## I. Contexte de travail

Née en décembre 2010, la société CUB est une entreprise spécialisée dans l’incubation de startups partageant les mêmes valeurs de solidarité et de développement durable. Au travers de sa plate-forme web, CUB permet à des professionnels d’accéder à des espaces de travail dédiés : salles de réunion, de formation ou de séminaire.

Le concept novateur de CUB repose sur une démarche collaborative de type « BtoB », en effet CUB propose aux entreprises qui disposent d’espaces inoccupés de les louer à l’heure ou à la journée.

Armand Zaks, Michèle Ribez et Quentin Reynaud, les trois fondateurs, sont partis d’un double constat :

- en Île-de-France, 6 millions de m² de bureaux sont vacants ;
- en France, plus de 100 000 personnes travaillent ou ont déjà travaillé en espace de coworking. La France se classe au 6ᵉ rang mondial pour ce qui est du nombre d’espaces, et la pratique du coworking devrait continuer à progresser.

Forte d’une croissance très rapide, CUB fait une levée de fonds de 1,2 millions d’euros en 2016 et développe son activité pour atteindre sa dimension actuelle d’incubateur.

À la différence d’une pépinière d’entreprises classique, CUB s’adresse à des sociétés très jeunes, ou encore en création, pour leur apporter un appui lors des premières étapes de la vie de l’entreprise. Outre un parc de près de 200 m² mis à disposition des jeunes entrepreneurs, l’incubateur offre des services logistiques et d’infrastructures mutualisés, un accompagnement professionnel de conseil et de financement personnalisé aux porteurs de projets liés au digital, aux applications mobiles et au e-commerce.

Chaque agence disposera d’une adresse IPv4 publique propre et nominative. Pour cela, l’entreprise CUB a demandé auprès du RIPE NCC l’obtention d’un numéro d’AS et d’un préfixe IPv4 : 192.36.253.0/24. Elle est donc considérée comme un LIR (Local Internet Registry).

CUB met à disposition de ses clients un ensemble de solutions techniques d’accès dans un millier de salles de réunion situées dans une quarantaine de villes différentes. Les ressources et outils du Web 2.0 qui permettent aux entreprises de gérer leurs contenus et leurs connaissances de manière sécurisée sont accessibles indépendamment via des prestataires de type informatique dans les nuages (cloud computing) : partage de fichiers, gestion de projet, réseau social d’entreprise, wiki d’entreprise, etc.

Le siège social de CUB est situé à Paris, des agences sont implantées dans plusieurs grandes villes internationales : Anvers, Barcelone, Hong-Kong et Los Angeles.

La direction des systèmes d’information (DSI), située à Paris, participe étroitement aux choix stratégiques de CUB, elle a pour mission de définir et mettre en œuvre la politique informatique en accord avec la stratégie générale et ses objectifs de performance.

Le siège social est le cœur du système d’information interne de CUB, mais un service informatique de proximité (SIP) est présent sur chaque agence. Le SIP est responsable de l’assistance aux utilisateurs locaux et de la maintenance des ressources locales (infrastructure réseau et serveurs). Le SIP prend également en charge des projets qui concernent ponctuellement leur site.

<center><img src="/images/b3schema.png"></center> 

## II. Les besoins 

1) Configurer les switchs de la zone LAN et DMZ.
2) Installer le Stormshield et configurer les VLAN et les différentes adresses IP.
3) Créer et configurer les différents Serveurs DNS de la zone LAN et de la DMZ. Installer le résolveur.
4) Implémenter la politique de filtrage de l’entreprise dans le pare-feu Stormshield : créer les règles pour chaque zone ainsi que les règles de redirection de ports pour le serveur Web et le serveur DNS en DMZ.
5) Mettre en place un proxy web HTTP et HTTPS sans déchiffrement pour filtrer l’accès Web des utilisateurs du VLAN Client.
6) Configurer un NIDS pour détecter les tentatives d’intrusion.
    Mettre en place un portail captif authentifiant en lien avec un annuaire Active Directory et un serveur RADIUS.
7) Mettre en place un accès VPN pour des clients nomades avec OpenVPN.
8) Mettre en place un lien VPN site-à-site avec IPsec.
