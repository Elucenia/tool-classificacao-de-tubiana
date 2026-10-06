<!-- ELUCENIA technical documentation · classificacao-de-tubiana · de · no clinical/professional/rights approval -->

# Tubiana-Klassifikation (Dupuytren)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/classificacao-de-tubiana)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Streckdefizit des MCP-Gelenks (Metakarpophalangealgelenk)

`mcf`

Grad · Bereich: 0–120

### Streckdefizit des PIP-Gelenks (proximales Interphalangealgelenk)

`ifp`

Grad · Bereich: 0–130

### Streckdefizit des DIP-Gelenks (oder Überstreckung)

`ifd`

Grad · Bereich: 0–100

### Ist ein Knoten oder Strang tastbar?

`nodulo`

- `0` — Nein
- `1` — Ja

## Fassung der Methode

Tubiana 1986: Gesamtstreckdefizit, Klassen 0/N/I–IV, Grenzen 45/90/135 Grad

## Dokumentierte Formel

Gesamtdefizit des Fingerstrahls = Streckdefizit MCP + PIP + DIP (DIP-Überstreckung zählt als Defizit). Stadien: 0 keine Läsion; N Knoten ohne Kontraktur; 1 bis 45°; 2 45–90°; 3 90–135°; 4 über 135°.

## Grenzen und Population

Die Tubiana-Klassifikation 1986 beschreibt Dupuytren-Deformitäten je Fingerstrahl und sieht ergänzende Angaben zu Daumen, erstem Zwischenfingerraum, Haut und postoperativer Steifigkeit vor. Das gesamte Streckdefizit allein bildet diese vollständige Bewertung nicht ab. Schwellen und Konventionen der verwendeten Version müssen im vollständigen Artikel geprüft werden.

## Referenzen

- [Tubiana R. Evaluation des déformations dans la maladie de Dupuytren (Evaluation of deformities in Dupuytren disease). Ann Chir Main, 1986.](https://doi.org/10.1016/s0753-9053(86)80043-6)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Stadium 1: gesamtes Defizit von 0 bis 45°

| Ergebnisdetails | |
| --- | --- |
| Gesamtes Extensionsdefizit | 30° |

MCF-Kontraktur ≥ 30° oder jede IP-Kontraktur: klassische Behandlungsindikation (Hueston-Kriterium).


### 2

Stadium 2: gesamtes Defizit von 45 bis 90°

| Ergebnisdetails | |
| --- | --- |
| Gesamtes Extensionsdefizit | 90° |

MCF-Kontraktur ≥ 30° oder jede IP-Kontraktur: klassische Behandlungsindikation (Hueston-Kriterium).


### 3

Stadium 4: gesamtes Defizit über 135°

| Ergebnisdetails | |
| --- | --- |
| Gesamtes Extensionsdefizit | 150° |

MCF-Kontraktur ≥ 30° oder jede IP-Kontraktur: klassische Behandlungsindikation (Hueston-Kriterium).


### 4

Stadium N: Knoten oder Strang ohne Kontraktur

| Ergebnisdetails | |
| --- | --- |
| Gesamtes Extensionsdefizit | 0° |

