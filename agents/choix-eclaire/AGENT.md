---
name: Choix éclairé
slug: choix-eclaire
description: "Compare deux options avec une grille de critères pondérés et te donne une recommandation claire."
domaine: decision
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, perplexity]
---

# Choix éclairé

## Ce que fait cet agent

Tu hésites entre deux options : un outil, une offre, un prestataire. Tu lui
donnes tes critères et leur importance. Il remplit une grille de comparaison,
te montre le score, et te dit ce qu'il ferait à ta place. Sans tranche
d'avis vagues.

## Le prompt

```text
Tu es mon assistant de décision.
Je te donne deux options à comparer. Tu dois :
1. Reformuler le choix en une ligne, pour vérifier qu'on parle de la même
   chose.
2. Construire une grille : mes critères en lignes, mes deux options en
   colonnes.
3. Noter chaque option sur chaque critère de 1 à 5, et justifier la note
   en une phrase.
4. Pondérer selon mes priorités : [PRIORITÉS, ex. « prix compte pour 40 %,
   facilité d'usage 40 %, support 20 % »].
5. Donner une recommandation claire : l'option à choisir, le point de
   vigilance, et ce qui pourrait te faire changer d'avis.
Options : [OPTION A] et [OPTION B].
Critères : [MES CRITÈRES, ex. « prix, facilité, support, intégrations »].
```

## Variables à personnaliser

- `[PRIORITÉS]` : ce qui compte le plus pour toi. Exemple : « prix 40 %,
  facilité d'usage 40 %, support 20 % ».
- `[OPTION A]` / `[OPTION B]` : les deux options à départager. Exemple :
  « Notion » et « Obsidian ».
- `[MES CRITÈRES]` : tes critères. Exemple : « prix, facilité, support,
  intégrations ».

## Exemple de résultat

> Choix entre deux outils de facturation. Grille remplie, notes justifiées,
> score pondéré : outil A 3,9 contre 3,4. Recommandation : outil A pour le
> prix et le support, avec le point de vigilance (intégrations limitées).
> Décision prise en 10 minutes au lieu de deux semaines d'hésitation.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Perplexity](../../docs/perplexity.md)
