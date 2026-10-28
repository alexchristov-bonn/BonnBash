# Bonn Bash · Tang Soo Edition

[Jetzt spielen](https://bonnbash.netlify.app/) · [ZIP-Release](https://github.com/alexchristov-bonn/BonnBash/releases/tag/v0.1.0)

2D-Arcade-Fighting-Game mit sechs Kämpfern, fünf Bonner Stages und eigenem FM-Soundtrack.

## Entwicklung und Veröffentlichung

Die spielbare Website liegt in `dist/`: `index.html`, `characters.js`, `arcade.js`, `game.js` und `assets/`. Kein Build-Schritt, keine Installation und keine externen Bibliotheken erforderlich. Die Netlify-Konfiguration im Repository veröffentlicht `dist/`.

Produktionsbranch: `main`. Nach Einrichtung der GitHub-Verbindung veröffentlicht Netlify neue Commits auf `main` automatisch. Lokale Änderungen müssen dafür zuerst committed und gepusht werden; reines Speichern löst kein Deployment aus.

Die ZIP unter Releases bleibt ein separat versionierter Download und wird nicht bei jedem Commit neu erstellt.

## Steuerung

- Bewegung: A/D, W springen, S ducken.
- Punch: J/K/L. Kick: U/I/O.
- Block: vom Gegner weg halten; Unten + Zurück für tiefen Block.
- Specials: Viertelkreis zum Gegner + Punch/Kick. Nach rechts S → S+D → D+J/U.
- Super: zwei Viertelkreise zum Gegner + schwerer Punch, voller Super-Meter.
- Chen: vier schnelle Punch-Tastendrücke für TAUSEND FÄCHER.
- P: Pause. Touch-D-Pad und Gamepad werden unterstützt; zweites Gamepad aktiviert Spieler 2.
