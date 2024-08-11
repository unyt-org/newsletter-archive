# August 2024

Liebe Freunde des unyt.org e.V.,

nach einigen turbulenten Monaten gibt uns die Sommerpause Zeit, uns zu erholen und uns auf die wichtigsten Ziele für 2024/Q3 zu konzentrieren.

# VEREIN

**Die Strategie für 2024/Q3 steht fest.**  
Dieses Mal dreht sich alles um Entwicklererfahrung (Developer Experience) und Stabilität.
Mit der Entwicklung dedizierter DATEX-Debugging-Tools und Bemühungen zur Vereinfachung der UIX-Syntax hoffen wir,
nicht nur Hobbyentwickler, sondern auch Profis und Unternehmen anzusprechen, die auf stabile und vorhersehbare System
angewiesen sind, mit denen sie schnell Fortschritte erzielen können.

# ENTWICKLUNG
Unser Fokus lag in den letzten Wochen auf der Identifizierung offener Probleme in DATEX/UIX und
in unseren Services. Wir haben nun damit begonnen, an Features zu arbeiten, die die Stabilität und die Erfahrung der Entwickler verbessern
und haben auch an der Behebung bestehender Fehler in unseren Bibliotheken gearbeitet.

## [UIX](https://github.com/unyt-org/uix/pulls?q=is:closed%20created:%3E=2024-07-01)
* Clients verwenden nun immer eine gepinnte Importmap, die beim Start des Backends aus der bereitgestellten Importmap aufgelöst wird. Das bedeutet, dass die Clients ihre Caches nicht mehr force-reloaden müssen, was in der Vergangenheit ein großes Problem war, und stellt außerdem sicher, dass die DATEX/UIX-Versionen auf dem Backend und Frontend immer identisch sind.
* Wir sind derzeit dabei, unsere experimentelle [Embedded Reactivity Syntax](https://unyt.blog/article/2023-12-04-introducing-experimental-embedded-jsx-reactivity-and-the-syntax) in die Deno-Runtime zu integrieren. Im Moment wird diese Syntax nur auf dem Frontend unterstützt, aber nicht auf dem Backend. Die Integration für Deno ist eine sehr komplexe Aufgabe, da wir unsere eigenen Forks des [Deno](https://github.com/denoland/deno)-Repositories und zwei weiterer zugehöriger Repositories ([deno_ast](https://github.com/denoland/deno_ast/) und [deno_lint](https://github.com/denoland/deno_lint)) maintainen müssen. Dies gibt uns die Möglichkeit, benutzerdefiniertes Transpiler-Verhalten für TypeScript-Dateien hinzuzufügen, die von Deno ausgeführt werden. Die neue Embedded Reactivity Syntax ermöglicht es Entwicklern, sauberen und strukturierten Code zu schreiben, um reaktives Verhalten zu definieren. In unserem [Blog-Artikel](https://unyt.blog/article/2023-12-04-introducing-experimental-embedded-jsx-reactivity-and-the-syntax) könnt ihr mehr darüber erfahren!

## [DATEX](https://github.com/unyt-org/datex-core-js-legacy/pulls?q=is:closed%20created:%3E=2024-07-01)
* Wir haben verschiedene Bugfixes und Verbesserungen im Zusammenhang mit dem SQL-Storage und dem Pointer-Storage im Allgemeinen umgesetzt
* Pointer, die an module exports gebunden sind, sind nun über Prozess-Neustarts hinweg beständig. Zuvor wurde jedem exportierten Wert beim Neustart eine neue Pointer-Id zugewiesen. Die Änderung macht sich vor allem bei Backend-Exporten und Formularen im UIX bemerkbar: Websites müssen nun nicht mehr neu geladen werden, um nach einem Neustart des Backends korrekt zu funktionieren - Backend-Funktionen können aufgerufen werden, sobald das Backend wieder online ist, und Formulare werden korrekt übermittelt, ohne einen Fehler zu verursachen.

# Kommende Veranstaltungen

## StartupSÜD SUMMIT 2024
Der unyt.org e.V. wird am 10. Oktober 2024 auf der StartupSÜD-Messe ausstellen.
Um mehr zu erfahren, lohnt sich ein Besuch auf [https://startupsued.de/summit/](https://startupsued.de/summit/)!

## Treffen
Jeder ist eingeladen, an unseren öffentlichen Meetings teilzunehmen.

* **Wöchentliches Entwickler-Meeting:** Dienstags, 8:00 pm MESZ.
* **Monatliches Management-Meeting:** 03. September, 8:00 pm MESZ.
