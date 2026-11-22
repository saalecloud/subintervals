# SUBINTERVALS – Versionsverlauf

Bei jeder Überarbeitung wird die Versionsnummer erhöht (Anzeige im Kopf der Seite und im Browser-Tab).

## v5.7 – 2026-11-22
- Navigation bleibt oben im normalen Seitenfluss, kein schwebendes Menü mehr (auch am Handy)

## v5.6 – 2026-11-22
- Design überarbeitet: ruhigerer Hintergrund, abgerundete Karten, Pill-Navigation (am Handy unten fixiert)
- Kopf mit Markenname, Versions-Chip und Status-Pille mit Farbpunkt
- Eingabefelder mit Fokus-Rahmen, einheitliche Knöpfe
- Willkommenskarte mit Login-Knopf, solange nicht angemeldet
- Tools durchgehend nummeriert (1–6) in Lesereihenfolge: Login, Workout planen, Korrigieren, Export, Körperdaten, Wellness-Felder; runde Nummern-Badges

## v5.5 – 2026-11-22
- Automatische Synchronisierung nach dem Laden, sobald ein Login vorhanden ist (auch von Firefox eingesetzt)
- Verständliche Fehlermeldungen (Login ungültig, ID nicht gefunden, offline); bei Login-Fehler springt die Seite zum Login
- Als App installierbar (PWA: Manifest, Icons, Service Worker)
- Offline-Cache: zuletzt geladene Aktivitäten, Events und Wellness bleiben sichtbar
- Abmelden-Knopf löscht Key, ID und Cache aus dem Browser
- Hinweis bei neuer Version mit „Jetzt neu laden“ (version.json)
- Dashboard: Block „Heute geplant“ mit dem geplanten Workout
- Einstellungen (Körperdaten, Wellness-Zuordnung) exportieren und importieren

## v5.4 – 2026-11-22
- Web-Version ohne eingebaute Zugangsdaten (Key-frei)
- Login (Athlete-ID + API-Key) ganz oben auf der Tools-Seite
- API-Key per Schalter im Klartext anzeigbar
- Login als echtes Formular: Firefox kann den Login speichern
- Autofill wird beim Laden nicht mehr überschrieben

## v5.3
- Calibri-Schrift, Redesign, Desktop-Layout
