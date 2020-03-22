# NOTIZEN VON VADZIM

## TEXT EDITORS SHORTCUTS

Bemerkung: Page (wie auf den Tasten PageUp und PageDown) ist Anzahl von Zeilen, die im Moment in das Viewport passen

| shortcut | effect |
| --- | --- |
| `ctrl left` | go to begin of the word |
| `ctrl shift left` | go to begin of the word and select |
| `ctrl right` | go to end of the word |
| `ctrl shift right` | go to end of the word and select |
| `pos1` | go to begin of the line |
| `shift pos1` | go to begin of the line and select |
| `ctrl pos1` | go to begin of the file |
| `ctrl shift pos1` | go to begin of the file and select|
| `end` | go to end of the line |
| `shift end` | go to end of the line and select |
| `ctrl end` | go to end of the file |
| `ctrl shift end` | go to end of the file and select|
| `ctrl down` | scroll the view for one line down |
| `ctrl up` | scroll the view for one line up |
| `shift down` | go one line down and select |
| `shift up` | go one line up and select |
| `pgUp` | go up one page or to begin of the view |
| `shift pgUp` | go up one page or to begin of the view and select |
| `pgDown` | go down one page or to the end of the view|
| `shift pgDown` | go down one page or to the end of the view and select |
| `ctrl a` | select all content |
| `ctrl c` | copy selection to cache |
| `ctrl x` | cut selection to cache |
| `ctrl v` | paste from cache |
| `ctrl f` | find |
| `ctrl z` | undo last action |

## GIT COMMANDS

| command | effect |
| --- | --- |
| `git clone _url_` | erstellt eine lokale Kopie von einem Online-Repository |
| `git add .` | fügt alle Änderungen zum Stage hinzu |
| `git commit -m "_message_"` | trägt alles aus dem Stage in die lokale Kopie vom Repository ein und fügt diesem Eintrag eine Beschreibung hinzu |
| `git pull` | lädt die aktuelle Version von dem Online-Repository runter |
| `git push`  | lädt die aktuelle Version von dem lokalen Repository hoch |
| `git keep` | um auch leere Ordner ohne Dateien dem Repo hinzuzufügen |

[git homepage](https://git-scm.com)

## VSCODE SHORTCUTS

| shortcut | effect |
| --- | --- |
| `ctrl l` | select line |
| `shift alt up/down` | duplicate line or selection |
| `ctrl c ctrl v` | duplicate line |
| `alt up/down` | move line or selection |
| `shift alt cursor` | edit many lines |
| `ctrl leftclick` | go to definition |
| `ctrl ö` | open terminal |
| `ctrl space` | force intellisense |
| `shift alt a` | comment / uncomment |
| `ctrl #` | comment / uncomment |
| `shift alt f` | format |
| `ctrl k s` | save all |
| `alt b` | open in browser |
| `f12` | go to definition |
| `ctrl +` | zoom in |
| `ctrl -` | zoom out |
| `ctrl shift p` | show all commands |

## VSCODE EXTENSION ES SNIPPETS

| snippet | effect |
| --- | --- |
| `clo` | console.log('object : ', object) |
| `clg` | console.log(object) |

## HTML SYNTAX

```html
<openingtag attributename=attributevalue> content to render in this tag </closingtag>
```

oder

```html
<openingtag attributename="attributevalue"> content to render in this tag </closingtag>
```

## CSS SYNTAX

```css
selectors {
    property: value;
    property: value;
}
```

## JS SYNTAX

Funktionen

```js
function _fctName_() {}
```

for-Schleife

```js
for (iterator; bedingung; aktualisierung; ) {
    anweisung;
    anweisung;
}
```

## EMMET CSS SNIPPETS

| snippet | effect |
| --- | --- |
| pos:s | position: static |
