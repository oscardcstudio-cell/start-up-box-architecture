# CLAUDE.md — start-up-box-architecture

> Hiérarchie : hérite de C:\dev\claude\CLAUDE.md et C:\dev\claude\oscardcstudio\CLAUDE.md

Page statique unique (`index.html`, HTML/CSS/JS inline, aucun build). Lancer : `npm install && npm start`.

- `npm start` échoue sous cmd.exe (Windows) à cause de `${PORT:-3000}` : utiliser Git Bash ou `npx serve -s -l 3800 .` (`.claude/launch.json`).
- `serve` est la seule dépendance et elle est utilisée (appelée par le script `start`, Railway lance `npm start`) : ne pas la retirer.
- Le contenu décrit le dépôt `start-up-box` ; si ses fichiers ou son installation changent, mettre `index.html` à jour.
