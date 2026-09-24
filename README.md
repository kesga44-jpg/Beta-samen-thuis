# Samen Thuis

Opgeschoonde repository voor de Samen Thuis PWA.

## Structuur
- `index.html` — app-shell
- `styles.css` — alle styling
- `js/app.js` — interface en interacties
- `js/store.js` — lokale data/opslag
- `js/utils.js` — hulpfuncties
- `js/prices.js` — prijslogica
- `js/sources.js` — openbare databronnen
- `js/sync.js` — Supabase-sync
- `js/importer.js` — imports
- `sw.js` + `manifest.webmanifest` + `icon.svg` — PWA
- `supabase/` — database/schema en Edge Functions

## Nieuwe GitHub repository
Upload de inhoud van deze map rechtstreeks naar de root van de nieuwe repository.
Voor GitHub Pages: Settings → Pages → Deploy from branch → `main` → `/ (root)`.

Geheime API-sleutels horen niet in GitHub. Zet `NED_API_KEY` en `TANKERKOENIG_API_KEY`
alleen als Supabase Edge Function secrets.

## Opmerking
Oude versie-, fix- en installatiedocumenten zijn bewust verwijderd. Er is maar één actuele
frontend-codepad: de bestanden in `js/`.
