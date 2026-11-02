---
name: Veille quotidienne
slug: veille-quotidienne
description: "Un briefing chaque matin sur ton secteur : actus, signaux faibles et action du jour."
domaine: veille
public: [solo-founder, grand-public]
difficulte: debutant
duree: 5 min
fournisseurs: [chatgpt, claude, perplexity]
---

# Veille quotidienne

## Ce que fait cet agent

Chaque matin, il te sort un briefing en dix lignes : trois actus majeures,
pourquoi elles te concernent, un signal faible et une action à faire en
quinze minutes.

## Le prompt

```text
Tu es mon agent de veille quotidien.
Chaque matin, fais un briefing sur : [TON SECTEUR].
Consignes :
1. 3 actualités majeures des dernières 24 h (sources primaires),
   chacune avec : 1 ligne de contexte + 1 ligne « pourquoi ça me
   concerne » + 1 lien.
2. 1 « signal faible » : une tendance peu médiatisée qui pourrait
   compter dans 6 mois.
3. 1 action concrète à faire aujourd'hui en 15 minutes.
Format : 10 lignes max, sans jargon.
Mon profil : [ton marché, ton offre, tes 3 concurrents principaux].
```

## Variables à personnaliser

- `[TON SECTEUR]` : le marché ou le sujet à surveiller. Exemple : « la
  cybersécurité cloud ».
- `[ton marché, ton offre, tes 3 concurrents principaux]` : remplace par ta
  situation, pour que le briefing soit pertinent pour toi.

## Exemple de résultat

> Mardi : un concurrent baisse ses prix. Action du jour : mettre à jour ta
> page tarif. Signal faible : l'automatisation des devis se démocratise.

## L'installer

- [ChatGPT](../../docs/chatgpt.md)
- [Claude](../../docs/claude.md)
- [Perplexity](../../docs/perplexity.md)
