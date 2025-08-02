---
icon: rocket-launch
---

# Démarrage rapide

## 2.1.  Généralités

**Proxmox VE** (Virtual Environment) est une solution complète de virtualisation **open source** qui combine :

* La virtualisation KVM pour les machines virtuelles ;
* La virtualisation légère LXC pour les conteneurs Linux ;
* Une interface web intuitive pour gérer tous les aspects du cluster ;
* Une API RESTful pour les automatisations ;
* Des outils intégrés pour la sauvegarde, restauration et haute disponibilité.

Basé sur **Debian GNU/Linux**, il intègre nativement des outils comme `qemu`, `lxc`, `zfs`, `Ceph`, etc.

## 2.2.  Fonctionnalités clés

* Gestion centralisée des VMs et CTs
* Snapshots, clones et backups planifiables
* Migration en ligne des VMs (si cluster)
* Support de ZFS, Ceph, iSCSI, NFS, CIFS…
* Contrôle d’accès par rôles (RBAC)
* API complète pour les automatisations

## 2.3.  Composants principaux

* **Proxmox VE Web UI** : interface de gestion graphique en HTTPS
* **PVE Manager** : service de gestion principal
* **QEMU/KVM** : hyperviseur pour les VMs
* **LXC** : conteneurs Linux
* **pve-cluster** : gestion du cluster et synchronisation
* **Proxmox Backup Server (optionnel)** : sauvegarde centralisée
* **Ceph (optionnel)** : stockage distribué

## 2.4.  Cas d’usage

Proxmox VE peut être utilisé dans de nombreux contextes :

* **Virtualisation en entreprise** : hébergement de serveurs internes (LDAP, mail, web, etc.)
* **Laboratoires d’apprentissage** : environnement d’expérimentation isolé
* **Hébergement mutualisé** ou **Cloud privé**

## 2.5.  Installation

Voici les **étapes essentielles** pour installer et commencer à utiliser Proxmox VE dans un environnement de test ou de production léger :

1. **Télécharger l’ISO de Proxmox VE** depuis le site officiel :\
   &#x20;[https://www.proxmox.com/en/downloads](https://www.proxmox.com/en/downloads)
2. **Créer une machine virtuelle** sur VMWare WorkStation ou ESXI, VrtualBox, Hyper-V et chargez y l'ISO ou  **Créer une clé USB bootable** avec l’ISO, à l’aide d’un outil comme **Rufus**, **balenaEtcher** ou `dd` sous Linux pour une installation bare métal.
3. **Démarrer sur l’ISO**, choisir "Install Proxmox VE", accepter la licence et suivre les étapes de l’installateur :
   * Sélection du disque d’installation ;
   * Configuration réseau (IP statique de préférence) ;
   * Mot de passe administrateur root ;
   * Nom d’hôte du serveur.
4. Une fois l’installation terminée et le serveur redémarre, accéder à l’interface web :\
   📍 `https://<IP_du_serveur>:8006`
5. Se connecter avec l’utilisateur `root` et le mot de passe défini.

> **💡&#x20;**_**Astuce :** Vous pouvez également ajouter d’autres nœuds au cluster, configurer des sauvegardes planifiées et surveiller les performances du système via le tableau de bord web._
