---
title: Ein Experimentierfeld für strukturierte Dokumente
---

Ich erprobe Methoden für die Erstellung strukturierter Dokumente und
deren Veröffentlichung in unterschiedlichen Formaten (HTML und PDF).
Vieles ist durch meine berufliche Tätigkeit in der
[KoSIT](https://www.xoev.de) motiviert.

Das zentrale Ergebnis meiner Arbeiten ist das "DocBook tng Framework
für Oxygen". Es basiert auf den [xslTNG
Stylesheets](https://xsltng.docbook.org/) von Norman Walsh. Der
folgende Link zum Bezug des Framework funktioniert derzeit nur
innerhalb der KoSIT: das [DocBook tng Framework für
Oxygen](https://projekte.kosit.org/steimke/xsltng-kosit/) im
KoSIT-internen GitLab.

## Strukturierte Dokumente schreiben und veröffentlichen

Die Dokumente werden im Format [DocBook
5.2](https://tdg.docbook.org/tdg/5.2/) erstellt. Grundsätzlich könnten
sie mit jedem Texteditor bearbeitet werden, vom Standard
[ed](https://www.gnu.org/fun/jokes/ed-msg.html) über
[emacs](https://www.gnu.org/software/emacs/manual/html_mono/nxml-mode.html)
bis [VSCode](https://en.wikipedia.org/wiki/Visual_Studio_Code) ist
vieles möglich. Aber für eine komfortable Bearbeitung ist ein
abgestimmtes Paket von Layout und Validierung mit [Relax
NG](https://de.wikipedia.org/wiki/RELAX_NG) und
[Schematron](https://www.schematron.com/) hilfreich, und das bietet
das Produkt [Oxygen XML
Editor](https://www.oxygenxml.com/xml_editor.html) mit dem Konzept des
[Framework](https://www.oxygenxml.com/doc/versions/25.1/ug-editor/glossary/framework.html). Dieses
Produkt wird für Autoren empfohlen.

Bei manchen Dokumenten, insbesondere den Spezifikationen von IT
Standards der KoSIT, werden wesentliche Bestandteile des Inhalts mit
dem [XÖV
Rahmenwerk](https://www.xoev.de/xoev/xoev-produkte/xoev-handbuch-5060)
automatisch generiert.

Veröffentlichungsreife Formate (HTML und PDF) werden mit den [xslTNG
Stylesheets](https://xsltng.docbook.org/) und dem *DocBook tng
Framework für Oxygen* erstellt.  Sie generieren *clean, semantically
rich HTML5*.  [Chunked
HTML](https://xsltng.docbook.org/guide/2.1.9/ch-using#chunking) für
umfangreiche Dokumente wird unterstützt. Die Veröffentlichung kann
sowohl innerhalb der Oxygen IDE mit Transformationsszenarien erfolgen,
oder vollautomatisiert mit [XPROC 3](https://xproc.org/), [XML
Calabash 3](https://docs.xmlcalabash.com/) (und ich gehe jede Wette
ein, dass Norman Walsh die Dokumentation mit xslTNG erstellt hat
&#x1F601;), sowie [bash](https://de.wikipedia.org/wiki/Bash_(Shell)).

Für die Veröffentlichung im PDF Format stehen drei Möglichkeiten zur
Verfügung:

* [Oxygen PDF Chemistry](https://www.oxygenxml.com/chemistry-html-to-pdf-converter.html) ist im Lieferumfang des [Oxygen XML
Editor](https://www.oxygenxml.com/xml_editor.html) enthalten, und wird genutzt wenn man ausschließlich ;
* [Antenna House
Formatter](https://www.antennahouse.com/formatter-v7) ist eine kommerzielle *PDF Rendering Engine*;
* [Weasyprint](https://weasyprint.org) ist eine kostenfreie *PDF Rendering Engine*.

Darüberhinaus gibt es eine *experimentelle* Unterstützung für Office Formate.

## Dokumente

- Der **Datensatz für das Meldewesen** ([HTML](dsmeld/index.html) |
  [PDF](dsmeld/dsmeld.pdf)) wird von der KoSIT herausgegeben. Im
  Gegensatz zur offiziellen Fassung sind die einzelnen DSMeld-Blätter
  jeweils als [DocBook Reference
  Page](https://tdg.docbook.org/tdg/5.2/ch02#making-refentry)
  ausgeführt.
  
- Die Spezifikation **XMeld** ([HTML](xmeld/index.html) |
  [PDF](xmeld/xmeld-34.pdf)) ist das umfangreichste Dokument. Die
  vollautomatisierte Veröffntlichung in den Formaten PDF, chunked HTML
  und HTML für Microsoft Word dauert auf meinem privaten Lenovo T480
  mit 16GB unter Linux mit Weasyprint für PDF ca. 25 Minuten.

- Das **XInneres-Basismodul** ([HTML](basismodul/index.html) |
  [PDF](basismodul/xinneres.pdf)) definiert wiederverwendbare
  Komponenten für den Standard XInneres der Innenverwaltung.
  
- **XNachweis** ([HTML](xnachweis/index.html) |
  [PDF](xnachweis/spezifikation.pdf)) wird von der KoSIT für das BVA
  erstellt.
  
- **XBestellung** ([HTML](xbestellung/index.html) |
  [PDF](xbestellung/xbestellung.pdf)) ist eine Profilierung von PEPPOL
  BIS Order only

- Das **Handbuch** ([HTML](handbuch/index.html) |
  [PDF](handbuch/handbuch.pdf)) wird irgendwann den Umgang mit DocBook
  tng Framework für Oxygen im Detail beschreiben. Derzeit ist es nur
  eine Sammlung von Textfragmenten.

## Impressum
Dies ist eine private Webseite, die ich ausschließlich mit dem Ziel
meiner eigenen Fortbildung in technischen Fragestellungen
betreibe. Ich bin per EMail an `frank.steimke (at) gmail.com`
erreichbar.
