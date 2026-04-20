# Command Center – Vermittlung Lippe

Dein persönliches Dashboard für die Vermittlungsarbeit. Läuft komplett im Browser, alle Daten werden lokal gespeichert.

## Was ist drin

- **Dashboard** mit Live-Kennzahlen (Leads, Partner, Aufgaben, Einnahmen)
- **Leads & Aufträge** – alle Kundenanfragen mit Status-Tracking und automatischer Provisionsberechnung
- **Partner** – 49 vorbereitete Kontakte aus Lemgo/Detmold laden mit einem Klick, plus eigene hinzufügen
- **Aufgaben** – 32 Starter-To-Dos für den kompletten Aufbau
- **Journal** – dein Arbeitstagebuch mit Stimmungs-Tagging
- **Notizen** – schnelle bunte Zettel
- **Einnahmen** – Provisionen verbuchen, Monats-Übersicht mit Balkendiagramm
- **Dokumente** – alle PDFs aus dem Starter-Paket direkt ansehen + eigene erstellen
- **Quick Links** – alle wichtigen Plattformen, Behörden, Tools auf einen Klick
- **Einstellungen** – Stammdaten, Provisionsprozente, Backup/Restore

## Setup auf GitHub Pages

### Einmalig einrichten (ca. 10 Minuten)

1. GitHub-Account erstellen auf https://github.com (kostenlos)
2. Neues Repository anlegen: Klick auf "+" oben rechts → "New repository"
3. Namen vergeben, z.B. `command-center`, auf "Public" lassen, "Create repository"
4. Im neuen Repo: "uploading an existing file" klicken
5. Diese Dateien alle hochladen:
   - `index.html` (das Dashboard)
   - Alle 10 PDFs (00_START_HIER bis 10_Mein_Merkzettel)
6. Unten "Commit changes" klicken
7. Gehe zu "Settings" → "Pages" im linken Menü
8. Unter "Source" wählen: "Deploy from a branch" → Branch: "main" → "/ (root)" → Save
9. Nach 1-2 Minuten ist deine Seite erreichbar unter:
   `https://DEIN-GITHUB-NAME.github.io/command-center/`

### Nutzung

Öffne die URL auf Handy oder PC. Die Seite funktioniert auch offline, nach dem ersten Laden.

**Wichtig:** Die Daten werden im Browser gespeichert – jedes Gerät hat seine eigenen Daten. 
Für die Übertragung zwischen Geräten: Backup exportieren (oben rechts ⬇), auf anderem Gerät wieder importieren (⬆).

## Daten-Sicherheit

- Alle Daten bleiben ausschließlich in deinem Browser
- GitHub sieht nur den Code der Seite, nicht deine Daten
- Niemand außer dir hat Zugriff
- Trotzdem: regelmäßig exportieren (wöchentlich) für Backup

## Tastatur-Shortcuts

- `Strg+N` – Schnell hinzufügen
- `Strg+S` – Backup exportieren
- `Esc` – Modal schließen

## Anpassungen

Alle Inhalte können direkt in der index.html bearbeitet werden, wenn du Programmier-Grundkenntnisse hast.
Ansonsten funktioniert alles über die Einstellungen-Seite in der App selbst.

## Support

Diese App ist eigenständig und wird nicht zentral gewartet. Bei Problemen:
- Browser-Cache leeren
- Im privaten/Inkognito-Modus testen
- Backup-Datei prüfen (muss gültiges JSON sein)
