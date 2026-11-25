# SUBINTERVALS – Versionsverlauf

Bei jeder Überarbeitung wird die Versionsnummer erhöht (Anzeige im Kopf der Seite und im Browser-Tab).

## v6.5 – 2026-11-25
- Analyse: Button „Einheit löschen“ für die gewählte Einheit (mit Rückfrage, löscht in Intervals.icu)

## v6.4 – 2026-11-25
- Verlängern: Kalorien und Load der Einheit können überschrieben werden (z. B. mit den Garmin-Gesamtkalorien), wenn die Werte in Intervals.icu nicht stimmen

## v6.3 – 2026-11-25
- Verlängern: Kalorien der Zusatzminuten standardmäßig nach Laufformel (Tempo, Gewicht) statt proportional zum Gerätewert; Umschalter und Gegenprobe mit beiden Werten, Warnhinweis bei großer Abweichung

## v6.2 – 2026-11-25
- Tools 3 und 4 zusammengeführt: „Einheit korrigieren & anpassen“ mit gemeinsamer Einheiten-Auswahl (A: verlängern/kürzen, B: Werte korrigieren)
- Verlängern/Kürzen legt jetzt eine neue Einheit mit den berechneten Werten (Distanz, Zeit, Puls, Kalorien) in Intervals.icu an; optional wird das Original gelöscht. Grund: Distanz und Zeit lassen sich beim aufgezeichneten Original nicht überschreiben
- Tools neu nummeriert (Export 4, Körperdaten 5, Wellness-Felder 6)

## v6.1 – 2026-11-25
- Neues Tool 4 „Einheit verlängern / kürzen“: aufgezeichnete Einheit wählen, Zusatzminuten (auch negativ) mit eigenem Tempo, Puls und Watt eintragen; Vorher/Nachher für Distanz, Zeit, Pace, Puls, Watt, Kalorien und Load
- Ergebnis kopieren; Kalorien und Load optional in Intervals.icu übernehmen (mit Rückfrage), optional Notiz an die Beschreibung
- Tools neu nummeriert (Export 5, Körperdaten 6, Wellness-Felder 7)

## v6.0 – 2026-11-22
- Plan: Workout-Profil neu als farbiges Mini-Diagramm mit Zeitskala (Minuten), Hilfslinien, Watt-/Pace-Beschriftung in den Blöcken und Farblegende; Darstellungsfehler (leere Pillen) behoben
- Diagramme: Balken mit Farbverlauf statt flacher Farbe

## v5.9 – 2026-11-22
- Kopfbereich neu geordnet: Titel mit Version links, runder Design-Knopf und Sync-Knopf rechts, Status als eigene Zeile darunter
- Datumsangabe über den Karten bricht nicht mehr mitten im Datum um

## v5.8 – 2026-11-22
- Umschalter hell/dunkel im Kopf (merkt sich die Wahl, ohne Wahl gilt die Systemeinstellung); Diagramme passen sich an

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
