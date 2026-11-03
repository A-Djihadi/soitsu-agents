# Soitsu Agents

Une bibliothèque d'agents IA **prêts à l'emploi**, utilisables chaque jour.
Un agent = un prompt testé, documenté, et installable sur le fournisseur de
ton choix (ChatGPT, Claude, Gemini, Perplexity, n8n, Make, …).

> **Nouveau chaque mardi** : trois agents ajoutés, en lien avec la série
> vidéo Soitsu.

---

## Pourquoi ce dépôt

Tu vois passer des prompts un peu partout. Tu les copies, tu les perds, tu ne
sais plus où ils sont. Ici, tout est **versionné, testé et documenté** : un
agent = un dossier, avec son prompt, ses variables à personnaliser et un
exemple de résultat.

## Utiliser un agent en 2 minutes

1. Ouvre le dossier [`agents/`](agents/README.md) et choisis un agent.
2. Ouvre son `AGENT.md` et copie le prompt.
3. Remplace les variables entre crochets `[...]` par tes infos.
4. Colle le prompt dans ton fournisseur préféré — voir les guides dans
   [`docs/`](docs/README.md).

## Les agents

| Agent | Domaine | Public |
| --- | --- | --- |
| [Gestionnaire de boîte mail](agents/inbox-manager/AGENT.md) | Productivité | Grand public |
| [Veille quotidienne](agents/veille-quotidienne/AGENT.md) | Veille | Solo founder |
| [Idée → plan d'action](agents/idee-en-plan/AGENT.md) | Organisation | Grand public |
| [Relances de paiement](agents/relances-paiement/AGENT.md) | Comptabilité | Solo founder |
| [Réponses clients](agents/reponses-clients/AGENT.md) | Support client | Grand public |
| [Déclinaison de contenu](agents/declinaison-contenu/AGENT.md) | Contenu | Grand public |

*Liste complète et à jour : [`agents/README.md`](agents/README.md).*

## Fournisseurs supportés

Chaque agent est fournisseur-agnostique. Les guides d'installation :

- [ChatGPT](docs/chatgpt.md) — GPT personnalisé
- [Claude](docs/claude.md) — Projet
- [Gemini](docs/gemini.md) — Gem
- [Perplexity](docs/perplexity.md) — Espace
- [n8n](docs/n8n.md) — nœud AI Agent
- [Make](docs/make.md) — module IA

## Contribuer

Tu veux ajouter un agent, corriger un prompt ou proposer un guide ? Lis
[`CONTRIBUTING.md`](CONTRIBUTING.md). C'est simple : copie le template, remplis
le frontmatter, ouvre une PR.

## Licence

[MIT](LICENSE). Utilise, adapte, partage — garde simplement l'attribution.

---

*Soitsu — des agents utiles, pas des gadgets.*
