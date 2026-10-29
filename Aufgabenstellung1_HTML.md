# Aufgabe 1: HTML - Steckbrief gestalten

## 1. Steckbrief gestalten

In dieser Aufgabe kreierst du **deinen eigenen Steckbrief**. Dazu nutzt du die Programmiersprache HTML, mit der auch Webseiten im Internet erstellt werden. Du kannst zum Beispiel deine Hobbys vorstellen, was für Musik du gerne hörst, oder sonst etwas über dich erzählen. Was genau du in deinen Steckbrief einbauen möchtest, kannst du selbst entscheiden.

Wie bereits erwähnt, wirst du für diese Aufgabe HTML nutzen. Webseiten verwenden heutzutage meist mehrere Sprachen die jeweils einen eigenen Zweck haben.

### 1.1 Überblick der Programmiersprachen im Web

- **HTML**: Diese Sprache wird verwendet um zu definieren, welche Elemente auf einer Website vorhanden sind (z.B. Text, Bilder) und um das Layout, also den Aufbau, zu beschreiben.

- **CSS**: Diese Sprache wird verwendet um das Design einzelner Elemente festzulegen. Damit kann man beispielsweise einstellen, welche Farbe, Grösse, Schriftart und Positionierung ein bestimmter Text haben soll.

- **JavaScript**: Diese Sprache wird dazu verwendet, um Elemente auf einer Webseite interaktiv zu machen. Wenn man zum Beispiel einen Button erstellen möchte, der eine Konfetti-Animation abspielt wenn man draufklickt, dann verwendet man dafür JavaScript.


### 1.2 HTML Basics

HTML besteht aus **Tags**. Ein Tag sagt dem Browser, was für ein Element auf der Seite angezeigt werden soll. Die meisten Tags haben einen Anfang und ein Ende:

```html
<p>Das ist ein Text.</p>
```

- `<p>` ist der **Start-Tag**.
- `</p>` ist der **End-Tag** (mit einem `/`).
- Dazwischen steht der **Inhalt**.

#### Aufbau einer HTML-Seite

Jede HTML-Seite hat dieselbe Grundstruktur:

```html
<html>
  <head>
    <title>Mein Steckbrief</title>
  </head>
  <body>
    <h1>Hallo, ich bin Anna!</h1>
    <p>Ich spiele gerne Fussball.</p>
  </body>
</html>
```

- `<head>`: Infos über die Seite, die man nicht direkt sieht. Der `<title>` ist der Name, der oben im Browser-Tab steht.
- `<body>`: Alles, was du auf der Seite sehen kannst.

#### Wichtige Tags für deinen Steckbrief

| Tag | Was macht er? | Beispiel |
|-----|---------------|----------|
| `<h1>` bis `<h6>` | Überschriften (`h1` = gross, `h6` = klein) | `<h1>Über mich</h1>` |
| `<p>` | Absatz (normaler Text) | `<p>Ich heisse Noel.</p>` |
| `<b>` | **Fetter** Text | `<b>wichtig</b>` |
| `<i>` | *Kursiver* Text | `<i>schräg</i>` |
| `<br>` | Zeilenumbruch (kein End-Tag nötig) | `Zeile 1<br>Zeile 2` |
| `<img>` | Bild einfügen | `<img src="bild.jpg" width="200">` |
| `<ul>` und `<li>` | Liste mit Punkten | siehe unten |
| `<a>` | Link zu irgendeiner Webseite | `<a href="https://www.google.ch">Google</a>` |

**Beispiel für eine Liste (z.B. Hobbys):**

```html
<ul>
  <li>Fussball</li>
  <li>Gamen</li>
  <li>Musik hören</li>
</ul>
```

#### Bilder einfügen

Mit `<img>` kannst du ein Bild anzeigen. Nach `src=` schreibst du den Dateinamen oder den Pfad des Bildes.

#### Kommentare

Mit einem Kommentar kannst du dir im HTML-Code Notizen machen. Der Browser zeigt sie nicht an:

```html
<!-- Das ist ein Kommentar -->
```

---

> #### Tipps
>
> - Vergiss den End-Tag nicht (`</p>`, `</h1>` usw.).
> - Speichere deine Datei mit der Endung `.html` (z.B. `steckbrief.html`).
> - Öffne die Datei im Browser, um dein Ergebnis zu sehen. Nach jeder Änderung speichern und die Seite neu laden.

### 1.3 Jetzt bist du dran

Probiere die HTML-Tags aus und erstelle eine kleine Webseite. Beginne mit der Grundstruktur aus dem Beispiel in Kapitel 1.2. Füge eine Überschrift, einen Absatz und eine Liste ein. Öffne die Datei im Browser und prüfe, ob alles richtig angezeigt wird. Ergänze danach weitere Elemente, zum Beispiel ein Bild oder einen Link.

