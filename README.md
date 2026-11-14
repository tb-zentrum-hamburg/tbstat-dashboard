# tbstat-dashboard

Öffentliches Dashboard "TB-Statistik" des Tuberkulose-Zentrums Hamburg: interaktive Kurzfassung mit freigegebenen, aggregierten Jahreswerten.

- Datei: `tb-dashboard.html` (Single-File-HTML, ohne Passwort)
- Die passwortgeschützte Fassung liegt im Repository `tbstat-portal`.

Die Version steht im Fußbereich der Seite und als Git-Tag `vX.Y`. Jede Änderung erhält einen Changelog-Eintrag und eine Commit-Nachricht `Dashboard vX.Y: …`.

## Changelog

- v1.0 (31.10.2026): Erste Fassung mit Hamburg-Design (Arial), GoatCounter-Zähler und Link "Informationsseiten des Tuberkulosezentrums".
- v1.1 (31.10.2026): `index.html` als Weiterleitung auf `tb-statistik.html` ergänzt, damit GitHub Pages im Hauptverzeichnis das Dashboard öffnet.
- v1.2 (03.11.2026): Neue Abschnitte "Betroffenes Organ" (Lunge gegenüber außerhalb der Lunge, Formen der extrapulmonalen Tuberkulose; 2017–2025 und 2025) und "Infektiosität der Lungentuberkulose" (mikroskopisch offen, kulturell offen, geschlossen; 2019–2025) mit Zusatztabelle.
- v1.3 (03.11.2026): Abschnitt "Geburtsland" (In Deutschland gegenüber im Ausland geboren, häufige Geburtsländer) vollständig entfernt, ebenso die Kennzahl "im Ausland geboren" und die Tabellenspalte. "Alter" und "Medianalter" stehen jetzt als zwei getrennte Karten nebeneinander.
- v1.4 (04.11.2026): Hinweise zu den Zahlen ergänzt um die Erklärung zu Abweichungen gegenüber den RKI-Zahlen (unterschiedliche Stichtage, RKI-Stichtag 28.02. des Folgejahres). Formulierung zu kleinen Fallzahlen überarbeitet.
- v1.5 (04.11.2026): Datenstand Juli 2026 in den Hinweisen zu den Zahlen genannt.
- v1.6 (14.11.2026): Versionsnummer im Fußbereich der Seite angezeigt. Git-Tags eingeführt (ab `v1.6`).
- v1.7 (14.11.2026): Seite von `tb-statistik.html` in `tb-dashboard.html` umbenannt. `tb-statistik.html` bleibt als Weiterleitung bestehen, damit alte Links weiter funktionieren. `index.html` verweist auf die neue Datei.
