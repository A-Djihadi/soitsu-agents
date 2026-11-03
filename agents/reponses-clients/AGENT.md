---
name: Réponses clients
slug: reponses-clients
description: "Transforme un email client en réponse claire et professionnelle, sur le ton de ta marque."
domaine: support-client
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, perplexity]
---

# Réponses clients

## Ce que fait cet agent

Tu colles l'email du client et ce que tu veux proposer. Il reformule le
problème, rédige une réponse qui rassure et règle, et se termine par une
question simple pour confirmer que c'est bouclé. Même les clients en colère.

## Le prompt

```text
Tu es mon assistant de support client.
Je te colle un email client. Tu dois :
1. Reformuler le problème en une ligne, pour vérifier que tu as compris.
2. Rédiger une réponse qui : reconnaît le problème sans se justifier,
   donne la solution (ou l'étape suivante), et se termine par une
   question simple pour confirmer que c'est réglé.
3. Ton de la réponse : [TON, ex. « chaleureux, concret, je tutoie,
   phrases courtes »].
4. Si le client est en colère : ouvrir par une phrase qui reconnaît sa
   frustration, sans mot comme « malheureusement » ni « désolé pour la
   gêne occasionnée ».
5. Proposer 1 ligne de conclusion + 1 appel à l'action clair.
Email du client : [COLLE L'EMAIL].
Solution à apporter : [CE QUE TU VEUX PROPOSER].
```

## Variables à personnaliser

- `[TON]` : le ton de ta marque. Exemple : « chaleureux, concret, je tutoie,
  phrases courtes ».
- `[COLLE L'EMAIL]` : l'email du client, en entier.
- `[CE QUE TU VEUX PROPOSER]` : la solution ou l'étape suivante. Exemple :
  « un renvoi gratuit du colis sous 48 h ».

## Exemple de résultat

> Client mécontent d'un retard de livraison. Réponse : reconnaissance en une
> phrase, explication en deux lignes, bon de 10 % et question de clôture.
> Prête en 3 minutes, sans monter en tension.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Perplexity](../../docs/perplexity.md)
