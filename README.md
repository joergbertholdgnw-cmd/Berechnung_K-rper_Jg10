# Berechnung_Körper_Jg10

Interaktive Lernseite zur Unterrichtsreihe „Kreis- und Körperberechnung“ in Jahrgang 10 (Gymnasium Niedersachsen, G9).

Die Seite zeigt den Lernweg als Karte mit „Du bist hier“-Markierung. Jede Station hat:
Ziele (Ich-kann-Sätze) → Animation → Herleitung Schritt für Schritt → Lernvideo → Kernfragen zur Herleitung → Lernprotokoll (Aufgabe, Umkehraufgabe, Vertiefung, Rückblick).
Der Fortschritt wird nur im Browser der Schülerin oder des Schülers gespeichert (localStorage), ohne Anmeldung.

## Stand

| Station | Thema | Stand |
|---|---|---|
| 0 | Startcheck | fertig |
| 1 | Kreisumfang und π (mit Messreihe und Lernprotokoll) | fertig |
| 2 | Flächeninhalt des Kreises (mit Lernprotokoll) | fertig |
| 3 | Kreisausschnitt und Kreisbogen | fertig |
| 4 | Zylinder: Netz und Oberfläche | fertig |
| 5 | Zylinder: Volumen | fertig |
| 6–10 | Pyramide/Kegel, Kugel, zusammengesetzte Körper | Ziele hinterlegt, Inhalte folgen |

Der vollständige Lernweg steht in [docs/lernweg.md](docs/lernweg.md).

## Dateien

- `src/lernseite.html` – Quelltext der Seite (HTML, CSS, JavaScript in einer Datei)
- `index.html` – daraus gebaute Seite für GitHub Pages; nach Änderungen `./build.sh` ausführen
- `docs/lernweg.md` – Stationen, Lernziele und Videovorschläge

## Veröffentlichen

In den Repository-Einstellungen unter *Pages* den Branch `main` und den Ordner `/ (root)` wählen. Die Seite ist dann unter `https://<benutzername>.github.io/Berechnung_K-rper_Jg10/` erreichbar.
