---
title: Importation d'images ISO 
slug: image-import
excerpt: "Gestion des images ISO à partir de Prism Central"
section: Premiers pas
order: 04
---

**Dernière mise à jour le 24/02/2022**

## Objectif

Être capable d'ajouter des images ISO dans le système Nutanix pour les utiliser ultérieurement lors d'installation des systèmes d'exploitations.

> [!warning]
> OVHcloud vous met à disposition des services dont la configuration, la gestion et la responsabilité vous incombent. Il vous appartient donc de ce fait d’en assurer le bon fonctionnement.
>
> Ce guide a pour but de vous accompagner au mieux sur des tâches courantes. Néanmoins, nous vous recommandons de faire appel à un prestataire spécialisé si vous éprouvez des difficultés ou des doutes concernant l’administration, l’utilisation ou la mise en place d’un service sur un serveur.
>
> Certains logiciels nécessitent une licence comme les produits Microsoft il faudra alors s'assurer que tous les systèmes et logiciels installés possèdent ces licences.

## Prérequis

- Disposer d'un cluster Nutanix dans votre compte OVHcloud
- Être connecté à votre [espace client OVHcloud](https://www.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/fr/&ovhSubsidiary=fr)
- Être connecté à Prism Central sur le cluster

## Présentation du système d'images dans Nutanix

Les images sont des fichiers importés de format divers comme des images ISO mais il est aussi possible d'importer la plupart des images d'ordinateurs virtuels existants (vhdx, qcow2, etc...).

L'importation des images se fait soit à partir de Prism Central ou de Prism Element. Cette documentation décrit l'importation d'une image à partir de Prism Central.

Il est possible de faire l'importation d'images à partir d'un fichier local ou d'un lien URL.

Pour plus de détails sur la création d'images reportez-vous à la section « [Aller plus loin](#gofurther) » de ce guide.

## En pratique

En haut à gauche Cliquez sur `l'icone avec 3 traits`{.action} 

![Affichage du menu de gauche](images/PrismCentralDashboardWithLeftMenu.PNG)

Dépliez `Compute & Storage`{.action} Cliquez sur `Images`{.action}.

![Menu de gauche déplié avec Image surlignée](images/PrismCentralLefMenuToImage.PNG).

Cliquez sur `Add Image`{.action}.

![Prism Central - Gestion des Images](images/PrismCentralAddImage.PNG)

Cliquer sur `Add File`{.action}

![Fenêtre d'ajout d'une image](images/AddImage01.PNG)

Sélectionner le fichier et cliquer sur `Open`{.action}

![Fenêtre des options d'ajout d'une image partie 1](images/AddImage02.PNG)

Saisissez le nom du fichier, une description ensuite `Cliquez sur Next`{.action}

![Fenêtre des options d'ajout d'une image partie 2](images/AddImage03.PNG)

Laissez les options par défaut et `Cliquez sur Save`{.action}

![Fenêtre des options d'ajout d'une image partie 3](images/AddImage04.PNG)

L'image importée apparait dans le tableau de bord des images dans Prism Central

![Tableau de bord des images avec nouvelle Image - Prism Central](images/PrismCentralDashboardImagesWithNewImages.PNG)


## Aller plus loin <a name="gofurther"></a>

[Présentation d'un cluster Nutanix](https://docs.ovh.com/fr/nutanix/nutanix-hci/)

[Documentation Nutanix sur l'importation des images à partir de Prism Central](https://portal.nutanix.com/page/documents/details?targetId=Prism-Central-Guide-Prism-v5_20:mul-image-import-pc-t.html)

[Documentation Nutanix sur l'importation des images à partir de Prism Element](https://portal.nutanix.com/page/documents/details?targetId=Web-Console-Guide-Prism-v5_20:wc-image-configure-acropolis-wc-t.html)

[Les licences Nutanix](https://www.nutanix.com/products/software-options)

Échangez avec notre communauté d'utilisateurs sur <https://community.ovh.com/>.