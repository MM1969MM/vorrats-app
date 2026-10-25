VORRAT – VERSION 1.6

Installation: Inhalt des Ordners vorrats-app in das bestehende GitHub-Pages-Repository hochladen.
Die vorhandene App-Installation auf dem iPad muss für dieses Update nicht entfernt werden.

NEU
- Tabs: Regelmäßiger Vorrat und Einmaliger Vorrat.
- Regelmäßiger Vorrat: Mindestbestand und Apple-Kurzbefehl wie bisher.
- Einmaliger Vorrat: keine Erinnerungen; beim Reduzieren auf 0 wird der Artikel entfernt. Über Rückgängig kann er wiederhergestellt werden.
- Im Bearbeiten-Modus: ✎ öffnet die nachträgliche Bearbeitung von Name, Bestand, Mindestbestand und Vorratsart.
- Beim Anlegen wird die Vorratsart des geöffneten Tabs vorbelegt.
- Bestehende Artikel aus v1.5.1 werden automatisch als regelmäßiger Vorrat behandelt.
- JSON-Sicherung Version 2; Import akzeptiert auch Sicherungen aus Version 1.

UNVERÄNDERT
- Vorratsglas-Icon und PWA-Vollbildmodus.
- Apple-Kurzbefehl 'Vorrat Einkaufsliste' und Rücksprung über webapp:// (im Kurzbefehl).
- Offline-Funktion und lokale IndexedDB-Datenhaltung.

HINWEISE
- Die Daten liegen weiterhin nur auf dem jeweiligen Gerät, nicht in GitHub.
- Eine reine Namensänderung löst keine Apple-Erinnerung aus.
- Die Rückgängig-Funktion bezieht sich auf die letzte Mengenänderung; nach anderen Bearbeitungen wird sie zurückgesetzt.
