# Juni 2024

Liebe Leser,

in den letzten Wochen haben wir einige Fehler behoben und die Dokumentation für unsere Flaggschiffprodukte UIX und DATEX verbessert.

Während wir noch auf die Ergebnisse unseres Förderantrags warten, bereiten wir unseren dezentralen Authentifizierungsdienst
unyt Auth nach seiner umfassenden Umstrukturierung für den Online-Betrieb vor.

# Verein

**Ergebnisse unseres transformD-Antrags werden für Ende Juni erwartet.**
Im März haben wir unseren Antrag für das Förderprogramm [transformD](https://www.deutsche-stiftung-engagement-und-ehrenamt.de/foerderung/transformd/) eingereicht.
Wir warten auf die Ergebnisse und erwarten, dass diese Ende dieses Monats bekannt gegeben werden. Bei einer erfolgreichen Finanzierung werden wir die Mittel in erster Linie in
den Ausbau, die Weiterentwicklung und die Wartung unserer dezentralen Authentifizierungsinfrastruktur unyt Auth investieren. In zweiter Linie werden auch UIX und DATEX von dieser Investition
profitieren.

# Schnell erklärt: Was ist unyt Auth?
unyt Auth ist ein kostenloser webbasierter Open-Source-Dienst zur Authentifizierung von Personen, Institutionen und Geräten in Anwendungen,
die mit unyt.org-Technologien erstellt wurden.

_Für Entwickler_ bietet er eine einfache Integration mit nur wenigen Codezeilen.  
_Für Benutzer_ verhält er sich wie ein Single-Sign-On-Anbieter wie „Mit Google anmelden“.

_unyt Auth ist jedoch dezentralisiert_ und schreibt die Informationen in einen verteilten Netzwerkspeicher, der mit Schlüsseln, die dem Nutzer gehören, _verschlüsselt_ ist.
_Der Benutzer hat die Kontrolle_ darüber, welche Informationen mit welchen Diensten geteilt werden, für die er sich anmeldet.

Zukünftig wird unyt Auth die Account-Validierung für natürliche Personen und Institutionen mittels behördlicher Nachweise unterstützen und damit eine
schnelle und manipulationssichere Alternative zu kostspieligen Know-Your-Customer (KYC)-Prozessen anbieten.

# Entwicklung
Im letzten Monat haben wir an der Verbesserung unserer Projektdokumentation auf [docs.unyt.org](https://docs.unyt.org) gearbeitet und viele Bugs behoben, um die allgemeine Stabilität von UIX und DATEX zu verbessern.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-05-01)
* Arbeiten an einem verbesserten Error-Handler, um die Fehlersuche für Entwickler zu vereinfachen. Der Benutzer soll Informationen über den Fehler-Stack, Grund und Schritte zur Behebung des Problems erhalten *(WIP)*.
* Verbesserung der UIX Session Handling Logik auf der Serverseite, um verifizierte und vertrauenswürdige Endpoint-Kommunikation zu ermöglichen

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-05-01)
* Die [match](https://docs.unyt.org/manual/datex/storage-collections#pattern-matching) Methode wurde für [StorageMaps](https://docs.unyt.org/manual/datex/storage-collections#storagemaps) eingeführt

## Sonstiges
* Entwicklung von unyt Auth, um einen dezentralen, flexiblen Authentifizierungsmechanismus für UIX@0.2.x bereitzustellen

# Kommende Veranstaltungen 

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Wöchentliches Entwickler-Meeting:** Dienstags, 8:00 pm MESZ.
* **Monatliches Management-Meeting:** 02. Juli, 8:00 pm MESZ.
