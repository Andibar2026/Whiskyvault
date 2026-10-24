WhiskyVault 2.0 – Update für iPhone/GitHub Pages

WICHTIG: ZUERST in der bestehenden App Einstellungen > Backup exportieren.
Die App nutzt weiterhin IndexedDB Datenbank whiskyvault, Version 1, Store bottles. Bestehende Einträge bleiben bei einem normalen Update unter derselben URL erhalten. Keine Website-Daten löschen und keine neue URL verwenden.

Alle Dateien aus diesem Ordner in das HAUPTVERZEICHNIS des bestehenden GitHub-Repositorys hochladen und vorhandene Dateien ersetzen. Nicht den Ordner selbst hochladen.

Neu: Barcode-Feld, optional BarcodeDetector-Kamera (auf iPhone eventuell nicht verfügbar), Open Food Facts EAN-Abfrage, kostenpflichtige OpenAI-Websuche, manuell bestätigte Produktdaten, Tasting Notes, Brennerei-Geschichte, Richtpreise mit Datum und Quelle, Sammlungswert.

Hinweise:
- Die App speichert Daten lokal im selben Browser-/PWA-Kontext. Bitte regelmäßig JSON-Backups erstellen.
- API-Schlüssel wird nur im Arbeitsspeicher gehalten. Direkte Browser-Nutzung ist ein Sicherheitsrisiko; besser künftig Backend-Proxy.
- Open Food Facts hat nicht alle Whiskys; API/Browser-Zugriff kann blockiert sein.
- BarcodeDetector wird nicht von allen Safari-Versionen unterstützt; manuelle EAN-Eingabe ist möglich.
- KI-Websuche kostet API-Gebühren und kann falsch zuordnen. Nur bestätigte Vorschläge speichern.
- Händlerpreise sind KEINE garantierten Sammler-/Wiederverkaufswerte.
- Keine echte Live-Preisvergleichs-API, keine automatischen Preisupdates.
- Quellenangaben können fehlen und sind kritisch zu prüfen.
