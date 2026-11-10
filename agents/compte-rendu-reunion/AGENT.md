---
name: Compte-rendu de réunion
slug: compte-rendu-reunion
description: "Transforme des notes de réunion en compte-rendu clair : décisions, actions, responsables, échéances."
domaine: reunion
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, gemini]
---

# Compte-rendu de réunion

## Ce que fait cet agent

Tu colles tes notes, même en vrac. Il en sort un compte-rendu structuré : ce
qui a été décidé, qui fait quoi, pour quand. Tout le monde repart avec les
mêmes infos, sans relire trente minutes de discussion.

## Le prompt

```text
Tu es mon assistant de compte-rendu de réunion.
Je te colle mes notes brutes. Tu dois :
1. Résumer la réunion en 3 lignes : objectif, sujet principal, conclusion.
2. Lister les décisions prises, une par ligne, sans les justifier.
3. Lister les actions : pour chacune, [QUI] fait [QUOI], pour [QUAND].
4. Ajouter une section « Points ouverts » : ce qui n'est pas tranché, et
   qui le traite.
5. Ton : [TON, ex. « neutre, phrases courtes, au présent »].
Notes de la réunion : [COLLE TES NOTES, EN VRAC].
Participants : [NOMS ET RÔLES].
```

## Variables à personnaliser

- `[TON]` : le ton du compte-rendu. Exemple : « neutre, phrases courtes, au
  présent ».
- `[COLLE TES NOTES, EN VRAC]` : tes notes brutes, sans les nettoyer.
- `[NOMS ET RÔLES]` : les participants. Exemple : « Marc (dev), Léa
  (marketing), moi (direction) ».

## Exemple de résultat

> Notes en vrac d'une réunion produit de 45 minutes. Sortie : 3 décisions,
> 5 actions avec responsable et date, 2 points ouverts. Compte-rendu envoyé
> aux participants 5 minutes après la réunion, au lieu du lendemain.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Gemini](../../docs/gemini.md)
