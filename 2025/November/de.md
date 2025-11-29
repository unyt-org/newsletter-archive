# November 2025

Liebe Leserinnen und Leser,

der November war ein Monat stetiger Fortschritte und neuer Kooperationen. Wir haben neue Mitglieder in unserer Community willkommen geheißen, eine Partnerschaft im Bildungsbereich aufgebaut und die Arbeit an unserem neuen DATEX Core fortgeführt.

---

# Verein

Wir freuen uns sehr, unsere **neuen Mitglieder** Bhavna und Mayank in diesem Monat bei unyt.org willkommen zu heißen! Nach unserer letzten Bewerbungsrunde ist unsere Gemeinschaft um weitere talentierte Menschen gewachsen, die unsere Vision teilen.

- **Onboarding mit Mayank**

  Wir haben Mayank ongeboardet, um unsere DATEX-Core-Initiativen voranzutreiben. Seine Expertise wird dazu beitragen, die Entwicklung unserer Kerntechnologien voranzubringen.

- **Erweiterung des Team-Website**

  [Lennart](https://github.com/lennartstoelting) und [Khaled](https://github.com/kha1dx), die im letzten Monat zu uns kamen, um an der DATEX Workbench zu arbeiten, wurden nun offiziell als Praktikanten auf unserer Team-Seite gelistet. Beide leisten weiterhin wertvolle Beiträge zum Projekt.

- **Partnerschaft mit dem IfDL**

  Wir haben ein strategisches Treffen mit dem **Institut für Digitale Lehre (IfDL)** abgehalten, unserem An-Institut mit Fokus auf digitale Bildung. Diese Initiative zeigt spannende Möglichkeiten auf, wie DATEX und UIX moderne Bildungsplattformen und digitale Lernumgebungen unterstützen können.

---

# Entwicklung

Der November war geprägt von intensiver Arbeit an mehreren Fronten, von der DATEX Workbench bis hin zu unseren Rust- und JavaScript-Implementierungen des DATEX Core.

## [DATEX Workbench](https://github.com/unyt-org/datex-workbench/pulls?q=created:2025-11-01..2025-11-30)

Die **DATEX Workbench** – unsere Tooling- und Debugging-Umgebung für das DATEX-Ökosystem – nimmt weiter Gestalt an.

In diesem Monat haben wir erste Code-Reviews abgeschlossen, die wichtige Komponenten integrieren:
* **DATEX Pointer View / Explorer** – zur Untersuchung des Speichers eines DATEX-Endpoints
* **DATEX Block Viewer** – zum Abfangen und Untersuchen eingehender und ausgehender DXB-Blöcke

Ein Merge und Deployment der ersten rudimentären Variante ist für Mitte Dezember geplant.

## [DATEX Core (Rust)](https://github.com/unyt-org/datex-core/pulls?q=is:closed%20created:2025-11-01..2025-11-30)

Bedeutende Fortschritte wurden beim **DIF-Protokoll** (DATEX Interchange Format) erzielt, das den Datenaustausch zwischen DATEX-Implementierungen (z.B. DATEX Core Rust in WebAssembly) und fremden Umgebungen wie JavaScript ermöglicht. Das DIF ist eine entscheidende Infrastrukturkomponente, die eine nahtlose Integration zwischen DATEX und bestehenden Technologien ermöglichen wird.

Wir reviewen die letzten Feature-Branches, während wir auf **Release 0.0.7** hinarbeiten, mit laufenden DIF-Updates und Komponenten, die die JS-Pointer-Synchronisation bis Anfang Dezember ermöglichen sollen.

## DATEX Core JS

Unsere DatexCore<->JavaScript-Verbindungsimplementierung hat wichtige Verbesserungen im Typsystem erhalten. Wir haben **Type Mappings** hinzugefügt, die es **JS-Objekten, Maps und Arrays ermöglichen, mit tatsächlichen DATEX-Core-Typen zu synchronisieren**.

---

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zwei-Wöchentliches Entwickler-Meeting:** Dienstags im zwei-wöchentlichen Rhythmus, 20:00 Uhr MEZ/MESZ.
* **Wöchentliche DATEX-Spezifikations-Diskussion:** Jeden Montag, 20:00 Uhr MEZ/MESZ.
* **Monatliches Management-Meeting:** Dienstag, 09. Dezember, 20:00 Uhr MEZ/MESZ.
