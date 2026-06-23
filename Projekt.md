# Hausübung: Global Bike Website (HTML5 & CSS3)

> Anleitung für Claude Code. Ziel ist es, eine vollständige Beispiel-Website
> "Global Bike" mit HTML5 und CSS3 zu erstellen. Die Originalübung nutzt
> Microsoft Expression Web – das brauchen wir hier nicht. Wir bauen die
> Dateien direkt im Editor / mit Claude Code.

## Projektstruktur

Lege folgende Struktur an:

```
Website<DeinNachname>/
├── default.html
├── styles.css
└── img/
    ├── racing-bike.jpg
    ├── city-bike.jpg
    ├── touring-bike.jpg
    ├── radhandschuhe.jpg
    ├── radhelm.jpg
    ├── radkorb.jpg
    ├── radschloss.jpg
    ├── radtaschen.jpg
    ├── GlobalBike_header.jpg
    └── footer.jpg
```

> ⚠️ **Wichtig – manuell zu erledigen:** Die 10 Bilder im `img/`-Ordner musst
> du selbst aus dem Moodle-Kurs (Bereich "HTML-Übung 1", Ordner "Vorlagen/img")
> herunterladen und in den `img/`-Ordner kopieren. Claude Code kann diese
> Bilder nicht beschaffen. Lege den Ordner an und füge sie ein, bevor du die
> Seite im Browser prüfst.

## Namensregeln (vom Aufgabenblatt)

Beim Benennen von Ordnern/Dateien beachten:
- keine Leerzeichen
- keine Sonderzeichen ($, &, /)
- keine Satzzeichen (Komma, Punkt)
- erlaubt: Trennstriche (-) und Unterstriche (_)
- Groß-/Kleinschreibung wird unterschieden

---

## Aufgabe 1–4: HTML-Grundgerüst (`default.html`)

Erstelle `default.html` als HTML5-Dokument mit:
- `<title>` = **Global Bike – Homepage** (direkt vor `</head>`)
- Im `<body>` die folgenden Struktur-Tags in dieser Reihenfolge:
  `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`.

## Aufgabe 5–6: Texteingabe in `<main>`

Folgende Texte zwischen `<main>` und `</main>` einfügen (zunächst als reiner
Text, Formatierung folgt in Aufgabe 7):

**Einleitung:**
> Global Bike - Fahrräder für jede Gelegenheit, egal ob Racing, Touring oder City Bike.

**Über uns:** Global Bike ist einer der führenden Anbieter von Fahrrädern für
alle Gelegenheiten. Unser Sortiment bedient sowohl alle Rennsportler sowie den
gemütlichen Radfahrer mit gehobenen und höchsten Ansprüchen. Neben einem
schicken Design legen wir bei der Sortimentsauswahl vor allem viel Wert auf
eine ausgewogene Zusammenstellung der technischen Komponenten. So überzeugen
die Bikes nicht nur durch einen fairen Preis, sondern auch mit ausgezeichneten
Fahreigenschaften und viel Fahrvergnügen. Im Vordergrund steht bei uns die
Kundenzufriedenheit. Sie können sich auf eine bedarfsgerechte Beratung
verlassen, bei der Sie garantiert das für Sie passende Fahrrad finden. Wir
beantworten fachkompetent Fragen rund um das Fahrrad.

**Hochleistung für Rennsportler: Racing Bike** – Unsere Racing Bikes sind für
lange Strecken mit hohem Tempo konstruiert. Der Bügellenker ermöglicht es
während der Fahrt verschiedene Griffpositionen und Sitzwinkel einzunehmen.
Racing Bike bedeutet die Reinform eines Fahrrades – kompromisslos auf Effizienz
und Geschwindigkeit getrimmt. Leistungssportler werden das geringe Gewicht
schätzen – hier ist nur verbaut, was wirklich nötig ist. Hochwertige
Komponenten schaffen beste Voraussetzungen für den Wettkampf gegen die Uhr.
Einfaches Handling und robuste Fahreigenschaften sind wesentliche Merkmale
dieses Rennrades. Die Verwendung von kohlenstofffaserverstärktem Kunststoff und
hochfestem Leichtmetall sorgen für außergewöhnlich geringes Gewicht.
Gleichzeitig wird ein Höchstmaß an Stabilität und Sicherheit gewährleistet.
Selbst Einsteiger erhalten hier ein ideales Sportgerät, um Gefühl für die
Anforderungen des Rennsports zu entwickeln und grundlegende Erfahrungen zu
sammeln.

**Perfekt für die Stadt: City Bike** – Das City Bike bietet ein bequemes und
sicheres Auf- und Absteigen. Begünstigt durch ein hochgezogenes Steuerlager und
den etwas geschwungenen Lenker, ermöglicht dieses Fahrrad eine aufrechte, sowie
nackenschonende Sitzposition. Alle Cityräder verfügen über eine hochwertige
Schaltung mit geringem Wartungsaufwand und einer einfachen Bedienung. Um das
komfortable Fahrgefühl weiter zu unterstützen sind unsere City Bikes gefedert.
Hierbei werden Federgabeln (für Handgelenke, Schulter und Nacken) und gefederte
Sattelstützen (für den Rücken) kombiniert. Die Ausstattung ist mit Lichtanlage,
Schutzblechen und Gepäckträger also ideal für den City Alltag. An den Rädern
lassen sich mühelos Körbe für den Einkauf montieren.

**Allrounder für weite Strecken: Touring Bike** – Wenn sie längere Strecken
zurücklegen wollen und in der Stadt wie auch auf unebenem Untergrund den vollen
Fahrkomfort genießen und dabei auch Ihre Arbeitstasche oder Gepäck
transportieren möchten, dann empfehlen wir Ihnen unser Touring Bike. Durch die
komplette StVZO-Ausstattung sind diese Räder die beste Symbiose aus
Alltagstauglichkeit und sportlichen Fahreigenschaften. Als Antrieb dient hier
eine 14-Gang Kettenschaltung mit geringem Wartungsaufwand und einer einfachen
Bedienung. Zur weiteren Ausstattung gehören Schutzbleche und ein stabiler
Gepäckträger. Die Sitzposition auf diesem Touring Bike ist moderat bis
sportlich und sorgt so für eine gute Kraftübertragung auf das Fahrrad. Sie
müssen sich vor Fahrtantritt keine bestimmte Strecke aussuchen. Ihr Touring
Bike fährt auch gerne abseits der Straße. Das heißt, wenn Sie einen schönen
Wald- oder Feldweg sehen, dann genießen Sie diesen! Eine Federgabel mit gutem
Ansprechverhalten dämpft dabei die Unebenheiten und Vibrationen ab.

## Aufgabe 7: Überschriften & Absätze formatieren

- Einleitungssatz → `<h1>`
- Diese vier als `<h2>`: `Über uns`, `Hochleistung für Rennsportler: Racing Bike`,
  `Perfekt für die Stadt: City Bike`, `Allrounder für weite Strecken: Touring Bike`
- Jeden zugehörigen Textblock in ein `<p>` setzen.

## Aufgabe 8: CSS-Datei einbinden

`styles.css` erstellen und im `<head>` **über** dem `<title>` einbinden:

```html
<link type="text/css" rel="stylesheet" href="styles.css"/>
```

## Aufgabe 9: Basisformatierungen (`styles.css`)

```css
body {
    max-width: 1080px;          /* max HD-Breite */
    margin-right: auto;          /* Inhalt zentrieren */
    margin-left: auto;           /* Inhalt zentrieren */
    font-family: Arial, Helvetica, Sans-Serif;
    font-size: medium;
    font-weight: normal;
    line-height: 1.8em;
}

h1 {
    font-family: Verdana;
    font-size: 20px;
    color: green;
    font-style: italic;
    padding-left: 10px;
}

h2 {
    font-size: 16px;
    color: white;
    height: 30px;
    padding-left: 5px;
    background-color: green;
}
```

## Aufgabe 10: Bilder in die Seite einfügen

Direkt hinter den jeweiligen `<p>`-Absatz von Racing/City/Touring einfügen:

```html
<img alt="Racing Bike"  src="img/racing-bike.jpg"  style="float: left"/>
<img alt="City Bike"    src="img/city-bike.jpg"    style="float: right"/>
<img alt="Touring Bike" src="img/touring-bike.jpg" style="float: left"/>
```

## Aufgabe 11: Bild-Styles

```css
main img {
    border-style: none;
    width: 30%;
    max-width: 100%;
    height: auto;
}
```

## Aufgabe 12: Header & Footer stylen

```css
header {
    background-image: url('img/GlobalBike_header.jpg');
    height: 100px;
    top: 0px;
    background-color: white;
    position: sticky;            /* bleibt oben "kleben" */
}

footer {
    margin-top: 50px;
    display: block;
    height: 75px;
    background-image: url('img/footer.jpg');
}
```

## Aufgabe 13: Navigationsmenü als Liste

In `<nav>`:

```html
<ul>
    <li>Home</li>
    <li>Produktkatalog</li>
    <li>Video</li>
</ul>
```

CSS:

```css
nav {
    background-color: darkseagreen;
    top: 100px;
    position: sticky;
}

nav ul {
    list-style: none;            /* keine Aufzählungszeichen */
}

nav li {
    font-size: large;
    font-weight: bold;
    display: inline;             /* horizontale Ausrichtung */
    margin-right: 65px;
    margin-bottom: 5px;
    padding-left: 10px;
}
```

## Aufgabe 14: Tabelle für Produktkatalog

Hinter dem letzten Absatz in `<main>`:

```html
<h2>Produktkatalog</h2>
```

Darunter eine Tabelle mit Kopfzeile (`Artikelbild`, `Beschreibung`, `Preis`),
**8 Datenzeilen** (je 3 Spalten) und einer Abschlusszeile:

```html
<tr>
    <td colspan="3">Alle Preise verstehen sich zzgl. der gültigen gesetzlichen MwSt.</td>
</tr>
```

CSS:

```css
table {
    width: 100%;
    border-style: outset;
    border: 8px double;
    border-color: darkslategrey;
}

th {
    font-family: "Courier New", Courier, Monospace;
    font-size: 18px;
    width: 33%;
    color: azure;
    background-color: darkseagreen;
    padding-top: 7px;
    padding-left: 5px;
}

td {
    font-size: medium;
    background-color: beige;
    padding-left: 5px;
}
```

### Tabelleninhalt – Spalte 1 (Bilder)

| Zeile | Bild |
|------|------|
| 1 | `<img alt="Racing Bike" src="img/racing-bike.jpg"/>` |
| 2 | `<img alt="City Bike" src="img/city-bike.jpg"/>` |
| 3 | `<img alt="Touring Bike" src="img/touring-bike.jpg"/>` |
| 4 | `<img alt="Handschuhe" src="img/radhandschuhe.jpg"/>` |
| 5 | `<img alt="Helm" src="img/radhelm.jpg"/>` |
| 6 | `<img alt="Korb" src="img/radkorb.jpg"/>` |
| 7 | `<img alt="Schloss" src="img/radschloss.jpg"/>` |
| 8 | `<img alt="Tasche" src="img/radtaschen.jpg"/>` |

Bild-CSS für die Tabelle:

```css
table img {
    width: 90%;
    max-width: 100%;
    height: auto;
    border-style: solid;
    border-width: 2px;
    border-color: darkseagreen;
    margin: 5px;
    padding: 2px;
}
```

### Tabelleninhalt – Spalte 2 (Beschreibung) & Spalte 3 (Preis)

| # | Beschreibung (Spalte 2) | Preis (Spalte 3) |
|---|---|---|
| 1 | `<p>Racing Bike</p><p>Gewicht: 7,9 kg<br>Gänge:20 <br>Reifengröße: 28"</p>` | 2200,- € |
| 2 | `<p>City Bike</p><p>Gewicht: 12,3 kg<br>Gänge: 30 <br>Reifengröße: 28"</p>` | 1400,- € |
| 3 | `<p>Touring Bike</p><p>Gewicht: 14,8 kg<br>Gänge: 24 <br>Reifengröße: 28"</p>` | 1700,- € |
| 4 | `<p>Handschuhe</p><p>Mit Verstärkungen an Handfläche und Daumen, wird zusätzliche Dämpfung und damit auch eine Entlastung der Handgelenke erreicht.</p>` | 55,- € |
| 5 | `<p>Fahrradhelm</p><p>Ein idealer Fahrradhelm mit optimaler Belüftung, maximalem Tragekomfort und Schutzwirkung.</p>` | 140,- € |
| 6 | `<p>Fahrradkorb</p><p>Der Fahrradkorb ist ein praktischer Korb für die Montage auf dem Gepäckträger deines Fahrrads.</p>` | 30,- € |
| 7 | `<p>Fahrradschloss</p><p>Das Stahlkabel Zahlenschloss bietet besseren Schutz gegen Durchschneiden oder Durchsägen.</p>` | 25,- € |
| 8 | `<p>Gepäckträgertaschen</p><p>Das Paar hochwertiger Gepäckträgertaschen zur einfachen Befestigung am Gepäckträger.</p>` | 185,- € |

## Aufgabe 15: YouTube-Video & weitere Liste im `<aside>`

```html
<h2>Der direkte Weg zu unserem Sortiment</h2>
<iframe src="https://www.youtube.com/embed/dtUDqpkUSbE" allowfullscreen></iframe>
<ul>
    <li>Racing Bike</li>
    <li>City Bike</li>
    <li>Touring Bike</li>
    <li>Produktkatalog</li>
</ul>
```

CSS:

```css
iframe {
    border: none;
    max-width: 100%;
    float: right;
    margin: 5px;
    padding: 5px;
}

aside ul {
    font-size: medium;
    margin-left: 15px;
    padding-left: 10px;
}
```

## Aufgabe 16: Bereiche segmentieren mit `<section>`

Jeden Block (ab `<h1>`/`<h2>` bis Abschnittsende) in eine `<section>` mit ID
fassen:

```html
<main>
    <section id="intro">  ... </section>   <!-- h1 + Über uns -->
    <section id="racing"> ... </section>
    <section id="city">   ... </section>
    <section id="touring"> ... </section>
    <section id="katalog"> ... </section>   <!-- Produktkatalog-Tabelle -->
</main>
<aside>
    <section id="video"> ... </section>
</aside>
```

## Aufgabe 17: Anker-/Hyperlinks

Navigation:

```html
<nav>
    <ul>
        <li><a href="default.html">Home</a></li>
        <li><a href="#katalog">Produktkatalog</a></li>
        <li><a href="#video">Video</a></li>
    </ul>
</nav>
```

Aside-Liste:

```html
<ul>
    <li><a href="#racing">Racing Bike</a></li>
    <li><a href="#city">City Bike</a></li>
    <li><a href="#touring">Touring Bike</a></li>
    <li><a href="#katalog">Produktkatalog</a></li>
</ul>
```

Die drei `<h2>`-Überschriften der Bikes mit Link auf den Katalog umschließen:

```html
<a href="#katalog"><h2>Hochleistung für Rennsportler: Racing Bike</h2></a>
<a href="#katalog"><h2>Perfekt für die Stadt: City Bike</h2></a>
<a href="#katalog"><h2>Allrounder für weite Strecken: Touring Bike</h2></a>
```

Link-CSS:

```css
a {
    text-decoration: none;
}

nav a:link    { color: navy; }
nav a:visited { color: white; }
nav a:hover   { color: green; background-color: white; }

aside a:link  { color: navy; text-decoration: underline; }
aside a:hover { background-color: green; color: white; text-decoration: none; }
```

## Aufgabe 18: Weitere Anpassungen (eigenständig)

1. Im Absatz "Perfekt für die Stadt: City Bike" nach jedem Satzpunkt einen
   `<br>` einfügen (jeder Satz in neuer Zeile).
2. Schriftfarbe der `<h1>`-Überschrift von Grün auf eine andere Farbe (z. B.
   Rot) ändern.
3. Hintergrundfarbe der Tabellen-`th` (Artikelbild/Beschreibung/Preis) auf die
   **gleiche** Farbe setzen, die in Punkt 2 gewählt wurde.
4. Den drei Bildern in den Absätzen Racing/City/Touring (`main img`) einen
   Rahmen mit frei wählbarer Farbe geben.
5. Schriftfarbe der Navigationsleiste von Schwarz auf Weiß ändern.
6. Den kompletten `aside`-Bereich mit einem gepunkteten oder gestrichelten
   Rahmen in Blau (o. ä.) umranden.
7. Den kompletten `footer`-Bereich mit einem violetten (o. ä.) Rahmen umranden.

---

## Hinweise für Claude Code

- Baue zuerst das vollständige HTML-Gerüst, dann die CSS-Datei – arbeite die
  Aufgaben in Reihenfolge ab, da spätere auf früheren aufbauen.
- Validiere am Ende, dass alle `id`-Anker (`#intro`, `#racing`, `#city`,
  `#touring`, `#katalog`, `#video`) existieren und die Links darauf zeigen.
- HTML5-Doctype: `<!DOCTYPE html>`, `lang="de"` am `<html>`-Tag, `charset=utf-8`.
- Die Bilder im `img/`-Ordner müssen vorhanden sein (manuell aus Moodle), sonst
  bleiben Header/Footer/Produktbilder leer.
- Zum Testen: `default.html` im Browser öffnen, Fensterbreite ändern und
  Sticky-Verhalten von Header/Nav prüfen.
