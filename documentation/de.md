<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · de · no clinical/professional/rights approval -->

# Absolute Neutrophilenzahl

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/contagem-absoluta-de-neutrofilos)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Gesamtleukozytenzahl

`leuco`

/µL · Bereich: 10–500000

### Segmentkernige neutrophile Granulozyten

`seg`

% · Bereich: 0–100

### Stabkernige neutrophile Granulozyten (optional)

`bast`

% · optional · Bereich: 0–100

## Fassung der Methode

ANC: Leukozyten×(Segmentkernige+Stabkernige)/100; IDSA Aktualisierung 2010/Veröffentlichung 2011

## Dokumentierte Formel

Absolute Neutrophilenzahl = Leukozyten (/µL) × (segmentkernige % + stabkernige Neutrophile %) ÷ 100.

## Grenzen und Population

IDSA 2010/2011 behandelt Fieber und chemotherapiebedingte Neutropenie bei Krebspatienten mit einer Einteilung nach Zeichen und Symptomen, Krebs, Therapie und Begleiterkrankungen. Der berechnete Absolutwert ersetzt diese Beurteilung nicht. Definitionsschwellen und Einheiten müssen in der vollständigen Leitlinie geprüft werden; das gelesene Abstract nennt sie nicht.

## Referenzen

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

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
