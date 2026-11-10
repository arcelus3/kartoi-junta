# Kartoi — dashboard de junta de dirección

Página estática publicada en https://arcelus3.github.io/kartoi-junta/ (GitHub Pages; dominio objetivo junta.kartoi.mx) que lee los datos del backend Apps Script "Kartoi Dashboards v2" y los pinta.
El URL del backend va cifrado en `index.html` (`ENDPOINT_ENC`); se abre con la clave de acceso del equipo.

- Fuente del código: `~/Desktop/kartoi sales engine/dashboard/` (Claude Code edita y publica con `git push`).
- Backend (Code.gs) en `../webapp-junta/`, se publica con `clasp push && clasp deploy`.
