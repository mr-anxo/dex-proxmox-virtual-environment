---
icon: book-open
---

# Introduction

Cette documentation présente les principes de fonctionnement de **Proxmox VE**, les étapes de sa configuration, ainsi que les principales actions permettant de réaliser les **tâches d’exploitation courantes** : gestion de machines virtuelles, de conteneurs, des sauvegardes, de la haute disponibilité, et bien plus.

Elle s’adresse aux personnes souhaitant découvrir, déployer ou maintenir une infrastructure virtuelle basée sur Proxmox dans un environnement personnel, professionnel ou en laboratoire.

***

## 1.1.  Objectifs de la documentation

L’objectif de cette documentation est de permettre à tout lecteur de :

* Comprendre l’architecture et le fonctionnement de Proxmox VE ;
* Savoir comment installer et configurer un hôte Proxmox ;
* Mettre en place et gérer des machines virtuelles (VM) ou des conteneurs (CT) ;
* Exploiter les fonctionnalités avancées comme les snapshots, les sauvegardes ou le clustering ;
* Identifier les cas d’usage adaptés à l’outil.
* S'exercer sur la prise en main de l'outil

***

## 1.2.  Public concerné

Cette documentation est destinée à :

* Les **administrateurs systèmes et réseaux** en charge d’une infrastructure de virtualisation ;
* Les **techniciens IT** en formation ou en montée en compétence ;
* Les **étudiants en informatique** ou passionnés souhaitant apprendre la virtualisation open source ;
* Toute personne intéressée par le **déploiement de serveurs virtuels** pour des environnements de test, de production ou de formation.

***

## 1.3.  Prérequis techniques et matériels

Avant de déployer Proxmox VE, il est recommandé d’avoir les éléments suivants :

**Connaissances de base :**

* Utilisation de la **ligne de commande Linux** ;
* Notions de **réseaux (IP, passerelles, DHCP, DNS, ...)** ;
* Compréhension de base des concepts de **virtualisation**.

**Matériel recommandé :**

* Avoir un ordinateur avec un processeur **compatible virtualisation** (Intel VT-x / AMD-V) ;
* Au moins **8 Go de RAM** (16 Go ou plus recommandé pour héberger plusieurs VM) ;
* Connexion réseau stable

***

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><i class="fa-rocket-launch">:rocket-launch:</i>  <strong>Démarrage rapide</strong></td><td>Mettez en place votre premier serveur Proxmox VE</td><td></td><td><a href="demarrage-rapide.md">demarrage-rapide.md</a></td></tr><tr><td><i class="fa-presentation-screen">:presentation-screen:</i>  <strong>Présentation</strong></td><td>Découvrez Proxmox VE et ses composantes</td><td></td><td><a href="pour-commencer/presentation.md">presentation.md</a></td></tr><tr><td><i class="fa-download">:download:</i>   <strong>Installation</strong></td><td>Installer Proxmox VE dans votre environnement</td><td></td><td><a href="pour-commencer/installation.md">installation.md</a></td></tr></tbody></table>



***

`#ProxmoxVE` `#Virtualisation` `#Infrastructure` `#KVM` `#LXC` `#Cluster` `#Sauvegarde` `#Réseau`
