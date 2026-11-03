---
name: Relances de paiement
slug: relances-paiement
description: "Rédige des relances de factures fermes et courtoises, de la première relance à la mise en demeure."
domaine: compta
public: [solo-founder, grand-public]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, gemini]
---

# Relances de paiement

## Ce que fait cet agent

Tu lui donnes la facture en retard et où tu en es dans la relation client. Il
rédige la relance adaptée au stade, sans agresser la relation, avec une
variante plus courte et une plus ferme. Tu n'as plus qu'à coller, vérifier et
envoyer.

## Le prompt

```text
Tu es mon assistant de relances de factures.
Je te donne une facture en retard. Tu dois :
1. Écrire la relance adaptée au stade : [STADE, ex. « 1re relance,
   15 jours de retard »].
2. Ton de la relance : [TON, ex. « ferme mais courtois, sans
   culpabiliser, une seule demande claire »].
3. Toujours inclure : montant dû, numéro de facture, date d'échéance,
   un moyen de paiement, et une date limite de réponse.
4. Si le client n'a jamais répondu : ajouter une phrase courte qui
   suspend le service en douceur.
5. Terminer par 2 variantes : une plus courte (3 lignes), une plus
   ferme (en vue d'une mise en demeure).
Facture : [NUMÉRO, MONTANT, ÉCHÉANCE].
Client : [NOM, historique de la relation].
```

## Variables à personnaliser

- `[STADE]` : où tu en es dans le retard. Exemple : « 1re relance, 15 jours
  de retard ».
- `[TON]` : le ton de la relance. Exemple : « ferme mais courtois, sans
  culpabiliser, une seule demande claire ».
- `[NUMÉRO, MONTANT, ÉCHÉANCE]` : les infos de la facture. Exemple :
  « F-2026-118, 1 450 €, échéance le 12/10 ».
- `[NOM, historique de la relation]` : le client et votre passé. Exemple :
  « Studio Lumière, client fidèle depuis 2 ans, premier retard ».

## Exemple de résultat

> Relance 1 : trois lignes, rappelle la facture F-2026-118 de 1 450 € échue
> le 12/10, avec un lien de paiement et une réponse attendue sous 7 jours.
> Variante ferme : annonce une mise en demeure sous 8 jours si pas de retour.
> Rédigée en 2 minutes au lieu de 20.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Gemini](../../docs/gemini.md)
