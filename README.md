# AI Bytes Adventskalender

24 Türchen voller AI-Wissen. Reine statische Seite (HTML/CSS/JS), keine Abhängigkeiten.

## Auf GitHub Pages veröffentlichen
1. Auf GitHub ein neues Repository anlegen (z. B. `adventskalender`).
2. Alle Dateien aus diesem Ordner hochladen (Add file → Upload files) und committen.
3. Repository → **Settings → Pages** → Source: *Deploy from a branch*, Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. 1–2 Minuten ist die Seite erreichbar unter `https://<dein-name>.github.io/<repo-name>/`.

## Anpassen
- `config.js`: Name deiner Freundin, dein Name, Schlussgruß, Motto.
- `content.js`: Texte, Prompts und Tipps der 24 Türchen.

## Testmodus (für dich)
- `…/index.html?preview=all` öffnet alle Türchen zum Durchklicken.
- `…/index.html?today=2026-12-10` simuliert ein bestimmtes Datum.
Im Testmodus wird der Fortschritt getrennt gespeichert, deine Freundin startet also frisch.

## Testmodus-Button
Im Seitenfuß gibt es den Button „🔓 Alle Türchen öffnen (Test)". Er verlangt die PIN aus `config.js` (`adminPin`, Standard `1224`; leer lassen = keine PIN) und öffnet dann alle Türchen. Zum Beenden: „🔒 Testmodus beenden".
Wichtig: Die PIN ist nur eine Hürde gegen versehentliches Drücken, kein echter Schutz – im Quelltext ist sie sichtbar.

## Hinweise
- Die Sperre richtet sich nach der Uhr des Geräts (Zeitzone Europe/Berlin). Wer die Geräteuhr umstellt, kann schummeln – für einen Adventskalender ist das gewollt unaufwendig.
- Fortschritt ("geöffnet", "Byte gesammelt") wird nur im Browser der jeweiligen Person gespeichert.
