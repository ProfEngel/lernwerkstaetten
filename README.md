# Lernwerkstätten

Sammlung interaktiver, browserbasierter Lernwerkstätten für Kinder. Die Materialien sind als eigenständige Webseiten angelegt und über GitHub Pages direkt und barrierefrei im Browser nutzbar (auch offline-fähig als PWA auf Tablets/iPads).

## Aktuell enthalten

### Mathe- & Lern-Werkstatt (Klasse 2–3)

Eine didaktisch aufbereitete Lernwerkstatt mit **fünf Lernbereichen** und **interaktiven 5er-Übungs-Nuggets**:

- **🕰️ Lern-Uhr:**
  - Analoge und digitale Uhr synchron einstellen
  - Farbige Stundensektoren und Umgangssprache (z. B. „Viertel vor vier“)
  - Zeitsprünge (+15m, +30m, +45m, +1h) und variable Animationsgeschwindigkeiten
  - **🎯 5 Übungs-Nuggets:** Zufällige Aufgaben zum Ablesen von Mini-Uhren, Zeitspannen vor- und rückwärts, Minutendauer und digitaler Übersetzung

- **💶 Euro & Cent:**
  - Realistischer Kaufladen mit Produkten von 0,30 € bis 19,50 €
  - Modi für *Bezahlen* und *Wechselgeld herausgeben*
  - Drei Schwierigkeitsstufen (Glatt/50c, 10er-Cent, krumme Cent-Beträge)
  - Interaktives Portemonnaie mit Münzen und Scheinen
  - **🎯 5 Übungs-Nuggets:** Aufgaben zu Einkaufssummen, Kassenwechselgeld, Zählen von Spardosen-Münzen und Sparzielen

- **➕➖ Plus & Minus (bis 100):**
  - Halbschriftliche Addition und Subtraktion mit Zehnerübergang
  - Interaktive **100er-Tafel** mit Froschsprung und Wegmarkierung
  - **Säckchen & Murmeln** zur Bündelung / Entbündelung von Zehnern
  - **Rechenleiste** mit Sprungbögen
  - **🎯 5 Übungs-Nuggets:** Zufällige Aufgaben mit Zehnerübergang, Eingabefeldern und schrittweiser Rechenweg-Auflösung

- **✖➗ Mal & Geteilt:**
  - Multiplikation und Division (mit und ohne Rest)
  - Anschauliches **Kekse-Backblech & Tellern**
  - **Punktefeld** mit Sonnenbrücke (z. B. Aufteilung in 5er- und 10er-Blöcke)
  - **Zahlenstrahl** mit Vielfachen-Bögen
  - **🎯 5 Übungs-Nuggets:** Einmaleins- und Divisionsaufgaben mit Rest-Eingabe und ausführlichem Rechenweg

- **🏰 Rechnen bis 1000 (Neu):**
  - **🏺 100er-, 10er- und 1er-Töpfe:** Farbcodiert nach dem Montessori-Standard:
    - 🔴 **100er-Topf (Rot):** Hunderter-Platten (H)
    - 🔵 **10er-Topf (Blau):** Zehner-Stangen (Z)
    - 🟢 **1er-Topf (Grün):** Einer-Würfel (E)
    - Mit animierter Bündelung (10 Einer werden zu 1 Zehner, 10 Zehner zu 1 Hunderter) und Entbündelung bei Subtraktion
  - **🔢 Tausendertafel (Immer vollständig 1–1000 & Einzel-Fokus auf Wunsch):**
    - **Vollständige Ansicht (Standard):** Alle 10 Hunderter-Felder (1–1000) gleichzeitig im Überblick mit lückenloser Pfadverfolgung des Frosches.
    - **Einzel-Hunderter (Fokus-Ansicht):** Auf Wunsch kann jedes Hunderterfeld groß im Fokus betrachtet und durchgeschaltet werden.
  - **📏 Zahlenstrahl bis 1000:** Didaktische Sprungbögen für Hunderter (Rot), Zehner (Blau) und Einer (Grün)
  - **🎯 5 Übungs-Nuggets:** 5 zufällige 3-stellige Rechnungen mit Stellenwert-Eingabe, „Prüfen & Lösen“, didaktischem Schritt-für-Schritt Lösungsweg, Sternen und Audiofeedback

## Didaktisches Konzept der 5 Übungs-Nuggets

In jedem der 5 Module können Kinder über den Reiter **🎯 5 Übungs-Nuggets** selbstständig trainieren:
1. Kinder tragen ihre Lösungen in kindgerechte Eingabefelder ein.
2. Ein Klick auf **✨ Prüfen & Lösen** prüft alle Aufgaben auf einen Schlag:
   - Richtig gelöste Aufgaben leuchten grün auf (✅) und vergeben Sterne ⭐.
   - Werden alle 5 Aufgaben richtig gelöst, ertönt ein Erfolgs-Jingle mit buntem Konfetti-Feuerwerk.
   - Jede Aufgabe blendet ihren didaktischen Schritt-für-Schritt Rechenweg ein, sodass Fehler sofort verstanden werden.
3. Über **🎲 Neue Aufgaben** kann beliebig oft ein neuer Aufgabensatz generiert werden.

## Aufrufen & Nutzen

Die Lernwerkstatt ist online erreichbar unter:

<https://profengel.github.io/lernwerkstaetten/>

- **Tablet-optimiert:** Große Touch-Flächen, kindgerechte Typografie und intuitive Bedienung.
- **Audio & Sterne:** Ton kann jederzeit über den Lautsprecher-Button an- oder ausgeschaltet werden. Gesammelte Sterne motivieren beim Üben.
- **Offline-fähig:** Dank integriertem Service Worker kann die Seite auf Tablets / iPads zum Homescreen hinzugefügt werden und funktioniert ohne Internetverbindung.

## Lokal ansehen

Einfach `index.html` direkt im Browser öffnen. Kein Build-Schritt oder Webserver erforderlich.

## Veröffentlichung

GitHub Actions veröffentlicht den Inhalt des Hauptbranches (`main`) automatisch via GitHub Pages (`.github/workflows/pages.yml`).
