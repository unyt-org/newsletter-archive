# Oktober 2025

Liebe Leserinnen und Leser,

den letzten Monat haben wir intensiv daran gearbeitet, die Grenzen dessen zu erweitern, was DATEX und UIX leisten können – von der Umstrukturierung unseres Codebases für intelligentere Typinferenz bis hin zur Erweiterung des Ökosystems mit einem völlig neuen Tool: der **DATEX Workbench**.

Auch außerhalb der Entwicklung konnten wir beim [ITCS München](https://messe-muenchen.de/de/veranstaltungen/itcs-2025.html) mit neuen Talenten in Kontakt treten.

---

# Verein

Wir freuen uns, **drei neue Mitglieder** im Team willkommen zu heißen: [Oliver](https://github.com/Silauras), [Lennart](https://github.com/lennartstoelting) und [Khaled](https://github.com/kha1dx).
Alle drei sind dem Team beigetreten, um an der **[DATEX Workbench](https://github.com/unyt-org/datex-workbench)** zu arbeiten – einer Anwendung, die vor allem die laufende Entwicklung von **DATEX Core** unterstützen soll, später aber als Open Source Projekt auch für alle zugänglich sein wird.

Die DATEX Workbench soll zu einer **Tooling- und Debugging-Umgebung** innerhalb des DATEX-Kosmos werden. Sie wird Entwicklerinnen und Entwicklern ermöglichen:

* Den Speicher eines DATEX-Endpunkts über eine **Pointer-Ansicht** zu untersuchen
* Live-Daten zu filtern, anzupassen und zu debuggen
* **Eingehende und ausgehende DXB-Blöcke** abzufangen und deren Inhalte einzusehen
* Eine **REPL, Sprachunterstützung** und eine integrierte **DATEX IDE** zu nutzen
* Direkte Integration in **Browser Devtools** und **IDEs wie VS Code**

Oliver arbeitet derzeit an der **Architektur und dem Window-Management-System** und unterstützt zusätzlich unser Kernteam bei **Koordination und Mentoring**.
Wir freuen uns sehr, alle drei an Bord zu haben – herzlich willkommen im Team!

---

# Events

Am **24. Oktober 2025** waren wir auf der **[ITCS Messe München](https://it-cs.io/)**, wo wir viele Entwicklerinnen, Entwickler und potenzielle Partner treffen konnten.
Unser Ziel war es, mit Gleichgesinnten ins Gespräch zu kommen und neue Kooperationen für unyt.org und unsere Open-Source-Projekte anzustoßen.

Es war inspirierend zu sehen, wie groß das Interesse an Projekten wie **DATEX** und **UIX** ist. Wir freuen uns auf zukünftige Zusammenarbeiten, die aus diesem Event entstehen.

---

# Bildung

Im Rahmen des **TU Berlin** Kurses *"Neue Webtechnologien"* von **Adrian Siebing** dienen sowohl **UIX** als auch **DATEX** weiterhin als Beispiele für moderne Webentwicklung.

Eine **Tutorial-Videoreihe** ist derzeit in Arbeit – sie soll Studierende (und die Community) Schritt für Schritt durch folgende Themen führen:

* Einrichtung von **UIX**
* Aufbau einer **Full-Stack-Webanwendung** mit UIX und DATEX
* Verständnis der Prinzipien von **Reaktivität und verteilter Berechnung**

Die Tutorials werden bald veröffentlicht und allen zur Verfügung stehen!

---

# Entwicklung

## [UIX](https://github.com/unyt-org/uix)

* Bugfixes für [CSS Scope Selectors](https://github.com/unyt-org/uix/commit/1f9bb24d818b03a3bdfcab819623e4a5acc6428f)
* [Verbesserungen](https://github.com/unyt-org/uix/commit/507589ed22a9d24fee21ba948a5228ffcfb1e402) für schnellere Startzeiten in großen Anwendungen

## [DATEX (Rust)](https://github.com/unyt-org/datex-core/pulls?q=is:closed%20created:2025-10-01..2025-10-31)

Die Entwicklung von DATEX Core läuft weiter auf Hochtouren.
Wir arbeiten an einer **größeren Umstrukturierung**, um die **Typinferenz** und **IDE-Integration** zu verbessern.
Ein erster **Language Server Prototyp** für die [DATEX CLI](https://github.com/unyt-org/datex-cli) ist bereits einsatzbereit – er bietet **Syntaxfehler-Hervorhebung** und **Typehints** direkt in **VS Code**.

Außerdem wurden weitere Schritte für **Embedded Support** unternommen, mit Zielplattformen wie **ESP32** und ähnlichen Mikrocontrollern.

Wir planen, **DATEX Core Rust 0.0.7** im nächsten Monat zu veröffentlichen – inklusive dieser Neuerungen und weiterer **Spracherweiterungen**.

---

# Bevorstehende Events

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zweiwöchentliches Entwicklermeeting:** Dienstags, alle zwei Wochen, 20:00 Uhr CET
* **Wöchentliches DATEX Spec Talk:** Montags, 20:00 Uhr CET
* **Monatliches Management Meeting:** Dienstag, 25. November, 20:00 Uhr CET
