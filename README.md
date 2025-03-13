# Administration Système

Porte sur les fondamentaux de l’administration système, couvrant l’installation, la gestion et la supervision des systèmes informatiques, en mettant l’accent sur la gestion des logs, le déploiement et la tolérance aux pannes.

## Notions abordées
- Installation de paquets.
- Gestion de logs.
- Outils de supervision et de métrologie.
- Déploiement de machines sur un réseau (boot PXE, TFTP...).
- Démarrage du système (systemd, SysV init).
- Récupération d’un système (BIOS, UEFI, GRUB, single user).
- Gestion de volumes logiques (LVM).
- Tolérance aux défaillances d’une unité de stockage (RAID logiciel).

## Objectifs
- Maîtriser les aspects de base de l’administration système.
- Introduction aux outils de supervision et de métrologie.

## Description

Ce répertoire contient l’ensemble des commandes exécutées sur différentes machines virtuelles (VM) dans le cadre de l’administration système. Il sert de journal de bord pour documenter les actions effectuées sur chaque système.
Structure des fichiers

### Les commandes sont classées par système d’exploitation pour une consultation simplifiée :

    Ubuntu : ubuntu_commands.md
    Rocky Linux : rocky_commands.md
    CentOS : centos_commands.md

Chaque fichier contient une liste chronologique des commandes utilisées, accompagnées d’explications lorsque nécessaire.
## Objectifs

    Assurer une traçabilité des actions effectuées sur chaque machine.
    Permettre la reproduction et l’automatisation des configurations.
    Faciliter le dépannage et la gestion des systèmes.

## Remarques

    Certaines commandes nécessitent des privilèges d’administration (sudo).
    Les configurations spécifiques sont expliquées directement dans les fichiers correspondants.
    Le contenu de ce répertoire est mis à jour régulièrement en fonction de l’évolution du projet.
