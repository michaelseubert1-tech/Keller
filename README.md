# Keller-Schimmelcheck (PWA)

## Auf GitHub Pages veröffentlichen

1. Lege auf GitHub ein neues Repository an (z. B. `keller-schimmelcheck`).
2. Lade **alle Dateien und den Ordner `icons`** aus diesem Paket in das Stammverzeichnis des Repositorys hoch.
3. Öffne im Repository **Settings → Pages**.
4. Wähle bei **Build and deployment** die Option **Deploy from a branch**.
5. Wähle den Branch `main` und den Ordner `/ (root)`, dann **Save**.
6. Warte, bis GitHub Pages die Website veröffentlicht hat. Die Adresse steht anschließend im Pages-Bereich.

## Auf Android installieren

1. Öffne die veröffentlichte `https://...github.io/...`-Adresse in Chrome auf Android.
2. Sobald Chrome die Installation anbietet, erscheint in der App der Button **„App installieren“**.
3. Tippe darauf und bestätige die Installation.

Falls der Button nicht erscheint, nutze in Chrome das Menü **⋮ → App installieren** oder **Zum Startbildschirm hinzufügen**. Die Verfügbarkeit der Installationsabfrage hängt von Chrome und den Installationsbedingungen ab.

## Dateien

- `index.html` – App und Installationsbutton
- `manifest.webmanifest` – Name, Startadresse, Darstellung und Icons
- `sw.js` – Offline-Cache (Service Worker)
- `icons/` – App-Symbole 192×192 und 512×512

Die App funktioniert nur als installierbare PWA über HTTPS (z. B. GitHub Pages) oder lokal über `localhost`. Sie ist keine APK und wird nicht über den Play Store verteilt.
