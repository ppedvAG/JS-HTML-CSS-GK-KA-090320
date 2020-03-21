# THEORIE VON HTML, PPEDV EDITION
<!-- Kommentare übergehen nicht in die PDF-Datei -->
<!--
PFLEGEN DIESER FOLIEN
* Überschriften vereinheitlichen (check 06.01.2020)
* draft-Folien und Abschnitte ausblenden
* Folien mit viel Code in Demos übernehmen
* in Demos übernommenen Folien mit #demo versehen
* Folien auf Englisch übersetzen
* Folien mit weniger als 5 Zeilen Text mit anderen Folien vereinen
* LABS einbinden
* Code-Bilder als Text umschreiben
* ???, !!! und #todo abarbeiten
* Tabellen vereinheitlichen (Folie mit Tabelle im Folienmaster anlegen?)
 -->

ppedv AG, Vadzim Naumchyk

<!-- ![html-logo](html-images/html-logo.png) -->

<img src="html-images/html-logo.png" alt="html-logo" height="300"/>

## HTML > GETTING STARTED

### HTML > GETTING STARTED > IDEA OF HTML

WAS IST HTML

- Hyper Text Markup Language
- Dokumentenbeschreibungsprache (Auszeichnungssprache)
- Keine Programmiersprache
- Aktuelle Version 5.2    <!-- #checkForUpdates -->

WOZU IST HTML

- Zuständig für die Struktur der Seite
- Markierungen (Markup) für die Struktur sind die HTML-Tags
- Plattformübergreifend
- Bilder, Links, Formulare, etc.

<!--
IN-COURSE REMARKS
Hypertext ist ein Text, der nicht linear sein muss (not constrained to be linear).
Hypertext ist ein Text, der Links zu anderen Texten enthält.
HyperMedia ist ein Hypertext, der auch Grafiken, Videos oder Klänge enthalten kann (not constrained to be text).
Hypertext und HyperMedia sind Konzepte, keine Produkte.
https://de.wikipedia.org/wiki/Hypertext

---------------------------------------------------------
PREPARATION REMARKS
checkForUpdates
 -->

### HTML > GETTING STARTED > LINKS

OFFIZIELLE QUELLEN

- HOMEPAGE <https://html.spec.whatwg.org/>
- DOCS <https://html.spec.whatwg.org/dev/>
- BLOG <https://blog.whatwg.org/>
- CODE <https://github.com/whatwg/html>

<!--
IN-COURSE REMARKS
Html5test: zeigt wie gut mein Browser HTML5 unterstützt.
Validator: Überprüft das Markup (HTML, XHTML, ...) von Webdokumenten.

http://html5test.com
http://validator.w3.org/
https://html.spec.whatwg.org/multipage/ (HTML Living Standard)
https://www.w3.org/html/
https://validator.w3.org/
Überprüfen, ob die Webseite stabil gebaut ist
Grammatikkenner

http://html5test.com/
Was kann welcher Browser

http://csszengarden.com/
Für CSS Beispiele

---------------------------------------------------------
PREPARATION REMARKS
*todo in die notes übernehmen
 -->

### HTML > GETTING STARTED > TOOLS

- VSCode
- VSCode Erweiterungen
  - open in browser
  - auto rename tag
  - evtl. Prettier

<!--
IN-COURSE REMARKS

---------------------------------------------------------
PREPARATION REMARKS

??? auto complete tag benennt die schließenden Tags nicht um
(evtl auch auto complete tag und auto close tag)

Prettier löscht beim Formatieren die leeren Zeilen
default Formatter - vscode.html

klicken auf install, dann reload

??? css formatter - was macht diese Erweiterung ?
??? was ist default oder built-in formatter für css, html und js ?
 -->

### HTML > GETTING STARTED > LAB

html-helloworld.html

<!--
IN-COURSE REMARKS
html-helloworld.html wird später zu index.html. Deswegen nur das einbauen, was später auch gebraucht wird. Alles andere, was man am Anfang zeigen möchte, in der der Datei html-syntax.html zeigen.

Ein erstes HTML5-Dokument
<!DOCTYPE html>
    <head>
        <meta charset="utf-8">
        <title>HTML</title>
    </head>
    <h1>Ich bin ein HTML5-Dokument</h1>
    <p class=beispiel>  Hallo!
    <p>
        Ich bin ein HTML5-Dokument!

---------------------------------------------------------
PREPARATION REMARKS

 -->

## HTML > SYNTAX

### HTML > SYNTAX > TAGS

Von der Syntax her gibt es 5 Arten von HTML-Tags:

1. Doctype-Tag `<!DOCTYPE>`
2. Start-Tag aus einem Tag-Paar `<button>`
3. End-Tag aus einem Tag-Paar `</button>`
4. ein alleinstehender Tag `<br/>` oder `<br />` (Version HTML4) oder einfach `<br>` (Version HTML5, so wie ein Start-Tag)
5. Kommentar-Tag `<!-- kommentar vom web-entwickler -->` (auch quasi alleinstehend)

Obwohl ein Start-Tag und ein End-Tag zwei Tags sind, werden sie zusammen auch einfach nur als HTML-Tag genannt. Z.B. das Paar `<p></p>` werden als p-Tag genannt. Die Mehrheit von HTML-Tags sind Tagspaare. Alleinstehende Tags sind etwas seltener. Und Doctype-Tag trifft man nur einmal pro eine HTML-Datei.

### HTML > SYNTAX > TAG-CONTENT, STRINGS, ENTITIES

Ein Tag-Paar besteht aus zwei Teilen, um dazwischen noch irgendwelcheren Inhalt einzuschließen. Welcher Inhalt es ist, hängt vom jeweiligen Tag ab. Meistens sieht man als Inhalt Text (String) oder weitere HTML-Tags.

Wenn es String ist, dann sind hier alle Zeichen ohne Bedenken zu benutzen außer diejenigen, die für HTML-Parser von besonderer Bedeutung sind. Und nämlich die spitzen Klammern. Mit denen muss man vorsichtig sein, nicht dass ein neuer unerwünschter Tag angelegt wird.

Will man aber genau die spitzen Klammern im Browser rendern lassen, kann man Sign-Entities benutzen. Vllt kennt das jemand auch aus Word. Z.B. `&lt;` wird gerendert als `<`.

Siehe `html-syntax.html, Syntax von Tags`.

### HTML > SYNTAX > ATTRIBUTES & IDENTIFIERS

Durch Hinzufügen eines HTML-Tags in einer HTML-Datei wird vom Browser in seinem Speicher ein HTML-Element angelegt. Das ist ein komplexes Objekt mit viiiiiiielen Eigenschaften. Wie z.B. Id-Bezeichner, Höhe, Breite, ob es draggable ist, Relation zu anderen Tags u.v.m.

Viele von diesen Eigenschaften bleiben einfach leer. Sie sind dafür da, um dem Web-Entwickler die Möglichkeit zu geben, diese Eigenschaften mit eigenen Werten zu befüllen.

Einige von diesen Eigenschaften bekommen sofort die Werte, die einem HTML-Element von Anfang an eigen sind. Wie z.B. die Schriftgröße bei den Überschriften erster Ordnung (h1) - sie ist zweimal größer als die bei normalen Text-Absätzen (Paragraphen).

Die Eigenschaften von HTML-Elementen können ihre Werte z.B. über HTML-Attribute bekommen.

Siehe `html-syntax.html, Syntax von Attributen`.



## HTML & EMMET / ZEN CODING

## HTML > METADATA CONTENT

## HTML > SECTIONING CONTENT

## HTML > HEADING CONTENT

## HTML > LISTS & TABLES

## HTML > PHRASING CONTENT

## HTML > EMBEDDED CONTENT

## HTML > INTERACTIVE CONTENT (FORMS)

## HTML > HOW TOS

## DRAFT HTML & WEB SECURITY

## HTML > PREPROCESSORS

## DRAFT HTML > HTML EMAIL

## HTML & WEB APIS

## HTML > FACTS
