# November 2024

Liebe Leserinnen und Leser,

die letzten zwei Monate bestanden aus zahlreichen Stunden Arbeit und Planung, die schließlich zur Veröffentlichung von UIX 0.3 führten – ein Sprung in der Entwicklererfahrung.

# Verein

- **Der StartupSÜD Summit war ein Erfolg.**

  Im Oktober stellte der Verein [auf dem StartupSÜD Summit](https://de.linkedin.com/posts/unyt-org_unytorg-uix-startups%C3%BCd-activity-7255479246079324160-5oft) in
  Ulm aus. Viele interessante Gespräche ergaben sich am prominent 
  platzierten unyt.org-Pavillon. Wir freuen uns auf die  
  Zusammenarbeit und Partnerschaft mit den inspirierenden Menschen,
  die wir dort getroffen haben.

- **Überarbeitung der Website steht bevor**

  Nachdem mehrere Vorschläge erarbeitet wurden, wird die Überarbeitung der Hauptseite von unyt.org nun mit dem Beitritt eines neuen Mitglieds für unsere Abteilung Kommunikation und Öffentlichkeitsarbeit Wirklichkeit. Als professionelle Web- und Marketingdesignerin wird sie sich ausdrücklich auf die neue Website konzentrieren und ihre Zeit der Erstellung einer kohärenten und optisch ansprechenden Benutzeroberfläche für unseren gesamten Webauftritt widmen.

- **Jubiläum: Ein Jahr Neue Webtechnologien**

  [Neue Webtechnologien](https://www.tu.berlin/snet/studium-lehre/modulbeschreibungen/programmierpraktikum-neue-webtechnologien) ist ein Kurs, der die Grundlagen moderner Vernetzung und Webanwendungsentwicklung vermittelt und dabei tiefgehende Sicherheitsansätze berücksichtigt. Es ist auch einer der ersten Kurse, in denen Technologien von unyt.org gelehrt werden und der als offizielle Qualifikation für staatliche Hochschulabschlüsse anerkannt ist. Nach vielen interessanten Studentenprojekten, die von Produktivitätstools bis hin zu Live-Unterhaltung reichten, feierte Neue Webtechnologien im Oktober 2024 seinen ersten Geburtstag.

# Schnell erklärt: Introducing Magic – Veröffentlichung von UIX 0.3
UIX 0.3 ist ein bemerkenswerter Sprung in Richtung einer angenehmen Entwicklererfahrung. Es führt standardmäßig automatische Reaktivität ein, was die Entwicklung erheblich vereinfacht. Diese Version macht manuelles Reaktivitätsmanagement, wie die Verwendung von `$`-Eigenschaften oder die `always`-Methode, überflüssig. Das Framework verarbeitet Statusaktualisierungen und DOM-Rendering jetzt autonom, ganz von selbst! Dies wird durch JUSIX erreicht, ein neues Deno SWC-Plugin, das JSX als reaktives JavaScript verarbeitet und mit _Deno für UIX 2.0_ mitgeliefert wird.

Dieser UIX 0.3-Codeausschnitt zeigt beispielsweise ein Kontrollkästchen, das an einen `checked`-Zeiger gebunden ist und die Benutzeroberfläche automatisch aktualisiert, wenn es umgeschaltet wird:

```tsx
const checked = $(false);
export default
    <div>
        <input type="checkbox" checked={checked}/>
        <label>{checked ? "Angekreuzt" : "Nicht angekreuzt"}</label>
    </div>
```

In UIX 0.3 muss die Methode `always` für reaktive Updates nicht mehr manuell verwendet werden. Der folgende Code reicht jetzt aus, um Änderungen automatisch widerzuspiegeln:

```tsx
const myVar = $(4);
<div>{myVar + 1}</div>;
myVar.val ++;
```

Reaktivität funktioniert jetzt sofort. Die neue Version enthält außerdem Leistungsverbesserungen, Fehlerbehebungen und ein neues benutzerdefiniertes Installationsskript, das die Einrichtung vereinfacht, um ein durchgängig komfortables Entwicklererlebnis zu bieten.

# Entwicklung
UIX 0.3 mit seiner neuen Syntax und einer benutzerdefinierten optimierten Deno-Runtime für UIX ist veröffentlicht. DATEX 0.2 ist veröffentlicht. Eine neue DATEX-Workbench befindet sich in der Entwicklung.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:2024-09-01..2024-10-31)
* **UIX 0.3 ist veröffentlicht**! Als eine der größten Veröffentlichungen in der Geschichte des Full-Stack Frameworks unterstützt es eine völlig neue Reaktivitätssyntax, die die Entwicklung von Anwendungen mit reaktivem Zustand erheblich vereinfacht.
* **Deno for UIX 2.0 ist veröffentlicht.** Zum ersten Mal wird UIX von einer eigenen dedizierten Version von Deno begleitet. Die implementierten Änderungen befinden sich tief im Kern der modernen Laufzeitumgebung, mit Verbesserungen am JSX-Compiler und Code-Linter, die den Komfort von UIX 0.3 erst möglich machen.
* **Einführung des neuen Setup-Erlebnisses.** Nach der Developer Experience Initiative 2024/Q3 wurde einer der ersten Eindrücke für neue Entwickler erheblich verbessert. Das neue Installationsverfahren benötigt nur einen einzigen Befehl und funktioniert auf allen wichtigen Betriebssystemen. Es installiert Deno für UIX und UIX 0.3 und setzt Umgebungsvariablen in einem Schritt. Das Verfahren zur Projekterstellung ist mit einer Reihe von Vorlagen zur Auswahl besser anpassbar.
* **Plattformübergreifende TailwindCSS-Unterstützung ist jetzt verfügbar.** Nach vielen Anfragen ist das zuvor experimentelle native TailwindCSS-Theme, das mit UIX ausgeliefert und integriert wird, jetzt auf allen wichtigen Betriebssystemen verfügbar.
* **Docker-Host v2 ist veröffentlicht.** Die neue Version bietet tokenbasierten Zugriffsschutz und zahlreiche Sicherheits- und Benutzerfreundlichkeitsverbesserungen.

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:2024-09-01..2024-10-31)
* **DATEX 0.2 ist veröffentlicht.** Die Verbesserungen umfassen umfassende Unterstützung für die neue einheitliche Reaktivitätsfunktion (`$()`), verbesserte SQLite3-Unterstützung, die den Betastatus erreicht hat und bald als Standard-Speicher-Backend für Eternal veröffentlicht werden könnte
* **Die DATEX Workbench befindet sich in der Entwicklung.** Erste Versionen wurden bereits bei Entwicklertreffen vorgestellt. Die Workbench wird aus einer Reihe von Inspektions-, Debugging- und Testtools für DATEX bestehen, die direkt in den Browser Developer Tools oder in Visual Studio Code genutzt werden können. Vorabversionen können bereits [aus dem Chrome Web Store](https://chromewebstore.google.com/detail/datex-workbench/pkbjldajjofekolhdglbncpjpkdplnok) installiert werden.

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Zwei-Wöchentliches Entwickler-Meeting:** Jeden ersten und dritten Dienstag im Monat, 20:00 Uhr MEZ/MESZ.
* **Monatliches Management-Meeting:** 03. Dezember 2024, 20:00 Uhr MEZ/MESZ.
