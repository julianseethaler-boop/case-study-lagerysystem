# Case Study – Analyse eines Lagersystems

Dieses Projekt analysiert historische Bestell- und Produktdaten, um die Eignung von Artikeln für ein Shuttle-Lagersystem zu bewerten und die erforderliche Systemleistung abzuleiten.

## Ziel der Analyse

- Klassifizierung der Artikel nach Systemtauglichkeit
- Analyse der Bestelldaten zur Ermittlung der Systemlast
- Ableitung der benötigten Systemleistung (Systempicks pro Stunde)
- Abschätzung der benötigten Outbound-Stationen

## Datengrundlage

Der Datensatz enthält:

- **Bestelldaten**: Historische Bestellpositionen
- **Artikelstammdaten**: Informationen zu Größe, Gewicht und Artikelnummern

Die Daten umfassen **14 aufeinanderfolgende Geschäftstage**.

## Methodik

Die Analyse wurde in **Python mit Jupyter Notebook** umgesetzt und umfasst:

- Datenaufbereitung und -bereinigung
- Klassifizierung der Artikel nach Systemtauglichkeit
- Berechnung der Systempicks
- Analyse der Systemlast im Tagesverlauf
- Statistische Auswertung (Minimum, Median, Q75, Maximum)
- Ableitung der erforderlichen Systemleistung
- Analyse der benötigten Outbound-Stationen

## Verwendete Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Zentrale Ergebnisse

- ca. **83 % der Artikel sind für das Lagersystem geeignet**
- durchschnittliche Systemlast: **≈ 13.764 Systempicks pro Tag**
- empfohlene Systemleistung: **≈ 854 Systempicks pro Stunde**

Weitere Details zur Analyse befinden sich im Notebook sowie in der Präsentation.
