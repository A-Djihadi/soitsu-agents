# Guides d'installation

Un agent Soitsu est un prompt, pas un produit lié à un fournisseur. Tu peux
l'installer sur le service que tu utilises déjà. Choisis ton fournisseur :

| Fournisseur | Méthode | Coût |
| --- | --- | --- |
| [ChatGPT](chatgpt.md) | GPT personnalisé | Gratuit / payant |
| [Claude](claude.md) | Projet | Payant |
| [Gemini](gemini.md) | Gem | Gratuit / payant |
| [Perplexity](perplexity.md) | Espace | Payant (Pro) |
| [n8n](n8n.md) | Nœud AI Agent | Gratuit (auto-hébergé) |
| [Make](make.md) | Module IA | Freemium |

## Principe commun

Quel que soit le fournisseur, le principe est le même :

1. Tu crées un « agent », un « projet » ou un « espace ».
2. Tu colles le prompt de l'agent dans le champ « instructions » ou
   « system prompt ».
3. Tu remplaces les variables `[...]` par tes infos.
4. Tu lui parles, ou tu l'automatises (n8n, Make).

Les guides détaillent chaque étape, fournisseur par fournisseur.
