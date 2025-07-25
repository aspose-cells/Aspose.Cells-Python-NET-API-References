---
title: calculate_array_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Berechnet eine Formel als Matrixformel.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zum Berechnen der Formel|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Berechnet eine Formel als Matrixformel.


###  Kehrt zurück

Berechnetes Formelergebnis.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zum Berechnen der Formel|
| max_row_count | int | die maximale Zeilenanzahl der resultierenden Daten.<br/> Wenn der Wert nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Zeilenanzahl verwendet.|
| max_column_count | int | die maximale Spaltenanzahl der resultierenden Daten.<br/> Wenn der Wert nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Spaltenanzahl verwendet.|
###  Bemerkungen

Die Formel wird als dynamische Arrayformel verwendet, um die Dimension und das Ergebnis zu berechnen.
Die benutzerdefinierte Maximaldimension wird in Fällen verwendet, in denen das berechnete Ergebnis ein großer Datensatz ist.
(das berechnete Ergebnis kann beispielsweise einer ganzen Zeile oder Spalte entsprechen)
Der Benutzer benötigt jedoch kein so großes Array, wenn es um geschäftliche Anforderungen oder die Leistung geht.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Berechnet eine Formel als Matrixformel.


###  Kehrt zurück

Berechnetes Formelergebnis.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) |Optionen zum Parsen von Formeln|
| c_opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zum Berechnen der Formel|
| base_cell_row | int | Der Zeilenindex der Basiszelle.|
| base_cell_column | int | Der Spaltenindex der Basiszelle.|
| max_row_count | int | Die maximale Zeilenanzahl der resultierenden Daten.<br/> Wenn der Wert nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Zeilenanzahl verwendet.|
| max_column_count | int | Die maximale Spaltenanzahl der resultierenden Daten.<br/> Wenn der Wert nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Spaltenanzahl verwendet.|
| calculation_data | [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata) | Die Berechnungsdaten. Sie werden für die Situation verwendet<br/>dass der Benutzer bei der Implementierung einer benutzerdefinierten Berechnungs-Engine einige statische Formeln berechnen muss.<br/>Für solche Situationen muss der Benutzer sie mit den bereitgestellten Berechnungsdaten angeben<br/> für Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  Bemerkungen

Die Formel wird als dynamische Arrayformel verwendet, um die Dimension und das Ergebnis zu berechnen.
Die benutzerdefinierte Maximaldimension wird in Fällen verwendet, in denen das berechnete Ergebnis ein großer Datensatz ist.
(das berechnete Ergebnis kann beispielsweise einer ganzen Zeile oder Spalte entsprechen)
Der Benutzer benötigt jedoch kein so großes Array, wenn es um geschäftliche Anforderungen oder die Leistung geht.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
