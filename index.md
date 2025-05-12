---
title: Ein Experimentierfeld für strukturierte Dokumente
---

Ich erprobe Methoden für die Erstellung strukturierter Dokumente und
deren Veröffentlichung in unterschiedlichen Formaten (HTML und PDF).
Vieles ist durch meine berufliche Tätigkeit in der
[KoSIT](https://www.xoev.de) motiviert.

## Strukturierte Dokumente schreiben …

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

### … und veröffentlichen
Veröffentlichungsreife Formate (HTML und PDF) werden mit den [xslTNG
Stylesheets](https://xsltng.docbook.org/) und dem [DocBook tng Framework
für Oxygen](https://projekte.kosit.org/steimke/xsltng-kosit/) erstellt.
Die xslTNG Stylesheets generieren *clean, semantically rich HTML5*.
[Chunked
HTML](https://xsltng.docbook.org/guide/2.1.9/ch-using#chunking) für
umfangreiche Dokumente wird unterstützt.

Für PDF stehen drei Möglichkeiten zur Verfügung:

* [Oxygen PDF Chemistry](https://www.oxygenxml.com/chemistry-html-to-pdf-converter.html) ist im Lieferumfang des [Oxygen XML
Editor](https://www.oxygenxml.com/xml_editor.html) enthalten;
* [Antenna House
Formatter](https://www.antennahouse.com/formatter-v7) ist eine kommerzielle *PDF Rendering Engine*;
* [Weasyprint](https://weasyprint.org) ist eine kostenfreie *PDF Rendering Engine*.

Darüberhinaus gibt es eine *experimentelle* Unterstützung für Office Formate.

## Dokumente

- Das **Handbuch** ([HTML](handbuch/index.html)
  | [PDF](handbuch/handbuch.pdf)) beschreibt den Umgang mit
  strukturierten Dokumenten in der KoSIT im Detail.

## Disclaimer
Dies ist eine private Webseite, die ich ausschließlich mit dem Ziel
meiner eigenen Fortbildung in technischen Fragestellungen
betreibe. Ich bin per EMail an `frank.steimke (at) gmail.com`
erreichbar.
