---
name: Déclinaison de contenu
slug: declinaison-contenu
description: "Transforme une idée en plusieurs posts prêts à publier, pour LinkedIn, X et ta newsletter."
domaine: contenu
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, gemini]
---

# Déclinaison de contenu

## Ce que fait cet agent

Une idée, cinq formats. Tu ne repars plus de zéro pour chaque réseau : il te
sort le post LinkedIn, le post X, l'intro de newsletter, le carrousel et la
story, tous alignés sur la même idée et ton ton.

## Le prompt

```text
Tu es mon éditeur de contenu.
Je te donne une idée ou un post existant. Tu dois le décliner en 5 formats :
1. Post LinkedIn (200-300 mots) : accroche en 1 ligne, 3 points,
   conclusion + question.
2. Post X / Threads (280 caractères max) : une idée, sans hashtag.
3. Intro de newsletter (4-6 lignes) : contexte + pourquoi maintenant.
4. Carrousel LinkedIn : 6 slides, un titre + 1 ligne par slide.
5. Story : 1 phrase forte + 1 question.
Règles : pas d'emoji, pas de jargon, garder la même idée dans les
5 formats, ton : [TON, ex. « direct, je tutoie, exemples concrets »].
Public cible : [TA CIBLE].
Mon idée : [COLLE TON IDÉE OU TON POST].
```

## Variables à personnaliser

- `[TON]` : ton style d'écriture. Exemple : « direct, je tutoie, exemples
  concrets ».
- `[TA CIBLE]` : à qui tu t'adresses. Exemple : « solo founders qui veulent
  automatiser sans équipe technique ».
- `[COLLE TON IDÉE OU TON POST]` : l'idée de départ ou un post déjà écrit.

## Exemple de résultat

> Idée : « les agents IA ne remplacent pas tes outils, ils les relient ».
> Sortie : un post LinkedIn, un tweet, une intro de newsletter, un carrousel
> de 6 slides et une story. 5 publications prêtes en 10 minutes.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Gemini](../../docs/gemini.md)
