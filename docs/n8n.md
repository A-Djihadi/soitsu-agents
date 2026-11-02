# Installer un agent sur n8n

Méthode : nœud AI Agent (auto-hébergé ou n8n Cloud).

## Étapes

1. Ouvre n8n, crée un nouveau workflow.
2. Ajoute un déclencheur (ex. **Chat Trigger** pour discuter, ou **Schedule
   Trigger** pour un agent qui tourne chaque matin).
3. Ajoute un nœud **AI Agent**, connecte-le au déclencheur.
4. Dans le nœud AI Agent, choisis un **modèle** (OpenAI, Claude, Gemini…) et
   renseigne ta clé API (stockée dans un *credential* n8n, jamais en dur).
5. Dans **System Message**, colle le prompt de l'agent.
6. Remplace les variables `[...]` par tes infos.
7. Sauvegarde et exécute.

## Aller plus loin

- **Veille quotidienne** : déclencheur *Schedule* (tous les matins) + le nœud
  AI Agent + un nœud pour recevoir le briefing (email, Slack, Notion).
- **Gestionnaire de boîte mail** : connecte un nœud de réception d'emails
  (IMAP/Gmail) pour traiter les mails automatiquement.
