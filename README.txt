WhiskyVault Version 1.0

Installation auf dem iPhone:
1. Lade den Ordner auf einen HTTPS-Webhost (z. B. GitHub Pages oder Netlify).
2. Öffne die HTTPS-Adresse in Safari.
3. Tippe auf Teilen > Zum Home-Bildschirm.
4. Öffne WhiskyVault über das neue Symbol.

Die App speichert Daten und Fotos lokal in IndexedDB auf dem iPhone.
Regelmäßig unter Einstellungen ein JSON-Backup exportieren und in Dateien speichern.

KI-Fotoerkennung:
Unter Einstellungen einen eigenen OpenAI-API-Schlüssel eingeben. Die App sendet
nur bei Betätigung von „Mit KI erkennen“ das gewählte Foto an OpenAI.
Es fallen ggf. API-Gebühren an. Der Schlüssel wird nicht dauerhaft gespeichert.
Ohne Schlüssel ist die manuelle Erfassung vollständig nutzbar.

Wichtig: Diese Version ist ein privater Prototyp. Für produktive öffentliche
Nutzung ist ein Backend-Proxy zur sicheren Schlüsselverwaltung nötig.
