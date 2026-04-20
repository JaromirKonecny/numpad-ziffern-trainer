# Num-Pad Ziffern-Trainer

Ein schlichter Browser-Trainer zum Üben des Nummernblocks auf der Tastatur. Zufällig ausgewählte Ziffern werden groß angezeigt und optional auf Deutsch ausgesprochen.

## Features

- Zufällige Ziffern (0–9), einzeln per Chip-Klick abwählbar
- Einstellbares Intervall (0,5 – 5 Sekunden)
- Einstellbares Sprechtempo (0,5× – 1,3×)
- Audio-Ausgabe über die Web Speech API (nutzt System-TTS, keine Cloud)
- Leertaste = Start/Stopp
- Automatisches Dark-/Light-Mode über `prefers-color-scheme`
- Keine Abhängigkeiten, kein Build, keine Installation

## Nutzung

**Lokal:** `index.html` doppelklicken — öffnet im Standard-Browser.

**Online:** Sobald GitHub Pages für dieses Repo aktiviert ist, läuft der Trainer unter
`https://<dein-github-name>.github.io/<repo-name>/`

## Technisches

Single-File-HTML. Vanilla JavaScript, keine Frameworks, keine externen Ressourcen. Die Sprachausgabe nutzt die [Web Speech API](https://developer.mozilla.org/de/docs/Web/API/Web_Speech_API) des Browsers — die deutsche Stimme muss vom Betriebssystem bereitgestellt werden (auf Windows/macOS/Linux-Desktops fast immer vorhanden; auf Mobilgeräten systemabhängig).

## Hintergrund

Entstanden als Übungstool beim Erlernen des Nummernblocks. Prinzip: Ohr und Finger gleichzeitig trainieren, ohne die Augen von der Tastatur zu lösen.

## Lizenz

MIT

---

*Erstellt von Jaromir Konecny & Claude Opus 4.7 (Anthropic), April 2026.*
