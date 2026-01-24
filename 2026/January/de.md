# unyt.org schaut zurück: 2025 – ein Jahr des Umbruchs

Liebe Leserinnen und Leser,

in dieser Januarausgabe des unyt.org-Newsletters möchten wir auf das vergangene Jahr zurückschauen. Bei unbedarfter Betrachtung mag man feststellen, dass der Entwicklungs-Fortschritt in unseren Haupt-Projekten UIX und DATEX Core JS (Legacy) langsamer geworden ist. Tatsächlich liegt seit einem Jahr unsere Konzentration auf der Entwicklung des neuen [DATEX Core](https://github.com/unyt-org/datex-core) in Rust.

Mit über 120.000 Zeilen Rust-Code in diesem Bereich allein arbeiten wir mit Hochdruck daran, dass unser neues [Datenübertragungs- und Kommunikationssystem](https://datex.unyt.org) in Zukunft die verlässliche, standardisierte und serienfähige Basis für eine gänzlich neue Version von UIX darstellen kann – und darüber hinaus noch auf vielen weiteren Gerätetypen [bis hin zu Embedded Devices](https://github.com/unyt-org/datex-core-embedded) lauffähig wird. Natürlich werden auf dem Weg dahin UIX 0.x and DATEX Core JS (Legacy) weiterhin wichtige Bug Fixes und Maintenance Updates erhalten.

# Offene Jahreshauptversammlung: 14. Februar, 11 Uhr

Wir laden alle herzlich zur öffentlichen Jahreshauptversammlung ein, wo ein umfassender Rückblick auf das Jahr 2025 gegeben und die zukünftige Agenda des Vereins beschlossen wird.

| | |
|-|-|
| Datum | **14. Februar 2026, 11:00 Uhr, MEZ** |
| Ort | [https://meet.digitalelehre.org/unyt-org](https://meet.digitalelehre.org/unyt-org) |
| Kalender | [📅 Eintrag herunterladen und speichern](https://raw.githubusercontent.com/unyt-org/newsletter-archive/refs/heads/main/2026/January/assembly.de.ics) |


# `parseInt()` – Der Rückblick in Zahlen

Gemeinsam haben wir viel erreicht. Um es quantiativ zu formulieren:

**+ 120.000** Zeilen Rust-Code.  

**20** neue Repositories.  

**+ 9.000** Zeilen im DATEX Core JS.  

**4** neue Praktikanten.  

**+ 2.000** Zeilen in der neuen DATEX Workbench.  

**130** neue Nutzerinnen und Nutzer.

**+ 5.000** Zeilen weiterer TypeScript-Code.  

**3** neue Vereinsmitglieder.

# Verein

In Zusammenarbeit mit unseren engagierten Praktikanten konnten wir diverse Erfolge im Jahr 2025 verzeichnen.

- **Neue Homepage**
  
  Mit aktuellen Komponenten, mehr Struktur, weniger Textblöcken und einem ansprechenden Design hat insbesondere unser Praktikant Marvin wertvolle Arbeit geleistet, um mit uns einen ansprechenenden Webauftritt auf [https://unyt.org](https://unyt.org) zu gestalten.


- **Merchandise und Neuer Shop**

  Was wäre ein Tech-Verein ohne Hoodies, ohne Kaffeetassen und ohne einen in UIX selbst entwickelten Online-Shop, wo man all das kaufen könnte? Dieses dystopische Szenario wäre kaum vorstellbar und ist dank des 2025 eröffneten [unyt.org-Shops](https://shop.unyt.org) nun kein Problem mehr. Alle Gewinne gehen selbstverständlich zu 100% in die Vereinskasse und werden zur Verfolgung unserer gemeinnützigen Ziele genutzt.

- **Drei neue Vereinsmitglieder**

	Wir freuen uns über unsere Neuzugänge, die sich hervorragend in den Verein eingebracht haben und bei Entwicklung sowieso Organisation unterstützen. Vielen Dank und, noch einmal, herzlich Willkommen!

- **Messe Neue Webtechnologien**

	Das an der Technischen Universität Berlin ansässige Modul [Neue Webtechnologien](https://nwt.tu-berlin.de) feierte im Sommer sein 2-jähriges Bestehen mit einem besonderen Abschluss. Auf einer Pop-Up-Messe präsentierten die Studierenden ihre vielfältigen auf unyt.org-Technologien basierenden Web-Apps, spielten kollaborative Spiele mit Besuchern und präsentierten einem ausgewählten Publikum Keynotes zu ihren Errungenschaften. Herzlichen Glückwunsch!

# Entwicklung

Das Jahr 2025 war geprägt von grundlegenden Entwicklungen, die das Fundament für die nächste Generation unserer Technologien legen. Der Fokus lag auf dem neuen DATEX Core in Rust sowie der Schaffung eines robusten Ökosystems an Werkzeugen und Integrationen.

## [DATEX Core](https://github.com/unyt-org/datex-core)

Mit dem **[DATEX Core Rust](https://github.com/unyt-org/datex-core)** haben wir eine völlig neue Basis für das DATEX-Protokoll geschaffen. Die wichtigsten Meilensteine des Jahres waren:

* **Grundlagen der Protokoll-Version 2** – Die Grundlagen für die zweite Generation des DATEX-Protokolls wurden erarbeitet und implementiert.

* **5. August: Erste Block-Übertragung** – An diesem Tag wurden erstmals erfolgreich Blöcke über das DATEX-Protokoll übertragen – ein historischer Meilenstein für das Projekt.

* **JavaScript-Native-Kommunikation** – Ebenfalls im August folgte die die erste erfolgreiche Kommunikation zwischen einer JavaScript-Umgebung und einem Native-Endpoint via WebSocket.

* **Typsystem** – Ein vollständiges Typsystem wurde etabliert, das die Grundlage für typsichere DATEX-Kommunikation bildet.

* **DIF-Protokoll** – Das DATEX Interchange Format (DIF) ermöglicht den Datenaustausch zwischen verschiedenen DATEX-Implementierungen und externen Umgebungen wie JavaScript.

* **Neue Programmiersprache** – Im Dezember wurde die Entwicklung einer ersten Version der DATEX-Cross-Network-Programmiersprache abgeschlossen.

* **[Embedded-Unterstützung](https://github.com/unyt-org/datex-core-embedded)** – Im September wurde DATEX erstmals auf ESP32-Mikrocontroller portiert und eröffnet damit neue Anwendungsfelder im IoT-Bereich.

* **Native CLI-Werkzeuge** – Ein natives Kommandozeilen-Tool wurde entwickelt, das REPL-Funktionen und die direkte Ausführung von DX-Dateien ermöglicht.

## [DATEX Workbench](https://github.com/unyt-org/datex-workbench)

Die **DATEX Workbench** wurde als neue Tooling- und Debugging-Umgebung für das DATEX-Ökosystem konzipiert:

* **DATEX Pointer View / Explorer** – Ermöglicht die Untersuchung des Speichers eines DATEX-Endpoints.
* **DATEX Block Viewer** – Erlaubt das Abfangen und Untersuchen eingehender und ausgehender DXB-Blöcke.

## [UIX](https://github.com/unyt-org/uix)

UIX erhielt im Laufe des Jahres kontinuierliche Wartung und Pflege:

* **Bug Fixes** – Zahlreiche Fehlerbehebungen sorgten für eine stabilere Nutzungserfahrung.
* **Maintenance Updates** – Laufende Wartungsarbeiten hielten das Framework aktuell und kompatibel.

# Vision 2026

Für das Jahr 2026 haben wir bereits einen Plan aufgestellt, den wir bei unserer öffentlichen Jahreshauptversammlung am **14. Februar 2026** um **11:00 Uhr** MEZ vorstellen werden.

Insbesondere zählen zu unserer Vision 2026:

* **DATEX Core Prototyp** – Ein erster verlässlich nutzbarer öffentlicher Prototyp des neuen DATEX Core mit feinjustierter Sprachsemantik.
* **DATEX Core JS** – Ein erstes Release unserer JavaScript-Bindings für den neuen DATEX Core
* **UIX Next-Gen Prototyp** – Die nächste UIX-Generation, die DATEX mit einem Full-Stack-Web-Framework vereint und somit verlässliche Cross-Network-Reaktivität, Backend-Imports und DOM-Rendering bietet.

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zwei-Wöchentliches Entwickler-Meeting:** Dienstags im zwei-wöchentlichen Rhythmus, 20:00 Uhr MEZ/MESZ.
* **Wöchentliche DATEX-Spezifikations-Diskussion:** Jeden Montag, 20:00 Uhr MEZ/MESZ.
* **Jahreshauptversammlung:** Samstag, 14. Februar 2026, 11:00 Uhr MEZ/MESZ.
