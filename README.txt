Vorrats-App v1.3 – x-callback-url Test auf iPadOS

Änderung gegenüber v1.2: Beim Erreichen des Mindestbestands wird shortcuts://x-callback-url/run-shortcut aufgerufen. x-success ist die HTTPS-Startadresse der aktuellen App (relativ zum Standort, kompatibel mit GitHub Pages).

WICHTIG: Im Kurzbefehl „Vorrat Einkaufsliste“ am Ende alle manuellen Rückkehraktionen (App öffnen → Safari, URL öffnen, webapp://) entfernen. Duplikatprüfung und Erinnerungsaktion unverändert lassen.

Die Rückkehr zur installierten Home-Bildschirm-App ist NICHT garantiert: iPadOS kann stattdessen Safari öffnen. x-callback-url ist offiziell für den Rückruf dokumentiert, nicht für die Auswahl einer bestimmten PWA.

GitHub Pages: Dateien aus dem Unterordner vorrats-app direkt in das Repository-Hauptverzeichnis hochladen (vorhandene Dateien überschreiben). Die Datenbank und Bestände bleiben bei gleicher Origin normalerweise erhalten. Vor Update eine JSON-Sicherung erstellen. Service Worker Cache ist v1.3, ggf. App vollständig schließen und neu öffnen.

Offline funktioniert die Bestandsverwaltung nach erfolgreicher Installation; Erinnerungen-Synchronisation zwischen Geräten erfordert Internet.
