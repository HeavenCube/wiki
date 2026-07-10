---
label: Guide de style
title: Guide de style du wiki
description: Rédigez des pages cohérentes, accessibles et compatibles avec Retype.
icon: typography
order: 180
---

# Guide de style du wiki

Ce guide fixe les règles éditoriales du wiki HeavenCube. Son objectif est de produire des pages naturelles en français, faciles à parcourir et fiables pour les nouveaux joueurs.

## Principes essentiels

1. Expliquez une fonctionnalité avant de donner ses commandes.
2. Définissez chaque terme technique lors de sa première utilisation.
3. Utilisez des phrases courtes et adressez-vous directement au joueur.
4. Ne confirmez jamais une mécanique propre au serveur sans source.
5. Utilisez les accents, les apostrophes et la ponctuation françaises.

## Structure recommandée

Une page de fonctionnalité peut contenir :

- une introduction qui répond à « à quoi cela sert-il ? » ;
- des prérequis utiles ;
- le moyen d’accéder à la fonctionnalité ;
- un guide étape par étape ;
- les commandes confirmées ou les champs à renseigner ;
- un exemple concret ;
- les erreurs fréquentes ;
- des conseils et questions fréquentes ;
- des pages associées et des backlinks.

Ne créez pas une section vide uniquement pour respecter ce modèle.

## Informations inconnues

Utilisez un champ en majuscules qui décrit exactement la donnée attendue :

```md
[COMMANDE DU MENU DES MÉTIERS]
[PRIX DE CRÉATION D’UN PWARP]
[NOMBRE MAXIMAL DE PROTECTIONS]
[DÉLAI HABITUEL DE RÉPONSE DU SUPPORT]
```

Dans le texte visible, regroupez les incertitudes dans un seul avertissement :

```md
!!!warning Information à confirmer
Cette partie sera complétée dès que les informations exactes du serveur auront été vérifiées.
!!!
```

## Composants Retype

+++ Avertissement
```md
!!!warning Titre clair
Expliquez ce qui manque et qui doit le confirmer.
!!!
```
+++ Onglets
```md
+++ Édition Java
Étapes pour Java.
+++ Édition Bedrock
Étapes pour Bedrock.
+++
```
+++ Carte
```md
[!card layout="compact" title="Rejoindre" text="Préparer Minecraft." icon="sign-in"](../rejoindre.md)
```
+++ Bouton
```md
[!button text="Rejoindre HeavenCube" icon="sign-in"](../rejoindre.md)
```
+++

## Images

Ne générez pas d’image pour remplir un espace. Utilisez un commentaire éditorial lorsque le propriétaire doit fournir une capture :

```md
<!--
IMAGE À AJOUTER

Sujet : menu réel des protections de terrain avec les permissions visibles
Fichier recommandé : assets/images/menu-protections.webp
Dimensions recommandées : 1000 × 1000 px
Format recommandé : WebP
Texte alternatif : Menu des permissions d’une protection de terrain
-->
<!-- ![Menu des protections](assets/images/menu-protections.webp) -->
```

## Dimensions recommandées

| Type d’image | Dimensions |
| --- | ---: |
| Bannière principale | 1600 × 500 px |
| Introduction d’une section | 1400 × 600 px |
| Capture de l’interface Minecraft | 1200 × 675 px |
| Capture d’un menu ou inventaire | 1000 × 1000 px |
| Logo | 512 × 512 px |
| Image de partage social | 1200 × 630 px |

## Arborescence éditoriale

:::code source="../includes/arborescence.txt" title="Organisation des pages" :::

## Vérifications

| Commande | Utilité |
| --- | --- |
| `retype build` | Vérifier la syntaxe et générer le wiki. |
| `git diff --check` | Repérer certains problèmes de formatage. |
| `rg "index\\.md"` | Repérer d’anciens liens de page d’accueil. |

## Questions fréquentes

!!!question Les noms de fichiers doivent-ils contenir des accents ?
Non. Les noms peuvent rester en minuscules, sans espace ni accent, afin de conserver des URL simples. Les textes visibles doivent toutefois être écrits en français correct.
!!!

!!!question Peut-on publier une commande avec la mention « à confirmer » ?
Non. Remplacez-la par un champ précis comme `[COMMANDE DE RETOUR AU POINT D’ACCUEIL]` jusqu’à sa validation.
!!!

!!!question Comment nommer une image ?
Utilisez un nom descriptif comme `menu-quetes.webp` ou `zone-accueil.webp`.
!!!

## Pages associées

- [Contributeurs](README.md)
- [Guide de contribution](contribuer.md)
- [Accueil](../README.md)

[!backlinks]
