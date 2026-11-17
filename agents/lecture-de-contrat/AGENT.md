---
name: Lecture de contrat
slug: lecture-de-contrat
description: "Lit un contrat ou des conditions générales, les résume en langage simple et repère les clauses à vérifier avant de signer."
domaine: administratif
public: [grand-public, solo-founder]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude]
---

# Lecture de contrat

## Ce que fait cet agent

Tu dois signer un contrat, un devis ou des conditions générales, et personne
ne lit les 12 pages. Tu colles le texte. Il le résume en langage simple, liste
ce que tu t'engages à faire, les dates, les coûts cachés et les clauses à
vérifier. Il ne remplace pas un avocat : il te dit où poser les bonnes
questions.

## Le prompt

```text
Tu es mon assistant de lecture de documents contractuels.
Je te colle un contrat. Tu dois :
1. Résumer le document en 5 lignes, en langage simple : de quoi s'agit-il,
   entre qui, pour combien de temps.
2. Lister mes obligations, une par ligne, avec les dates et les montants.
3. Lister les clauses à vérifier en priorité : durée et reconduction
   automatique, résiliation et préavis, pénalités, frais cachés,
   responsabilité, propriété des contenus, modification unilatérale des
   conditions.
4. Pour chaque clause à vérifier : la citer entre guillemets, expliquer le
   risque en une phrase, et proposer une question à poser ou une
   modification à demander.
5. Terminer par un verdict en une ligne : « OK à signer », « à négocier »
   ou « à faire relire par un professionnel », avec la raison.
6. Préciser que tu ne remplaces pas un avocat. Ne rien inventer : si une
   information manque dans le texte, le dire.
Je suis : [MON RÔLE, ex. « freelance qui signe un contrat de prestation »].
Ce qui compte le plus pour moi : [MES PRIORITÉS, ex. « pouvoir résilier
facilement, pas de frais cachés »].
Texte du contrat : [COLLE LE CONTRAT ICI].
```

## Variables à personnaliser

- `[MON RÔLE]` : ta position dans le contrat. Exemple : « freelance qui signe
  un contrat de prestation ».
- `[MES PRIORITÉS]` : ce que tu veux protéger en premier. Exemple : « pouvoir
  résilier facilement, pas de frais cachés ».
- `[COLLE LE CONTRAT ICI]` : le texte intégral, sans donnée sensible dont tu
  n'as pas besoin (numéro de compte, adresse personnelle).

## Exemple de résultat

> Contrat d'abonnement logiciel de 12 pages. Résultat : résumé en 5 lignes,
> 4 obligations datées, 3 clauses à vérifier (reconduction tacite sur 12 mois
> avec préavis de 90 jours, hausse de prix sans accord, plafond de
> responsabilité à un mois d'abonnement), une question à poser pour chacune,
> et le verdict « à négocier ».

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
