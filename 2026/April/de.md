# April 2026

Liebe Leserinnen und Leser,

Februar und März waren ereignisreiche Monate für unyt.org. Wir haben unsere Jahreshauptversammlung abgehalten, das DATEX-Ökosystem mit einer grundlegenden strukturellen Umgestaltung vorangetrieben und den Grundstein für eine neue KI-Richtlinie gelegt.

# Verein

- **Jahreshauptversammlung**

  Am 14. Februar hielt der Verein seine öffentliche Jahreshauptversammlung ab. Einige Highlights aus den vorgestellten Zahlen: Unser Discord-Server hat sein Ziel von 150 Mitgliedern mit **179 Mitgliedern** übertroffen und das [UIX-Repository](https://github.com/unyt-org/uix) hat die Marke von **100 GitHub-Sternen** geknackt. Die Newsletter-Leserschaft ist von 25 auf **31 Leserinnen und Leser** gewachsen und die Gesamtzahl der Nutzerinnen und Nutzer hat sich auf rund **195** fast verdoppelt. Der Verein besteht derzeit aus 3 Vorständen und 18 ordentlichen Mitgliedern.

  Die Versammlung umfasste außerdem eine Präsentation des **Instituts für Digitale Lehre (IfDL)**, einem An-Institut mit Fokus auf innovative Softwarelösungen für Schulen und Universitäten. Das IfDL stellte seine beiden Produkte [quix.digitalelehre.org](https://quix.digitalelehre.org) und Kritzel vor – begleitet von einem erfreulichen Trend: Die Zahl der Supportanfragen pro Nutzer im Kurs *Neue Webtechnologien* an der TU Berlin ist in den vergangenen zwei Jahren stetig gesunken, was für eine zunehmend ausgereifte UIX/DATEX-Entwicklererfahrung spricht.

- **KI-Richtlinie in Arbeit**

  Beim Verwaltungs-Treffen am 17. März stimmten die Mitglieder dafür, eine offizielle KI-Richtlinie für unyt.org zu erarbeiten. Zu den diskutierten Kerngrundsätzen zählt ein Verbot von GitHub-Copilot-Vorschlägen sowie der Nutzung von Vibe-Coding zur Erstellung ganzer Features von Grund auf, während Tab Completion, Rechercheunterstützung und minimale KI-generierte Code-Schnipsel erlaubt bleiben sollen. Sobald der vollständige Entwurf vorliegt, wird er zur formellen Abstimmung aufgestellt. Auch ein Blogbeitrag zur Richtlinie ist geplant.

- **Neue Praktikanten**

  Wir haben zwei neue Praktikanten im Februar und März begrüßt. Beide bringen sich bereits aktiv in laufende Entwicklungsarbeiten ein.

# Entwicklung

Die bedeutendste Neuerung ist struktureller Natur: Das DATEX-Ökosystem wurde rund um einen neuen übergeordneten `datex`-Cargo-Workspace reorganisiert, der die `core`- und `macro`-Crates unter einem kohärenten Projekt zusammenführt. Parallel dazu wurde die JavaScript-Binding-Schicht umbenannt und eine eigene Native-Crate etabliert – das Ökosystem erhält damit eine klarere Form über seine drei Zielumgebungen hinweg: Web, Desktop/Server und Embedded.

Die strukturellen Änderungen wurden durch die freundliche Unterstützung des bisherigen Inhabers des `datex`-Namens auf crates.io ermöglicht, der den Namen bereitwillig an das unyt.org-Projekt übertragen hat. Vielen Dank!

## [DATEX](https://github.com/unyt-org/datex-core)

* **Grundlegende Projektumstrukturierung.** Das DATEX Core Rust-Projekt wurde rund um einen zentralen `datex`-Workspace reorganisiert, der `core`- und `macro`-Crates sauber voneinander trennt.
* **v0.0.11 veröffentlicht** – mit aktualisierten Macro-Abhängigkeiten, AST-Fixes und einer Reihe von Refactoring-Verbesserungen. Das vorherige **v0.0.10** lieferte ein umfassendes Refactoring der Wert- und Referenz-Ownership-Semantik sowie eine überarbeitete Crypto-API.
* **Neuer `range`-Datentyp.** Ein dedizierter Range-Typ für numerische Werte wurde in das DATEX-Typsystem eingeführt.
* **[datex-web](https://github.com/unyt-org/datex-web)** – der JavaScript/TypeScript-Binding-Layer wurde offiziell von `datex-core-js` umbenannt, um seine Rolle als webspezifischer Layer besser widerzuspiegeln. Mit **v0.0.14** kamen Abhängigkeits-Updates und Crypto-Fixes. Die Arbeit an der plattformübergreifenden Pointer-Synchronisierung läuft und bleibt ein zentrales kurzfristiges Ziel.
* **[datex-native](https://github.com/unyt-org/datex-native)** – eine neue dedizierte Crate für Desktop- und Server-Plattformen, die `datex-web` ergänzt – hat **v0.0.10** erreicht, mit einer verbesserten CI-Pipeline und Test-Workflows.
* **[datex-embedded](https://github.com/unyt-org/datex-embedded)** erhielt Krypto-Unterstützung für das ESP32-Target sowie ein umfangreiches Refactoring der Embedded-Update-Loop, das die Stabilität verbessert und die Grundlage für ein TCP-Client-Interface legt.

## [DATEX Workbench](https://github.com/unyt-org/datex-workbench)

* **Netzwerkschnittstellen-Ansicht.** Das erste Live-Panel für Netzwerkschnittstellen wurde fertiggestellt. Es zeigt aktive Socket-Verbindungen mit Echtzeit-Updates und gibt Entwicklerinnen und Entwicklern damit direkten Einblick in die Kommunikationsschicht eines DATEX-Endpoints.
* **Script-Editor.** Die Arbeit an einem integrierten DATEX-Script-Editor wird fortgesetzt und baut die Workbench schrittweise zu einer vollständigen Entwicklungs- und Inspektionsumgebung aus.

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zwei-Wöchentliches Entwickler-Meeting:** Dienstags im zwei-wöchentlichen Rhythmus, 20:00 Uhr MEZ/MESZ.
* **Wöchentliche DATEX-Spezifikations-Diskussion:** Jeden Montag, 20:00 Uhr MEZ/MESZ.
* **Monatliches Management-Meeting:** Dienstag, 12. Mai, 20:00 Uhr MEZ/MESZ.
