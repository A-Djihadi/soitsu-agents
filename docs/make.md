# Installer un agent sur Make

Méthode : module IA (OpenAI, Anthropic/Claude ou Gemini).

## Étapes

1. Ouvre Make, crée un nouveau scénario.
2. Ajoute un déclencheur (ex. **Webhook** ou **Planification**).
3. Ajoute un module IA : **OpenAI** → *Create a completion*, ou
   **Anthropic** → *Create a message*, ou **Gemini**.
4. Connecte ton compte (clé API via une *connection* Make).
5. Dans **System prompt** (ou le champ *system*), colle le prompt de l'agent.
6. Dans **User** (ou le champ *user/prompt*), mets ta demande du moment.
7. Remplace les variables `[...]` par tes infos, sauvegarde et active.

## Aller plus loin

Make excelle pour l'automatisation sans code : combine le module IA avec des
modules Google Sheets, Gmail, Notion ou Slack pour créer un vrai agent qui
enchaîne les tâches tout seul.
