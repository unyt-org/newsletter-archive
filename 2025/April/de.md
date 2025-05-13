# April 2025

Liebe Leser,

im April haben wir die Arbeit an der neuen Website aufgenommen und intensiv am DATEX Core Rust weitergearbeitet.

# Verein

**Arbeit an der Website**
Wir durften unsere beiden neuen Teammitglieder, Marvin und Dave, herzlich in unserem Verein willkommen heißen!
Nach der Einführungsphase geht es nun in die Entwicklung eines ganzheitlichen Konzepts und anschließend in die Umsetzung des neuen Internetauftritts für den unyt.org e.V.

# Entwicklung
Wir haben im April viele Verbesserungen an unserer Dokumentation auf docs.unyt.org vorgenommen. Dazu gehören:
* Mehr detailliertere Beispiele zur Nutzung unserer APIs
* Das Entfernen veralteter API-Dokumentation (Soft Deletions)

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:2025-04-01..2024-04-30)
* Verbesserte Dokumentation auf docs.unyt.org
* Optimierung von Struktur und Beispiele, um neuen Nutzer:innen den Einstieg zu erleichtern
* Bugfix für ein Problem, das durch den TypeScript-Compiler (TSC) verursacht wurde, wenn der UIX Projektpfad Leerzeichen enthält

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:2025-04-01..2025-04-01)
* Verbesserte Dokumentation für [Storage Collections](https://github.com/unyt-org/datex-core-js-legacy/blob/main/docs/manual/15%20Storage%20Collections.md)

## [DATEX (Rust)](https://github.com/unyt-org/datex-core)
Wir konnten bedeutendende Fortschritte bei der Rust-Neuentwicklung des DATEX Cores erzielen:
* Die erste Implementierung der Protokoll-Logik zum Senden und Routen ist jetzt funktionsfähig! Wir können nun erste DATEX Blöcke über verschiedene Kanäle (z. B. WebSocket, TCP) adressieren und senden. Das grundlegende Routing funktioniert damit in einem frühen, aber brauchbaren Zustand
* Nächste Ziele:
  * Integration von DATEX Values und Pointern
  * Unterstützung für Serialisierung, Updates und das Updaten von Daten über Endpoints hinweg

## Anderes
An der Technischen Universität Berlin startet in diesem Semester wieder das Programmierpraktikum Neue Webtechnologien,
das von unyt.org-Werkzeugen Gebrauch macht, um den Studierenden in Gruppenarbeit die Entwicklung umfangreicher eigener
Webanwendungen zu ermöglichen. Wir freuen uns darauf, die vielen Ideen zu sehen.

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zwei-Wöchentliches Entwickler-Meeting:** Jeden ersten und dritten Dienstag im Monat, 20:00 Uhr MEZ/MESZ.
* **Wöchentliche DATEX-Spezifikations-Diskussion:** Jeden Montag, 20:00 Uhr MEZ/MESZ.
* **Monatliches Management-Meeting:** 10. Juni 2025, 20:00 Uhr MEZ/MESZ.
