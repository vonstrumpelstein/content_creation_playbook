[README.md](https://github.com/user-attachments/files/33003305/README.md)
# Content-Prozess im KI-Zeitalter

Einseitige Lern-Website zum Modul *Content Creation & Performance*. Sie fasst den Content-Prozess in fünf Schritten zusammen, stellt Adobe-Tools und kostenlose KI-Alternativen gegenüber und zeigt typische Probleme aus der Praxis mit Lösungswegen.

**Live-Version:** https://claude.ai/artifact/2N2nMaTQzVCnDtsbH2X9tg

## Inhalt

| Bereich | Beschreibung |
| :--- | :--- |
| **Hero** | Titel und kurze Einführung |
| **Prozess** | Planung, Erstellung, Distribution, Analyse, Optimierung als Karten |
| **Tool-Landkarte** | Tabelle: Adobe CC vs. Gratis-/KI-Alternativen nach Disziplin |
| **Problem-Landkarte** | Drei aufklappbare Probleme mit *Erkennen*, *Prüfen*, *Lösen* |

## Dateien

```
content-prozess-ki.html   # komplette Website (HTML, CSS in einer Datei)
README.md                 # diese Datei
```

## Nutzung

**Lokal ansehen:** `content-prozess-ki.html` per Doppelklick im Browser öffnen. Es wird nichts installiert, und es gibt keine externen Abhängigkeiten, Schriften oder Skripte.

**Veröffentlichen:** Die Datei lässt sich ohne Anpassung bei jedem statischen Hoster ablegen, zum Beispiel GitHub Pages, Netlify oder dem eigenen Webspace. Für den Startseiten-Aufruf die Datei am besten in `index.html` umbenennen.

## Anpassen

- **Texte:** Direkt im HTML ändern. Jeder Prozessschritt ist ein `<div class="step">`, jede Tabellenzeile ein `<tr>`, jedes Problem ein `<details>`-Block.
- **Neues Problem ergänzen:** Einen bestehenden `<details>`-Block kopieren und Titel sowie die drei Zeilen (`lbl l1`, `l2`, `l3`) austauschen.
- **Farben:** Im `<style>`-Bereich unter `:root` stehen alle Farben als Variablen (`--accent`, `--accent2`, `--bg` usw.). Für den Dunkelmodus gibt es einen zweiten Satz in `@media (prefers-color-scheme: dark)`. Beide Sätze anpassen.
- **Schrift:** Überschriften nutzen Georgia, der Fließtext die Systemschrift. Änderung über `font-family` in `body` und `h1`/`h2`.

## Technische Hinweise

- Responsives Layout, die Tabelle scrollt auf kleinen Bildschirmen seitlich.
- Automatischer Hell-/Dunkelmodus nach Systemeinstellung.
- Aufklappbare Bereiche über natives `<details>`, daher ohne JavaScript und per Tastatur bedienbar.
- Sanftes Scrollen zu den Abschnitten über die Navigation.

## Quelle

Inhalte stammen aus den Vorlesungs- und Tutoriumsunterlagen zu *Content Creation & Performance*. Die Quellenverweise aus der Vorlage wurden für die Website entfernt.
