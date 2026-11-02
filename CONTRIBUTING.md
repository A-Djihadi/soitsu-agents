# Contribuer

Merci de vouloir enrichir la bibliothèque. Ajouter un agent prend cinq minutes.

## Ajouter un agent

1. Copie [`agents/_template/AGENT.md`](agents/_template/AGENT.md) vers
   `agents/<slug>/AGENT.md` (slug en minuscules, tirets, ex. `inbox-manager`).
2. Remplis le frontmatter (tous les champs) :
   - `name`, `slug`, `description` — obligatoires
   - `domaine` — un des domaines déjà utilisés ou un nouveau
   - `public` — `grand-public`, `solo-founder`, ou les deux
   - `difficulte` — `debutant`, `intermediaire`, `avance`
   - `duree` — temps d'installation estimé
   - `fournisseurs` — où l'agent a été testé
3. Remplis les sections : ce que fait l'agent, le prompt (les seuls éléments à
   modifier sont entre crochets `[...]`), les variables à personnaliser, un
   exemple de résultat.
4. Ajoute une ligne dans [`agents/README.md`](agents/README.md).
5. Ouvre une PR sur `main`.

## Règles de qualité

- Le prompt doit être **directement utilisable** : les seuls éléments à
  modifier sont entre crochets `[...]`.
- Pas de secret, pas de donnée personnelle, pas de lien interne.
- Un exemple de résultat concret et réaliste.
- Français, tutoiement, sans emoji.

## Améliorer un agent existant

Ouvre une issue ou une PR avec le changement et sa raison. Un prompt est un
produit : explique ce que ton changement améliore et dans quel cas.
