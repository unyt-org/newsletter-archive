# Juli 2024

Liebe Freunde des unyt.org e.V.,

im letzten Monat haben wir Standardisierungsstrategien diskutiert und an einer Reihe technischen Verbesserungen unserer Kernprodukte UIX und DATEX gearbeitet.

# VEREIN

Wir planen, das DATEX-Kommunikationsprotokoll und die Laufzeitumgebung zu verbessern. Hier werden wir gemeinsam versuchen, als Mitglieder von Standardisierungsinstitutionen wie dem W3C einen Standard zu erarbeiten und diesen klar zu kommunizieren. Weitere Informationen folgen.

# Schnell erklärt: Client-seitiges Routing
Mit UIX 0.2.16 wird ein neues client-seitiges Routing in das aktuelle UIX-Routingsystem eingeführt. Diese Implementierung nutzt die neue [Navigation API](https://developer.mozilla.org/en-US/docs/Web/API/Navigation). Durch das neue System kann das vollständige Neuladen von Seiten bei der Navigation vermieden werden und es entsteht ein reibungsloser Übergang zwischen verschiedenen Ansichten und Routen.

Sobald das Flag `"frontend-navigation"` zur Liste `experimental_features` in der [app.dx-Konfiguration](https://docs.unyt.org/manual/uix/configuration#experimental-features) hinzugefügt wird, können Frontend-Routen somit ohne Neuladen der Seite aufgelößt und angezeigt werden. Mit der neuen [View Transitions API](https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API) lassen sich mit minimalem Aufwand auch Animationen für Übergänge hinzufügen, um eine nahtlose visuelle Attraktivität zu erzielen.

[Dieser Artikel auf unyt.blog](https://unyt.blog/article/2024-07-07-client-side-routing-for-web-apps-with-uix) gibt eine erste Einführung in das neue UIX-Routing System und erklärt, wie sich die neuen Features verwenden lassen.

# Ein besonderer Tag: Herzlichen Glückwunsch, Benni!
Heute ist ein besonderer Tag für einen der Gründer unseres Vereins und treibender Kraft hinter dem gesamten unyt.org Projekt – **Benedikt Strehle**. Mit mehr als einem Jahrzehnt Erfahrung, die er zusammen mit seinem Cousin Jonas gesammelt hat, wird er so mit Sicherheit noch miterlebt haben, wie das Internet von Pferdekutschen angetrieben wurde, das Windows-UI noch schwarz-weiß war und Steve Jobs noch Haare hatte. Immer mit der Zeit und dem Innovationsgeist gehend, hat er jedoch bald die kreidezeitlichen Ideen von Deno, Rust & co aufgegriffen, um einen riesigen Tech-Stack mit UIX, DATEX, unyt Auth, HELIX & co Stein für Stein aufzubauen.

Ursprünglich begannen er und Jonas jedoch mit der Entwicklung von Spielen und arbeiteten ständig an Allem, was Spaß und Unterhaltung brachte, egal, welche technischen Herausforderung sich den Beiden stellte. Mit großartigen Spielen wie "Keks-mas" oder "Card-To-Throw" bestand nie ein Zweifel daran, dass Benedikt später das gesamte Internet umwälzen würde. Auch wenn niemand von uns genau weiß ob du nun Benedikt, Benni, Ben, oder (unwahrscheinlich) Beni bist - all das ist ziemlich inspirierend und cool – also danke, Ben[\w]*! Und alles Gute zum Geburtstag!

# ENTWICKLUNG
Mit dem jüngsten UIX Release wurde ein neues Frontend-Routing System eingeführt. An unseren Core-Projekten konnten weitgehende Stabilitäts-Verbesserungen vorgenommen werden.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-06-01)
* Einführung eines experimentellen [Frontend-Routers](https://github.com/unyt-org/uix/pull/160) für Client-seitige Navigation
* Support für die neue [View Transitions API](https://docs.unyt.org/manual/uix/configuration#experimental-features)
* [`Dates`](https://github.com/unyt-org/uix/issues/154) können nun als Werte für HTMLInputElemente verwendet werden

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-06-01)
* Verbesserung der [Endpoint Instanz-Ermittlung](https://github.com/unyt-org/datex-core-js-legacy/pull/116) zwischen verschiedenen Browser-Tabs
* Sonstige Stabilitätsverbesserungen und Bugfixes

## Anderes
* Der [unyt Auth](https://auth.unyt.org)-Service ist nun wieder aktiv

# Kommende Veranstaltungen

Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Wöchentliches Entwickler-Meeting:** Dienstags, 20:00 Uhr MEZ.
* **Monatliches Management-Meeting:** 09. July, 20:00 Uhr MEZ.
