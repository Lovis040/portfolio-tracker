# Portfolio Tracker

Ein Depot-Tracker als eigenständige Web-App mit Live-Kursdaten über eingebettete TradingView-Widgets.

## Funktionen

- Startkapital von 100.000 € mit editierbarem Bargeld-Bestand
- Positionen anlegen für Aktien, ETFs, Fonds, Krypto, Rohstoffe, Optionsscheine und Zertifikate
- Live TradingView-Chart mit Symbol-Auswahl und freier Suche
- Live-Vorschau-Chart direkt beim Anlegen einer neuen Position
- Zusatzfelder für Derivate (Basiswert, Typ, Strike, Hebel, Fälligkeit, WKN/ISIN) inkl. Fälligkeits-Badge
- Persistente Speicherung der Daten im Browser
- Verlaufs-Snapshot mit Sparkline-Chart

## Nutzung

Diese Datei einfach im Browser öffnen (`index.html`) oder über GitHub Pages hosten, um von überall darauf zuzugreifen.

### GitHub Pages aktivieren

1. Im Repo unter **Settings → Pages**
2. Branch `main`, Ordner `/ (root)` auswählen
3. Speichern — die App ist danach unter `https://<username>.github.io/portfolio-tracker/` erreichbar

## Hinweis zu Live-Kursen

Positionswerte werden manuell aktualisiert: Der Live-Kurs wird im eingebetteten TradingView-Widget angezeigt, da TradingView keine öffentliche API zum automatischen Auslesen von Kursen bereitstellt.
