# Juni 2025

Liebe Leser,

Im Juni haben wir bei der Entwicklung des DATEX Core Rust (auch als DATEX v2 bezeichnet) bedeutende Fortschritte erzielt.
Außerdem freuen wir uns, neue Praktikanten in unserem Verein begrüßen zu dürfen.

# Verein

Nach der Überarbeitung unserer Website, die einen weiteren Meilenstein in der Professionalisierung des unyt.org e.V. darstellt, haben wir uns entschieden, Stellenausschreibungen sowohl auf unserer Website als auch auf dem Karrierenetzwerk LinkedIn zu veröffentlichen. Wir waren von der großen Anzahl an Bewerbungen überwältigt und konnten mit vielen Bewerbern nette Gespräche führen.

Wir suchen derzeit noch Praktikanten, freuen uns aber bereits, Norbert in unserem Team begrüßen zu dürfen. Er hat bereits hochqualitative Softwarekomponenten zu unserer hochprioritären Flaggschiff-Entwicklung DATEX Core Rust beigetragen und wird dies auch weiterhin tun. Insbesondere wird er seine Erfahrung nutzen, um sich auf Kryptografie-Implementierungen zu konzentrieren, die ein entscheidendes Element für die Sicherheit von DATEX sind.

Bewerbungen sind jederzeit möglich unter: [https://unyt.org/career](https://unyt.org/career).

# Entwicklung
Eine erste Version der DATEX-Sprache ist implementiert. Der Schwerpunkt liegt nun auf der Synchronisierung von Daten (Pointern) über das Netzwerk.
UIX erhielt kleinere Fehlerbehebungen. Erste Arbeiten am DATEX-Spezifikations-Viewer wurden abgeschlossen.

## [DATEX (Rust)](https://github.com/unyt-org/datex-core/pulls?q=is:closed%20created:2025-06-01..2025-06-30)
* Der values-Branch wurde migriert. DATEX kann nun „primitive“ Werte (alle JSON-Werte) wie Boolesche Werte, Arrays, Strings und Integer darstellen.
* Da JSON eine Teilmenge der DATEX-Skriptsprache ist, kann die DATEX-Core-Laufzeitumgebung nun JSON analysieren.
* Wir haben Benchmarks hinzugefügt, um die Geschwindigkeit unseres Installationsprogramms zu testen.
* Wir haben der DATEX-Sprache Zuweisungen hinzugefügt: `val x = 42 + 5`; `ref y = 52`
* Wir konzentrieren uns nun auf das DATEX-Konzept _Pointer_, um DATEX-Daten zwischen Endpunkten übertragen zu können.
* Tupel hinzugefügt: `(1,5,"Hallo Welt")`

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:2025-06-01..2025-06-30)
* Kleinere Fehlerbehebungen (u.a. Berechtigungsfehler bei Hydration)

## Anderes
* Arbeit am Spec-Viewer, um unsere DATEX-Spezifikation anzeigen zu können

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zwei-Wöchentliches Entwickler-Meeting:** Dienstags im zwei-wöchentlichen Rhythmus, 20:00 Uhr MEZ/MESZ.
* **Wöchentliche DATEX-Spezifikations-Diskussion:** Jeden Montag, 20:00 Uhr MEZ/MESZ.
* **Monatliches Management-Meeting:** Dienstag, 8. Juli, 20:00 Uhr MEZ/MESZ.
