VANSTOCK – Firmenwagen-Lagerverwaltung

ENTHALTEN
- index.html: App-Oberfläche und Funktionen
- manifest.webmanifest und sw.js: Grundlage für Installation als PWA und Offline-Cache

WICHTIG
Die App ist als lokale Einzelbenutzer-Version angelegt. Artikel, Bestände und Buchungen werden im Browser auf dem jeweiligen Gerät gespeichert. Es gibt keine Cloud-Synchronisierung und keinen Benutzer-Login.

START
1. index.html im Browser öffnen, um die App auszuprobieren.
2. Für die Installation als echte PWA auf Android müssen alle drei Dateien über eine HTTPS-Adresse bereitgestellt werden.
3. Die HTTPS-Seite in Chrome öffnen, dann Menü > App installieren bzw. Zum Startbildschirm hinzufügen.
4. Beim ersten Start regelmäßig unter Einstellungen > Daten sichern eine JSON-Sicherung exportieren.

BARCODE
- Kamera-Scan funktioniert nur, wenn Browser und Gerät BarcodeDetector unterstützen und die Seite über HTTPS läuft.
- Alternativ funktioniert ein Bluetooth-/USB-Scanner, der den Code wie Tastatureingaben übermittelt. Code in das Barcode-Feld eingeben.
- Wenn du die HTML-Datei direkt öffnest (file://), können Kamera- und PWA-Funktionen je nach Android-Browser eingeschränkt sein.

DATEN
- CSV-Export für Bestandslisten.
- JSON-Export und -Import für vollständige Sicherung/Wiederherstellung.
- Keine automatische Sicherung. Exportiere regelmäßig eine Kopie.
