# Eldoradio Event Jukebox – GitHub Pages Demo

Statische, offline-fähige Präsentationsdemo der Event-Jukebox-Idee.

## Enthalten
- Kampagneneditor
- Tastenmatrix A1–K10
- Song-, Gewinn-, Nieten- und Zufallsbelegung
- Lokale Audio-Uploads via IndexedDB
- Gewinnwahrscheinlichkeit und Limits
- Interaktiver Jukebox-Demo-Spielmodus
- Simulierte Winner-/Jackpot-Lightshow als Vorbereitung für DMX
- Live-Statistik
- JSON Export/Import
- LocalStorage-Persistenz
- Service Worker für Offline-Nutzung nach dem ersten Laden

## GitHub Pages
1. Neues Repository erstellen.
2. Alle Dateien aus diesem Ordner in das Repository hochladen.
3. In GitHub: **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch `main`, Ordner `/root` auswählen.
6. Danach die angezeigte GitHub-Pages-Adresse öffnen.

## Wichtiger Hinweis zur Demo
Es gibt noch keine echte Jukebox-, GPIO- oder DMX-Hardwareanbindung. Diese Schnittstellen werden ergänzt, sobald das konkrete Jukebox-Modell und die Tastaturmatrix bekannt sind.

Die hochgeladenen Audiodateien bleiben nur im Browser des jeweiligen Geräts gespeichert. Der JSON-Export exportiert die Konfiguration, nicht die Binär-Audiodateien. Für die spätere Raspberry-Pi-Version wird daraus ein echtes USB-Kampagnenpaket mit Audio, DMX-Shows und Konfiguration.
