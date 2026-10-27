# start-up-box-architecture

Page statique d'onboarding qui explique comment l'assistant IA de start-up-box connaît la boîte (étapes d'installation, exemples de demandes, architecture des fichiers). Déployée sur Railway.

## Lancer en local

```
npm install
npm start    # serve -s sur $PORT (3000 par défaut)
```

`npm start` utilise la syntaxe shell `${PORT:-3000}` : sous Windows, passer par Git Bash ou `npx serve -s -l 3000 .`.
