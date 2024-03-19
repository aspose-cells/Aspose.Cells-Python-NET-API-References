---
title: calculate_array_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula {#str-aspose.cells.CalculationOptions}
Berechnet eine Formel als Arrayformel.



```python
def calculate_array_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zur Berechnungsformel|


##  calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}
Berechnet eine Formel als Arrayformel.


###  Kehrt zurück

Berechnetes Formelergebnis.


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zur Berechnungsformel|
| max_row_count | int | die maximale Zeilenanzahl der resultierenden Daten.<br/> Wenn es nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Zeilenanzahl verwendet.|
| max_column_count | int | die maximale Spaltenanzahl der resultierenden Daten.<br/> Wenn es nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Spaltenanzahl verwendet.|
###  Bemerkungen

Die Formel wird als dynamische Array-Formel zur Berechnung der Dimension und des Ergebnisses verwendet.
Die vom Benutzer angegebene maximale Dimension wird in Fällen verwendet, in denen das berechnete Ergebnis ein großer Datensatz ist
(Das berechnete Ergebnis kann beispielsweise den Daten einer ganzen Zeile oder Spalte entsprechen.)
Der Benutzer benötigt jedoch kein so großes Array entsprechend den Geschäftsanforderungen oder aus Leistungsgründen.

##  calculate_array_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Berechnet eine Formel als Arrayformel.


###  Kehrt zurück

Berechnetes Formelergebnis.


```python
def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel|
| c_opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zur Berechnungsformel|
| base_cell_row | int | Der Zeilenindex der Basiszelle.|
| base_cell_column | int | Der Spaltenindex der Basiszelle.|
| max_row_count | int | Die maximale Zeilenanzahl der resultierenden Daten.<br/> Wenn es nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Zeilenanzahl verwendet.|
| max_column_count | int | Die maximale Spaltenanzahl der resultierenden Daten.<br/> Wenn es nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Spaltenanzahl verwendet.|
| calculation_data | [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata) | Die Berechnungsdaten. Es wird für die Situation verwendet<br/>Dieser Benutzer muss einige statische Formeln berechnen, wenn er eine benutzerdefinierte Berechnungs-Engine implementiert.<br/>Für eine solche Situation muss der Benutzer dies mit den bereitgestellten Berechnungsdaten angeben<br/> für [`AbstractCalculationEngine.calculate`](/cells/python-net/de/aspose.cells/abstractcalculationengine/calculate).|
###  Bemerkungen

Die Formel wird als dynamische Array-Formel zur Berechnung der Dimension und des Ergebnisses verwendet.
Die vom Benutzer angegebene maximale Dimension wird in Fällen verwendet, in denen das berechnete Ergebnis ein großer Datensatz ist
(Das berechnete Ergebnis kann beispielsweise den Daten einer ganzen Zeile oder Spalte entsprechen.)
Der Benutzer benötigt jedoch kein so großes Array entsprechend den Geschäftsanforderungen oder aus Leistungsgründen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
