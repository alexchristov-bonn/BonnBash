# Bonn Bash · Tang Soo Edition

Ein 2D-Arcade-Fighting-Game in JavaScript und HTML5 Canvas mit sechs Kämpfern, fünf Bonner Stages und eigenem FM-Soundtrack.

## Download und Spielen

Die vollständige spielbare Version einschließlich JavaScript-Quellcode, PNG-Sprites und WAV-Musik ist als **Bonn-Bash-Netlify.zip** unter [Releases](https://github.com/alexchristov-bonn/BonnBash/releases) verfügbar. ZIP entpacken: `index.html`, `characters.js`, `arcade.js`, `game.js` und `assets/` liegen direkt im entpackten Ordner. Kein Build-Schritt und keine Installation erforderlich. Diesen Ordner oder die ZIP bei Netlify Drop hochladen.

Netlify-Projekt: https://dulcet-gumdrop-39d6b8.netlify.app/

Das Repository enthält die Anleitung; die komplette Spielversion liegt im Release-Archiv. Ein automatisches Git-Deployment aus dem Repository ist nicht eingerichtet.

## Steuerung

- Bewegung: A/D; W springen; S ducken.
- Punch: J/K/L. Kick: U/I/O.
- Block: vom Gegner weg halten; Unten + Zurück für tiefen Block.
- Specials: Viertelkreis zum Gegner + Punch/Kick. Nach rechts etwa S → S+D → D+J/U. Normale Specials benötigen keinen Meter.
- Super: zwei Viertelkreise zum Gegner + schwerer Punch bei vollem Meter.
- Meisterin Chen: vier schnelle Punch-Tastendrücke für TAUSEND FÄCHER.
- P: Pause. Smartphone: Touch-D-Pad. Gamepad wird unterstützt; ein zweites Gamepad aktiviert Spieler 2.

## Stand 28.10.2026

Wärmere Stage-Musik, kraftvolles Moll-Intro und KO-Thema, Punch-Sounds im Auftakt, tolerante Special-Eingaben, animierte Pixel-Geschosse, gerenderte Arcade-Schrift und AC-Teacher-Portraits mit runder Brille.
