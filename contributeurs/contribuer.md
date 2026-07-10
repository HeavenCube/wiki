---
label: Guide de contribution
title: Contribuer au wiki
description: Proposez une correction fiable et vérifiez son rendu avant publication.
icon: git-pull-request
order: 190
---

# Contribuer au wiki

Toute contribution doit aider un joueur à comprendre HeavenCube sans lui présenter une supposition comme un fait. Une correction courte et vérifiée vaut mieux qu’une longue explication incertaine.

## Prérequis

- Disposer d’une information confirmée par l’équipe, la configuration du serveur ou un test reproductible.
- Lire le [guide de style](style-guide.md).
- Connaître les bases de Markdown pour modifier une page.

## Outils utiles

| Commande | Utilité |
| --- | --- |
| `git status` | Afficher les fichiers modifiés. |
| `git diff --check` | Repérer certains problèmes d’espaces. |
| `retype start` | Prévisualiser le wiki localement. |
| `retype build` | Vérifier la génération complète du site. |

## Guide étape par étape

1. **Choisissez une page.** Commencez par une erreur précise ou une information manquante.
2. **Vérifiez la source.** Notez d’où vient l’information et quand elle a été confirmée.
3. **Rédigez pour un débutant.** Expliquez le but avant les commandes et les détails techniques.
4. **Marquez l’inconnu.** Utilisez un champ précis comme `[COMMANDE DU MENU DES QUÊTES]`.
5. **Ajoutez les liens associés.** Orientez le joueur vers l’étape suivante ou le support.
6. **Testez le rendu.** Vérifiez les liens, les composants Retype et les caractères accentués.
7. **Proposez la modification.** Suivez `[PROCÉDURE DE CONTRIBUTION DU DÉPÔT]`.

## Checklist avant envoi

- [ ] Le titre et l’introduction expliquent l’utilité de la page.
- [ ] Tous les textes visibles utilisent une typographie française correcte.
- [ ] Aucune commande ni valeur serveur n’a été inventée.
- [ ] Chaque champ entre crochets décrit précisément l’information manquante.
- [ ] Les liens internes existent.
- [ ] Les images proviennent du propriétaire ou d’une source validée.
- [ ] Le build Retype réussit, si l’outil est disponible.

## Erreurs fréquentes

- Copier la commande d’un autre serveur utilisant un plugin similaire.
- Retirer un champ entre crochets sans avoir obtenu la valeur officielle.
- Ajouter une capture contenant une adresse électronique ou un identifiant privé.
- Modifier plusieurs sujets sans rapport dans la même contribution.

## Conseils pratiques

!!!tip Écrivez depuis le point de vue du joueur
Une page utile répond d’abord à quatre questions : à quoi sert la fonctionnalité, où la trouver, que faire en premier et que se passe-t-il ensuite ?
!!!

## Questions fréquentes

!!!question Puis-je ajouter une astuce personnelle ?
Oui, si elle est clairement présentée comme un conseil et si elle ne contredit pas le règlement.
!!!

!!!question Quand puis-je remplacer un champ entre crochets ?
Uniquement lorsque la valeur a été confirmée par une source propre à HeavenCube.
!!!

!!!question Puis-je ajouter une image ?
Oui, si elle a été fournie ou validée par le propriétaire. Placez-la dans `assets/images/` avec un nom descriptif et un texte alternatif précis.
!!!

## Pages associées

- [Contributeurs](README.md)
- [Guide de style](style-guide.md)
- [Accueil](../README.md)

[!backlinks]
