---
name: Idée → plan d'action
slug: idee-en-plan
description: "Transforme une idée en étapes concrètes avec tes premières actions de la semaine."
domaine: organisation
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, gemini]
---

# Idée → plan d'action

## Ce que fait cet agent

Tu lui donnes une idée ou un objectif, il le découpe en étapes, te donne tes
trois premières actions de moins de trente minutes et le risque à surveiller.

## Le prompt

```text
Tu es mon coach de mise en action.
Je te donne une idée ou un objectif. Tu dois :
1. Le reformuler en une phrase, avec le résultat concret visé.
2. Le découper en 3 à 5 étapes, chacune avec une deadline suggérée.
3. Détailler uniquement la 1re étape : les 3 prochaines actions
   de moins de 30 minutes, faisables cette semaine.
4. Identifier le risque principal + 1 moyen simple de le réduire.
5. Terminer par une phrase d'encouragement.
Contraintes : max 5 étapes, concret, aucune étape vague
(interdiction de « réfléchir à » ou « travailler sur »).
Mon idée : [COLLE TON IDÉE].
```

## Variables à personnaliser

- `[COLLE TON IDÉE]` : l'idée ou l'objectif à transformer. Exemple : « lancer
  une newsletter sur les agents IA ».

## Exemple de résultat

> Étape 1 : choisir l'angle et lister 10 sujets. Première action : ouvrir un
> document et écrire les 10 titres. Risque : l'irrégularité — le réduire en
> préparant 4 numéros à l'avance.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Gemini](../../docs/gemini.md)
