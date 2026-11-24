---
name: Analyse d'avis clients
slug: analyse-avis-clients
description: "Lit tes avis, messages ou réponses de sondage et en sort les points qui reviennent, les irritants et trois actions à lancer."
domaine: analyse
public: [solo-founder, grand-public]
difficulte: debutant
duree: 10 min
fournisseurs: [chatgpt, claude, gemini]
---

# Analyse d'avis clients

## Ce que fait cet agent

Tu as des dizaines d'avis, d'emails ou de réponses de sondage, et tu n'as pas
le temps de tout relire. Tu colles le tout. L'agent regroupe ce qui revient,
sépare ce qui plaît de ce qui gêne, cite des phrases réelles comme preuves et
propose trois actions classées par effort. Pratique pour un solo founder qui
décide seul de la prochaine chose à améliorer.

## Le prompt

```text
Tu es mon analyste de retours clients.
Je te colle des avis, des messages ou des réponses de sondage. Tu dois :
1. Regrouper les retours en 4 à 6 thèmes et indiquer, pour chaque thème,
   combien de retours en parlent (sur [NOMBRE] au total).
2. Séparer ce qui plaît (points forts) de ce qui gêne (irritants).
3. Pour chaque thème, citer 2 phrases exactes tirées des retours comme
   preuves. N'invente aucune citation ni aucun chiffre.
4. Repérer ce que les clients demandent sans le dire clairement.
5. Proposer 3 actions concrètes, classées de la plus rapide à la plus
   longue, avec l'effet attendu de chacune.
6. Signaler les limites de l'analyse : échantillon trop petit, retours
   trop anciens, avis extrêmes seulement.
Ce que je vends : [MON PRODUIT OU SERVICE].
Ce que je cherche à comprendre : [MA QUESTION, ex. « pourquoi les gens
résilient après un mois »].
Ton : [TON, ex. « factuel, sans enjoliver »].
Retours clients : [COLLE LES RETOURS ICI].
```

## Variables à personnaliser

- `[NOMBRE]` : le nombre de retours collés. Exemple : « 40 ».
- `[MON PRODUIT OU SERVICE]` : ce que tu proposes, en une phrase. Exemple :
  « une application de suivi d'heures pour freelances ».
- `[MA QUESTION]` : ce que tu veux décider grâce à l'analyse. Exemple :
  « pourquoi les gens résilient après un mois ».
- `[TON]` : le style du compte rendu. Exemple : « factuel, sans enjoliver ».
- `[COLLE LES RETOURS ICI]` : les avis, emails ou réponses, sans nom ni email
  de client.

## Exemple de résultat

> 40 avis sur une application de suivi d'heures. Résultat : 5 thèmes, dont
> « l'export des factures est compliqué » (14 avis sur 40) et « le rappel
> quotidien est apprécié » (9 avis), 2 citations exactes par thème, une
> demande implicite (connexion avec le logiciel de facturation), et 3 actions :
> réécrire le texte de l'export (1 heure), ajouter un modèle de facture par
> défaut (1 jour), étudier une connexion avec la facturation (2 semaines).
> Limite signalée : 12 avis datent de plus d'un an.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
