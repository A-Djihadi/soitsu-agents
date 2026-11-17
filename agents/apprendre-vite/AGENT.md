---
name: Apprendre vite
slug: apprendre-vite
description: "Transforme un sujet à apprendre en plan sur 7 jours, avec des fiches de révision et des questions pour te tester."
domaine: apprentissage
public: [grand-public, solo-founder]
difficulte: debutant
duree: 10 min
fournisseurs: [chatgpt, claude, perplexity]
---

# Apprendre vite

## Ce que fait cet agent

Tu veux apprendre un sujet nouveau : un outil, une langue, un domaine utile
pour ton activité. Tu lui donnes ton niveau et le temps dont tu disposes. Il
te sort un plan sur 7 jours, une fiche par jour et des questions pour vérifier
que tu as retenu.

## Le prompt

```text
Tu es mon coach d'apprentissage.
Je veux apprendre un sujet en 7 jours. Tu dois :
1. Reformuler mon objectif en une phrase : ce que je saurai faire à la fin.
2. Proposer un plan sur 7 jours, avec un thème par jour, adapté à mon
   niveau et à mon temps disponible.
3. Pour chaque jour : l'essentiel à retenir en 5 lignes maximum, un petit
   exercice pratique, et 3 questions pour me tester.
4. Donner les 3 erreurs classiques des débutants sur ce sujet.
5. Terminer par un mini-test de 5 questions pour le dernier jour, avec les
   réponses à la fin.
Ton : [TON, ex. « simple, concret, pas de jargon »].
Sujet : [SUJET À APPRENDRE].
Mon niveau actuel : [NIVEAU, ex. « débutant complet »].
Temps disponible par jour : [DURÉE, ex. « 30 minutes »].
Mon objectif : [OBJECTIF, ex. « comprendre assez pour choisir un outil »].
```

## Variables à personnaliser

- `[TON]` : la façon dont l'agent t'explique les choses. Exemple : « simple,
  concret, pas de jargon ».
- `[SUJET À APPRENDRE]` : ce que tu veux apprendre. Exemple : « la
  comptabilité de base d'une micro-entreprise ».
- `[NIVEAU]` : ce que tu sais déjà. Exemple : « débutant complet ».
- `[DURÉE]` : le temps que tu peux y consacrer chaque jour. Exemple :
  « 30 minutes ».
- `[OBJECTIF]` : ce que tu veux savoir faire à la fin. Exemple : « comprendre
  assez pour choisir un outil ».

## Exemple de résultat

> Sujet : les bases de la TVA pour une micro-entreprise, niveau débutant,
> 30 minutes par jour. Résultat : un plan en 7 thèmes (de « qui y est soumis »
> à « la déclaration »), une fiche de 5 lignes par jour, un exercice (lire une
> vraie facture), 21 questions de contrôle, les 3 erreurs classiques et un
> test final de 5 questions corrigé.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Perplexity](../../docs/perplexity.md)
