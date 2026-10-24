Vorrats-App v1.2 – Apple Erinnerungen Test

1. Dateien auf einem HTTPS-Webserver oder zum Testen auf einem PC mit Python-Webserver bereitstellen.
2. iPad: URL des Servers in Safari öffnen. localhost auf dem PC ist NICHT localhost auf dem iPad!
3. iPad: In der App „Apple Erinnerungen aktivieren“ einschalten.
4. Kurzbefehl „Vorrat Einkaufsliste“ muss auf dem iPad vorhanden und eingerichtet sein.
5. Bei einem Wechsel von oberhalb des Mindestbestands auf den Mindestbestand wird der Kurzbefehl gestartet.
6. Bei erneuter Absenkung ohne vorheriges Überschreiten erfolgt kein erneuter Aufruf.
7. iPadOS kann eine Bestätigung verlangen oder zu Kurzbefehle wechseln. Vollautomatische Ausführung ist nicht garantiert.
8. Die Daten liegen lokal im Browserprofil je Gerät/Origin. Sie werden NICHT zwischen Windows und iPad synchronisiert. Für den Umzug JSON-Sicherung exportieren und auf dem iPad importieren.
9. Wenn ein vorhandener Eintrag bereits auf der Einkaufsliste steht, verhindert der eingerichtete Kurzbefehl Duplikate.
10. Bei Updates mit derselben URL bleibt die lokale Datenbank normalerweise erhalten. Vorher Sicherung exportieren.
