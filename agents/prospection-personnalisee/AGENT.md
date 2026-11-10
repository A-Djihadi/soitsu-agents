---
name: Prospection personnalisée
slug: prospection-personnalisee
description: "Transforme une liste de prospects en messages courts et personnalisés, sans effet spam."
domaine: prospection
public: [solo-founder, grand-public]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, gemini]
---

# Prospection personnalisée

## Ce que fait cet agent

Tu lui donnes un prospect et ce que tu proposes. Il écrit un message court,
qui ouvre une vraie conversation, en s'appuyant sur un détail précis du
prospect. Fini le copier-coller qui sonne faux : chaque message part de la
personne, pas de ton pitch.

## Le prompt

```text
Tu es mon assistant de prospection.
Je te donne un prospect et mon offre. Tu dois :
1. Identifier un point d'accroche concret chez le prospect : [DÉTAIL, ex.
   « il vient de recruter un responsable marketing »].
2. Écrire un message d'ouverture de 4 à 6 lignes qui : mentionne ce détail
   sans flatterie, relie mon offre à son problème, et pose une seule
   question ouverte.
3. Ton : [TON, ex. « direct, je tutoie, zéro formule toute faite »].
4. Interdit : « j'espère que vous allez bien », superlatifs vides, lien
   en premier message, plus d'une question.
5. Terminer par 2 variantes : une plus courte (2 lignes), une plus formelle
   (pour un grand compte).
Prospect : [NOM, POSTE, ENTREPRISE, CE QU'IL PUBLIE OU FAIT].
Mon offre : [CE QUE JE VENDS OU PROPOSE, EN UNE PHRASE].
```

## Variables à personnaliser

- `[DÉTAIL]` : le point d'accroche chez le prospect. Exemple : « il vient de
  recruter un responsable marketing ».
- `[TON]` : ton style. Exemple : « direct, je tutoie, zéro formule toute
  faite ».
- `[NOM, POSTE, ENTREPRISE, ...]` : les infos du prospect. Exemple :
  « Marie, fondatrice de Studio Lumière, poste sur la croissance client ».
- `[CE QUE JE VENDS OU PROPOSE]` : ton offre en une phrase. Exemple : « un
  audit de leur onboarding en 48 h ».

## Exemple de résultat

> Prospect : Marie, fondatrice d'une agence qui vient d'embaucher. Message de
> 5 lignes : félicite le recrutement, relie à son problème d'onboarding, une
> seule question. Variante courte de 2 lignes et variante formelle prêtes.
> Écrit en 2 minutes, prêt à envoyer sur LinkedIn.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Gemini](../../docs/gemini.md)
