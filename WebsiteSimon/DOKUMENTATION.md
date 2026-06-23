# Dokumentation – Global Bike Website

Diese Datei erklärt den Aufbau von `default.html` und `styles.css`.

## Dateien

```
WebsiteSimon/
├── default.html   – Inhalt & Struktur (HTML5)
├── styles.css      – Layout & Design (CSS3)
└── img/            – Alle Bilder (Header, Footer, Produktbilder)
```

## default.html – Struktur

Die Seite folgt dem klassischen HTML5-Seitenlayout:

| Tag | Zweck |
|---|---|
| `<header>` | Logo/Banner-Bild, bleibt beim Scrollen oben kleben (`position: sticky`) |
| `<nav>` | Navigationsleiste mit Anker-Links, klebt direkt unter dem Header |
| `<main>` | Hauptinhalt, unterteilt in 5 `<section>`-Blöcke |
| `<aside>` | Seitenleiste mit YouTube-Video und Sprungmarken-Liste |
| `<footer>` | Abschlussbereich mit Hintergrundbild |

### Sections in `<main>` (jede mit eindeutiger ID)

- `#intro` – Einleitung (`<h1>`) und "Über uns" (`<h2>` + `<p>`)
- `#racing` – Racing Bike, Text + nach links gefloatetes Bild
- `#city` – City Bike, Text (mit `<br>` nach jedem Satz) + nach rechts gefloatetes Bild
- `#touring` – Touring Bike, Text + nach links gefloatetes Bild
- `#katalog` – Produkttabelle mit allen 8 Artikeln

Die IDs sind das Sprungziel für alle Anker-Links (`href="#katalog"` etc.).
Im `<aside>` liegt zusätzlich `#video` mit dem eingebetteten YouTube-Video.

### Warum `<a href="#katalog"><h2>...</h2></a>`?

Die drei Bike-Überschriften sind anklickbar und führen direkt zur Produkttabelle,
damit Besucher schnell vom Beschreibungstext zum Preis springen können.

### Die Produkttabelle

- Erste Zeile (`<th>`) = Kopfzeile: Artikelbild / Beschreibung / Preis
- 8 Datenzeilen, je 3 `<td>` (Bild, Beschreibung, Preis)
- Letzte Zeile nutzt `colspan="3"` für den MwSt.-Hinweis über die volle Breite

## styles.css – Design

| Bereich | Wichtige Regeln |
|---|---|
| `body` | Begrenzt Breite auf 1080px, zentriert den Inhalt, setzt Grundschrift |
| `h1` / `h2` | Einleitung rot/kursiv (`h1`), Zwischenüberschriften als grüne Balken (`h2`) |
| `main img` | Produktbilder in Sektionen: 30% Breite, roter Rahmen |
| `header` / `footer` | Hintergrundbilder, Header ist sticky |
| `nav` | Sticky direkt unter dem Header (`top: 100px`), horizontale Liste über `display: inline` |
| `table` / `th` / `td` | Tabellen-Look: dicker Rahmen außen, rote Kopfzeile, beige Datenzellen |
| `table img` | Kleinere Variante der Bilder speziell für die Tabelle |
| `iframe` | YouTube-Video rechtsbündig, ohne Rahmen |
| `aside` | Gepunkteter blauer Rahmen um die gesamte Seitenleiste |
| `a` / `nav a` / `aside a` | Linkfarben je nach Bereich (Navigation weiß, Aside navy mit Unterstreichung) |

### Wichtiger Stolperstein: Bilder über grünen Balken

Die Produktbilder in `#racing`, `#city`, `#touring` sind mit `float: left`/`float: right`
gesetzt, damit der Text um sie herumläuft. Ohne Gegenmaßnahme würde die nächste
`<h2>`-Leiste (grüner Balken) neben/über das noch "schwebende" Bild rutschen,
weil ein Float den normalen Element-Fluss verlässt.

**Lösung:** `h2 { clear: both; }` in `styles.css` zwingt jede Überschrift dazu,
unterhalb aller vorherigen Floats zu beginnen.

### Sticky Header + Nav

`header` und `nav` nutzen beide `position: sticky`. Der `top`-Wert bestimmt,
wo das Element beim Scrollen "einrastet":
- `header { top: 0px }` → klebt ganz oben
- `nav { top: 100px }` → klebt direkt unterhalb des 100px hohen Headers
