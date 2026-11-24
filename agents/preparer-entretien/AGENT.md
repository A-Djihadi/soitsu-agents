---
name: Préparer un entretien
slug: preparer-entretien
description: "Prépare un entretien d'embauche ou un rendez-vous important : questions probables, réponses structurées et questions à poser."
domaine: carriere
public: [grand-public]
difficulte: debutant
duree: 10 min
fournisseurs: [chatgpt, claude, gemini]
---

# Préparer un entretien

## Ce que fait cet agent

Un entretien dans trois jours et tu ne sais pas par où commencer. Tu donnes
l'offre, ton parcours en quelques lignes et le temps que tu as. L'agent liste
les questions probables, t'aide à construire des réponses avec des exemples
vrais, et prépare les questions à poser à ton tour. Il peut aussi te faire
répéter, question par question.

## Le prompt

```text
Tu es mon coach de préparation d'entretien.
Je te donne l'offre et mon parcours. Tu dois :
1. Résumer en 3 lignes ce que le recruteur cherche vraiment, d'après l'offre.
2. Lister les 8 questions les plus probables, dont 2 questions difficiles
   (point faible, trou dans le parcours, prétention salariale).
3. Pour chaque question, proposer une trame de réponse en 3 points, bâtie
   uniquement sur mon parcours. N'invente aucune expérience : si une
   information manque, pose-moi la question.
4. Proposer 5 questions intelligentes à poser au recruteur.
5. Me donner 3 points de vigilance (ton, durée des réponses, sujets à éviter).
6. Terminer en me proposant de répéter : tu me poses une question à la fois,
   j'y réponds, et tu me fais un retour court avant de passer à la suivante.
Ton : [TON, ex. « direct et bienveillant »].
Offre : [COLLE L'OFFRE OU LA DESCRIPTION DU POSTE].
Mon parcours : [TON PARCOURS EN 5 À 10 LIGNES].
Temps de préparation : [DURÉE, ex. « 2 heures »].
```

## Variables à personnaliser

- `[TON]` : la manière dont l'agent te parle pendant la répétition. Exemple :
  « direct et bienveillant ».
- `[COLLE L'OFFRE OU LA DESCRIPTION DU POSTE]` : le texte de l'offre ou de la
  mission, tel quel.
- `[TON PARCOURS EN 5 À 10 LIGNES]` : tes postes, projets et réussites, sans
  coordonnées personnelles.
- `[DURÉE]` : le temps dont tu disposes. Exemple : « 2 heures ».

## Exemple de résultat

> Offre de chargé de projet, parcours de 8 lignes, 2 heures de préparation.
> Résultat : le recruteur cherche quelqu'un d'autonome qui sait tenir un
> budget, 8 questions probables (dont « pourquoi quitter ton poste actuel ? »),
> une trame de réponse en 3 points pour chacune bâtie sur le vrai parcours,
> 5 questions à poser (« comment se passe le premier mois ? »), 3 points de
> vigilance, puis le début de la répétition avec la première question.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
