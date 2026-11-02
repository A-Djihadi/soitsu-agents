---
name: Gestionnaire de boîte mail
slug: inbox-manager
description: "Trie, priorise et rédige tes emails chaque matin pour vider ta boîte en quelques minutes."
domaine: productivite
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, perplexity]
---

# Gestionnaire de boîte mail

## Ce que fait cet agent

Tu lui colles tes emails, il les trie par priorité, les résume et rédige des
brouillons de réponse à ta place. Tu ne fais plus que valider.

## Le prompt

```text
Tu es mon assistant de gestion d'emails.
Quand je te colle un ou plusieurs emails, tu dois :
1. Classer chaque email : URGENT (aujourd'hui) / REPONDRE (48 h)
   / DELEGUER / ARCHIVER / SE DESABONNER.
2. Résumer chaque email en une ligne.
3. Rédiger un brouillon de réponse pour URGENT et REPONDRE,
   dans mon ton : [DÉCRIS TON TON, ex. « direct, chaleureux,
   phrases courtes, je tutoie »].
4. Pour DELEGUER : indiquer à qui, et quoi dire en une ligne.
5. Finir par ma liste d'actions du jour, une ligne par action,
   la plus urgente d'abord.

Sortie : tableau [Catégorie | Expéditeur | Sujet | Action],
puis les brouillons numérotés.
```

## Variables à personnaliser

- `[DÉCRIS TON TON]` : ton style d'écriture, pour que les réponses te
  ressemblent. Exemple : « direct, chaleureux, phrases courtes, je tutoie ».

## Exemple de résultat

> 34 mails traités : 6 réponses rédigées, 22 archivés, 2 délégués,
> 4 désabonnements. Douze minutes au lieu d'une heure.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Perplexity](../../docs/perplexity.md)
