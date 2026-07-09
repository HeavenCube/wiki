# Guide de style du wiki

Le guide de style garde les pages coherentes, faciles a lire et utiles aux joueurs, meme quand plusieurs personnes contribuent.

[!badge text="Style" variant="primary" icon="typography"]
[!badge text="Retype" variant="info" icon="book"]

## Prerequis

- [ ] Connaitre l'objectif du wiki : aider les joueurs.
- [ ] Utiliser un francais clair et direct.
- [ ] Verifier les informations serveur avant de les affirmer.

## Commandes utiles

| Commande | Role | Statut |
| --- | --- | --- |
| `retype start` | Previsualiser le wiki. | [!badge Retype\|info] |
| `retype build` | Verifier la generation statique. | [!badge Retype\|info] |
| `git diff --check` | Detecter certains problemes d'espaces. | [!badge Git\|info] |

## Structure recommandee

Chaque page joueur doit contenir :

- [ ] Un titre clair.
- [ ] Une courte introduction.
- [ ] Les prerequis.
- [ ] Les commandes utiles.
- [ ] Un guide etape par etape.
- [ ] Des conseils pratiques.
- [ ] Une FAQ.
- [ ] Des liens vers les pages liees.

## Guide etape par etape

>>> Commencer par le besoin joueur
Explique ce que la page permet de faire avant d'entrer dans les details.

>>> Utiliser les composants Retype
Ajoute des callouts pour les avertissements, des tabs pour les variantes, des tableaux pour les commandes et des boutons pour les actions principales.

>>> Marquer l'incertain
Quand une valeur manque, ecris `TODO : confirmer ...` au lieu d'inventer.

>>> Relier les pages
Ajoute des liens internes et garde `[!backlinks]` en bas de page quand c'est utile.
>>>

## Exemples Retype

+++ Callout
```md
!!!tip Conseil
Texte du conseil.
!!!
```
+++ Tabs
```md
+++ Java
Etapes Java.
+++ Bedrock
Etapes Bedrock.
+++
```
+++ Bouton
```md
[!button text="Rejoindre" icon="sign-in"](../rejoindre.md)
```
+++

## Conseils pratiques

!!!tip Ton editorial
Ecris comme si tu accompagnais un nouveau joueur : clair, chaleureux, concret, sans supposer qu'il connait les plugins.
!!!

## FAQ

!!!question Peut-on utiliser des accents ?
Oui, les pages sont en francais. Garde simplement les noms de fichiers en minuscules, sans espaces.
!!!

!!!question Comment nommer une image ?
Utilise un nom descriptif comme `claims-menu.png` ou `spawn-portail-survie.png`.
!!!

!!!question Que faire si une commande est incertaine ?
Ajoute-la avec le badge `[!badge A confirmer|warning]` et un `TODO` explicite.
!!!

## Pages liees

- [Contribuer](contribuer.md)
- [Accueil](../readme.md)
- [Support](../utilitaire/support.md)

[!backlinks]
