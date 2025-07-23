---
title: calculate_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(self, formula) {#str}
Berechnet eine Formel.


###  Kehrt zurück

Berechnetes Formelergebnis.


```python

def calculate_formula(self, formula):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|


##  calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Berechnet einen Formelausdruck direkt.


###  Kehrt zurück

Berechnetes Ergebnis der angegebenen Formel.
Das zurückgegebene Objekt kann vom Typ [`Cell.value`](/cells/python-net/de/aspose.cells/cell#value) oder ReferredArea sein.


```python

def calculate_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zum Berechnen der Formel|
###  Bemerkungen

Die Formel wird so berechnet, als wäre sie in Zelle A1 eingestellt.
Und die Formel wird als normale Formel übernommen.
Wenn Sie die Formel als Array-Formel berechnen und ein Array für das berechnete Ergebnis erhalten möchten,
Bitte verwenden Sie stattdessen [`Worksheet.calculate_array_formula`](/cells/python-net/de/aspose.cells/worksheet/calculate_array_formula).

##  calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}
Berechnet alle Formeln in diesem Arbeitsblatt.



```python

def calculate_formula(self, options, recursive):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Berechnungsoptionen|
| recursive | bool | True bedeutet, dass die Zellen des Arbeitsblatts von den Zellen anderer Arbeitsblätter abhängen.<br/>die abhängigen Zellen in anderen Arbeitsblättern werden ebenfalls berechnet.<br/> „Falsch“ bedeutet, dass alle Formeln im Arbeitsblatt berechnet wurden und die Werte richtig sind.|


##  calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Berechnet einen Formelausdruck direkt.


###  Kehrt zurück

Berechnetes Ergebnis der angegebenen Formel.
Das zurückgegebene Objekt kann vom Typ [`Cell.value`](/cells/python-net/de/aspose.cells/cell#value) oder ReferredArea sein.


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|
| c_opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zum Berechnen der Formel.|
| base_cell_row | int | Der Zeilenindex der Basiszelle.|
| base_cell_column | int | Der Spaltenindex der Basiszelle.|
| calculation_data | [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata) | Die Berechnungsdaten. Sie werden für die Situation verwendet<br/>dass der Benutzer bei der Implementierung einer benutzerdefinierten Berechnungs-Engine einige statische Formeln berechnen muss.<br/>Für solche Situationen muss der Benutzer sie mit den bereitgestellten Berechnungsdaten angeben<br/> für Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  Bemerkungen

Die Formel wird so berechnet, als wäre sie für die angegebene Basiszelle festgelegt worden.
Die Formel wird als normale Formel verwendet. Wenn Sie die Formel als Array-Formel benötigen,
und um ein Array für das berechnete Ergebnis zu erhalten, verwenden Sie bitte
[`Worksheet.calculate_array_formula`](/cells/python-net/de/aspose.cells/worksheet/calculate_array_formula) stattdessen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
