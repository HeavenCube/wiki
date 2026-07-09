# Contribuer au wiki

Cette page explique comment proposer une correction ou une nouvelle page pour garder le wiki HeavenCube clair, fiable et utile aux joueurs.

[!badge text="Documentation" variant="primary" icon="repo"]
[!badge text="Pull request" variant="success" icon="git-pull-request"]

## Prerequis

- [ ] Avoir une information confirmee ou une correction precise.
- [ ] Respecter le [guide de style](style-guide.md).
- [ ] Ne pas ajouter de mecanique non confirmee sans `TODO`.

## Commandes utiles

| Commande | Role | Statut |
| --- | --- | --- |
| `retype start` | Lancer une previsualisation locale. | [!badge Retype\|info] |
| `retype build` | Construire le site statique. | [!badge Retype\|info] |
| `git status` | Voir les fichiers modifies. | [!badge Git\|info] |

## Guide etape par etape

>>> Choisir une page
Corrige d'abord les informations les plus utiles aux joueurs : commandes, prerequis, etapes, FAQ.

>>> Verifier l'information
Base-toi sur une source officielle : configuration serveur, annonce staff, test en jeu ou validation explicite.

>>> Rediger simplement
Ajoute des titres clairs, tableaux de commandes, callouts et liens vers les pages liees.

>>> Tester le rendu
Lance Retype localement si possible et verifie les liens internes.

>>> Proposer la modification
Ouvre une pull request ou transmets le changement a l'equipe selon le flux choisi.
>>>

## Conseils pratiques

!!!tip Priorite aux joueurs
Une bonne page repond vite a trois questions : que faut-il avoir, quelle commande utiliser, que faire ensuite ?
!!!

## Checklist de contribution

- [ ] La page a un titre clair.
- [ ] Les commandes sont dans un tableau.
- [ ] Les informations non confirmees sont marquees `TODO`.
- [ ] La FAQ contient les questions probables.
- [ ] Les liens internes fonctionnent.

## FAQ

!!!question Puis-je ajouter une astuce personnelle ?
Oui si elle n'est pas presentee comme une regle officielle et qu'elle respecte les reglements.
!!!

!!!question Puis-je retirer un TODO ?
Oui uniquement si l'information est confirmee par l'equipe ou par une source serveur fiable.
!!!

!!!question Faut-il des captures d'ecran ?
Elles sont utiles pour les menus, commandes et interfaces. Ajoute-les dans `assets/images/` avec un nom explicite.
!!!

## Pages liees

- [Guide de style](style-guide.md)
- [Accueil](../readme.md)
- [Support](../utilitaire/support.md)
- [Reglements](../reglements.md)

[!backlinks]
