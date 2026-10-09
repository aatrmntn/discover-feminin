# feminin discovery

Ein Wegweiser für neue Patientinnen von feminin.at: Sie beschreiben in eigenen Worten, was sie beschäftigt, oder beantworten drei kurze Fragen (Lebensphase, Anliegen, Abrechnung). Am Ende steht eine klare Empfehlung: welches Angebot, wer dafür da ist, wie abgerechnet wird und wie man einen Termin bekommt.

Keine zweite Homepage, sondern ein Werkzeug. Alles steckt in `index.html`. Kein Build, keine Installation.

## Ansehen

- Live: `https://DEIN-USERNAME.github.io/feminin-discovery/`
- Lokal: `index.html` im Browser öffnen

## Selbst weiterbauen

Vibe Coding heißt: Du beschreibst, was du willst, die KI schreibt den Code, du schaust dir das Ergebnis an und sagst, was anders sein soll.

1. Öffne Claude und lade `index.html`, `DESIGN.md` und `PRODUCT.md` hoch.
2. Sag, was du ändern willst. Zum Beispiel:
   - „Patientinnen suchen oft nach ‚Pilzinfektion‘. Ordne das der Vorsorge zu.“
   - „Füge das Anliegen ‚Endometriose‘ als eigenen Punkt hinzu.“
   - „Verlinke beim Ergebnis die passende Seite auf feminin.at.“
   - „Zeige bei der Empfehlung ein Foto der zuständigen Person.“
3. Lade die neue Datei hier auf GitHub hoch (Add file, Upload files, Commit changes).
4. Nach etwa einer Minute ist die neue Version live.

## Wo was steht

Im Skript in `index.html`:

- `SERVICES`: die Angebote mit Beschreibung, Fachbereich und wer betreut
- `PHASES`: die Lebensphasen in Schritt 1
- `CONCERNS`: die Anliegen. `l` ist der Text, `p` die Lebensphasen, `s` die passenden Angebote (das erste ist die Hauptempfehlung), `k` die Wörter, die Patientinnen in die Suche tippen
- `URGENT`: Suchbegriffe, bei denen der Hinweis auf 144 oder 142 erscheint

Angebote und Team stammen von feminin.at (Stand Oktober 2026). Anliegen, Suchwörter und Zuordnungen sind ein Vorschlag, den du fachlich prüfen solltest.
