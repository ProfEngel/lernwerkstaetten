# Lernwerkstätten

Sammlung interaktiver, browserbasierter Lernwerkstätten für Kinder. Die Materialien sind als eigenständige Webseiten angelegt und sollen über GitHub Pages einfach erreichbar sein.

## Aktuell enthalten

---

### ⚽ TSV Plattenhardt – Interaktive Fußball-Taktiktafel

**🔗 [Zur Taktiktafel → https://profengel.github.io/lernwerkstaetten/fussball-taktik/](https://profengel.github.io/lernwerkstaetten/fussball-taktik/)**

Eine vollständige, interaktive Taktiktafel speziell für den **Juniorinnen-Fußball** (TSV Plattenhardt). Entwickelt für Trainerinnen, Trainer und Spielerinnen – nutzbar direkt auf dem Sportplatz, auch **ohne Internetverbindung**.

**Wofür ist das gut?**

- 📋 **Trainer-Modus:** Zeigt taktische Abläufe wie die Vereinsphilosophie „Immer die 6 suchen", Verschieben, Pressing und typische Fehler (z. B. LV rennt blind vor) als animierte Simulation.
- 👧 **Kids-Modus:** Erklärt den Spielerinnen die zwei goldenen Regeln (Groß machen / Eng machen) und Kommunikation auf dem Platz (Rufen, Schulterblick) auf einfache, kindgerechte Weise.
- 🎮 **Freispiel-Modus:** Spielerinnen und Trainer können selbst Pässe spielen – die App prüft automatisch ob der Pass ins **Abseits** geht oder ob die Empfängerin **gedeckt** ist.
- 🔵 **Abseits-Linie:** Optional einblendbar – berechnet automatisch die korrekte Abseitsposition anhand des vorletzten Gegners.
- 🔺 **Deckungskegel:** Zeigt den Deckungsbereich jedes Gegners als visuellen Kegel – ideal um taktische Räume zu erkennen.
- 📐 **Formationen:** 3-1-3-1, 3-3-2 (9er-Feld) sowie 4-3-3 und 4-2-3-1 (11er-Feld) als animierte Aufstellung.
- ❓ **Hilfe-Button:** Vollständige Erklärung aller Taktikbegriffe, Regeln und Bedienhinweise direkt in der App.

**Technisch:**
- Läuft direkt im Browser, keine Installation nötig
- **Offline-fähig (PWA):** Einmal mit WLAN geöffnet → danach auf dem Sportplatz ohne Internet nutzbar
- Optimiert für iPad, iPhone und Android-Tablets im Querformat
- Als App auf dem Home-Bildschirm installierbar (Vollbild, ohne Browser-Leiste)

> **📱 Als App installieren (offline nutzbar):**
> - **iPhone/iPad:** Safari → Teilen ↑ → „Zum Home-Bildschirm" → Hinzufügen
> - **Android:** Chrome → Menü ⋮ → „App installieren"
>
> Nach der Installation funktioniert die Taktiktafel auch ohne WLAN – perfekt für den Sportplatz!

---

### Mathe- & Lern-Werkstatt

**🔗 [Zur Lernwerkstatt → https://profengel.github.io/lernwerkstaetten/](https://profengel.github.io/lernwerkstaetten/)**

Eine Lernwerkstatt für die 2.–3. Klasse mit vier Bereichen:

- **Lern-Uhr:** analoge und digitale Uhr, Zeit einstellen und Zeitspannen erkunden
- **Euro & Cent:** Einkaufen, Bezahlen und Wechselgeld mit unterschiedlich schwierigen Aufgaben
- **Plus & Minus:** Rechenwege mit Hundertertafel, Säckchen und Rechenleiste nachvollziehen
- **Mal & Geteilt:** Aufgaben mit anschaulichen Darstellungen wie Backblech, Punktefeld und Zahlenstrahl lösen

Die Seite ist für Tablets und kleinere Bildschirme gestaltet. Sie benötigt keine Installation und läuft direkt im Browser. Ton kann ein- und ausgeschaltet werden. Eine verlässliche Offline-Nutzung ist derzeit nicht gewährleistet.

---

## Aufrufen

| Lernwerkstatt | Link |
|---|---|
| ⚽ TSV Taktiktafel | https://profengel.github.io/lernwerkstaetten/fussball-taktik/ |
| 📐 Mathe-Werkstatt | https://profengel.github.io/lernwerkstaetten/ |

## Lokal ansehen

`index.html` direkt in einem aktuellen Browser öffnen. Für den normalen Gebrauch ist kein Build-Schritt erforderlich.

## Weitere Lernwerkstätten ergänzen

Neue Materialien können als eigene Unterordner (zum Beispiel `lesen/` oder `sachunterricht/`) mit jeweils einer `index.html` hinzugefügt werden. Verlinkungen zur Sammlung können später auf einer Startseite ergänzt werden.

## Veröffentlichung

GitHub Actions veröffentlicht den Inhalt des Hauptbranches automatisch mit GitHub Pages. Die Workflow-Datei liegt unter `.github/workflows/pages.yml`.
