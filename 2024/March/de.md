# März 2024

Liebe Freunde des unyt.org e.V.,

die Updates des letzten Monats drehen sich um wichtige Kompatibilitäts- und Stabilitätsverbesserungen für unsere Frameworks und um strategische Entscheidungen zum Auftritt in der Öffentlichkeit.

# Verein
Wir verbessern unseren Webauftritt und erweitern unsere Präsenz in den sozialen Netzwerken. 

- **Der unyt.org e.V. wächst.**
  
    Innerhalb der letzten Wochen konnten wir **5 neue Mitglieder** für unseren Verein gewinnen. Herzlich willkommen!

    Den Mitgliedsantrag kann auf [unyt.org](https://unyt.org/join) gestellt werden.


- **Wir arbeiten an einer Überarbeitung unserer Homepage.**

	Nach intensiven Diskussionen und Anregungen unserer Mitglieder haben wir uns für einen neuen Kommunikationsauftritt in der Öffentlichkeit entschieden. Wir wollen wirkungsvoll vermitteln, was die Ziele von unyt.org sind und wie wir versuchen, diese durch die Bereitstellung von Tools und Plattformen, die wir entwickeln, zu realisieren. Als Community möchten wir den offenen und einladenden Charakter unserer Projekte auf allen unseren Seiten vermitteln.

- **Wir verstärken unsere Präsenz in den sozialen Medien. Wir freuen uns über Unterstützung!**

	Um eine größere Zielgruppe auf unsere Projekte aufmerksam zu machen, werden wir uns künftig verstärkt in sozialen Medien beteiligen. In erster Linie verwenden wir [LinkedIn](https://linkedin.com/company/unyt-org), um Themen zu kommunizieren, die unsere Organisation und die Community betreffen (z.B. Events). Mastodon und [X (Twitter)](https://unyt.org/twitter) werden die weniger formellen Medien für die Interaktion mit der Entwickle-Community sein. 

  Falls dies nach einer interessanten Tätigkeit klingt, laden wir dich gerne dazu ein, unserer Arbeitsgruppe für Öffentlichkeitsarbeit beizutreten.

# Entwicklung
Die Ladezeiten von UIX wurden erheblich verbessert. Wir haben mehrere Bugfixes in DATEX Core JS eingearbeitet und zahlreiche Refactorings vorgenommen.

Die neuen Versionen `UIX 0.2.x` und `DATEX 0.1.x` enthalten Breaking Changes aufgrund der neuen [ES6 Decorator](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0/#decorators). Wir unterstützen jetzt die neueste Deno-Version. Bitte migriere deine Projekte!

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-02-01)
* Migration auf die die neue Version der Decorator, jetzt kompatibel mit Deno v0.40.0+
* Verbesserte Source-Map-Unterstützung für TypeScript-Dateien
* Hybrid-Rendering unterstützt jetzt [early hydration](https://docs.unyt.org/manual/uix/rendering-methods#hybrid-rendering)
* Einführung von [Minification und Module-Preloading](https://github.com/unyt-org/uix/issues/102) für optimiertes Laden

# [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-02-01)
* Migration auf die die neue Version der Decorator, jetzt kompatibel mit Deno v0.40.0+
* Einführung des neuen [SQL Storage](https://github.com/unyt-org/datex-core-js-legacy/pull/90) für eine effizientere Handhabung von großen Daten
* Einführung von [match conditions](https://docs.unyt.org/manual/datex/storage-collections#match-conditions) für StorageCollections
* Wichtige Bugfixes und Speicherverbesserungen

# Andere Themen
Der Kurs "Neue Web-Technologien" an der **TU Berlin**, der von Adrian Siebig als Dozent begleitet wurde, wurde am 14. Februar mit der Präsentation der UIX-Projektarbeit der Studenten abgeschlossen. Wir sind beeindruckt von den Ergebnissen, die die Kursteilnehmer erzielt haben und sind stolz darauf, dass die unyt.org-Projekte eine wichtige Rolle im Kurs gespielt haben.

# Kommende Veranstaltungen 

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

**Wöchentliches Entwickler-Meeting:** dienstags, 20:00 Uhr CET.
**Monatliches Management-Meeting:** 05. März, 20:00 Uhr MEZ.

----------------

Wir hoffen, dass unsere neuen Kommunikationskanäle die Reichweite unserer Projekte steigern und der Verein dadurch neue wertvolle Mitstreiter gewinnen kann. Vielen Dank, dass du dabei bist.

Mit freundlichen Grüßen
Das unyt.org-Team
