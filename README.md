# feminin discovery

Ein Prototyp für feminin.at: Patientinnen wählen ihre Lebensphase und sehen sofort, welche Angebote im Gesundheitszentrum für sie passen.

Alles steckt in einer einzigen Datei, `index.html`. Kein Build, keine Installation.

## Ansehen

- Live: `https://DEIN-USERNAME.github.io/feminin-discovery/`
- Lokal: `index.html` im Browser öffnen

## Selbst weiterbauen

Vibe Coding heißt: Du beschreibst, was du willst, die KI schreibt den Code, du schaust dir das Ergebnis an und sagst, was anders sein soll.

1. Öffne Claude und lade `index.html` hoch.
2. Sag, was du ändern willst. Zum Beispiel:
   - „Ergänze bei jedem Angebot einen Link auf die passende Seite von feminin.at.“
   - „Füge eine Lebensphase ‚Ab 60‘ hinzu.“
   - „Verwende die Farben unseres Logos.“
   - „Zeige bei jedem Angebot, wer im Team dafür zuständig ist.“
3. Lade die neue Datei hier auf GitHub hoch (Add file, Upload files, Commit changes).
4. Nach etwa einer Minute ist die neue Version live.

## Wo was steht

Die Inhalte stehen ganz unten in `index.html` in vier Listen:

- `PHASES`: die Punkte auf dem Lebensbogen
- `INTENTS`: die Auswahl „Was führt Sie zu uns?“
- `SPECS`: die Fachbereiche und ihre Farben
- `SERVICES`: die Angebote. `p` sind die passenden Lebensphasen, `i` die passenden Anliegen, `w` wer betreut.

Angebote und Team stammen von feminin.at (Stand Oktober 2026). Die Zuordnung zu Lebensphasen ist ein Vorschlag, den du prüfen solltest.
