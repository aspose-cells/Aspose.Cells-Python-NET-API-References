---
title: calculate_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
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


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Berechnet einen Formelausdruck direkt.


###  Kehrt zurück

Berechnetes Ergebnis der angegebenen Formel.
Das zurückgegebene Objekt kann vom möglichen Typ [`Cell.value`](/cells/python-net/de/aspose.cells/cell#value) oder ReferredArea sein.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zur Berechnungsformel|
###  Bemerkungen

Die Formel wird genauso berechnet, wie sie in Zelle A1 festgelegt wurde.
Und die Formel wird als normale Formel verwendet.
Wenn Sie möchten, dass die Formel als Array-Formel berechnet wird und Sie ein Array für das berechnete Ergebnis erhalten möchten,
Bitte verwenden Sie stattdessen [`Worksheet.calculate_array_formula`](/cells/python-net/de/aspose.cells/worksheet/calculate_array_formula).

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Berechnet alle Formeln in diesem Arbeitsblatt.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Berechnungsmöglichkeiten|
| recursive | bool | „True“ bedeutet, dass die Zellen des Arbeitsblatts von den Zellen anderer Arbeitsblätter abhängen.<br/>Die abhängigen Zellen in anderen Arbeitsblättern werden ebenfalls berechnet.<br/> Falsch bedeutet, dass alle Formeln im Arbeitsblatt berechnet wurden und die Werte richtig sind.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Berechnet einen Formelausdruck direkt.


###  Kehrt zurück

Berechnetes Ergebnis der angegebenen Formel.
Das zurückgegebene Objekt kann vom möglichen Typ [`Cell.value`](/cells/python-net/de/aspose.cells/cell#value) oder ReferredArea sein.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Zu berechnende Formel.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|
| c_opts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Optionen zur Berechnungsformel.|
| base_cell_row | int | Der Zeilenindex der Basiszelle.|
| base_cell_column | int | Der Spaltenindex der Basiszelle.|
| calculation_data | [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata) | Die Berechnungsdaten. Es wird für die Situation verwendet<br/>Dieser Benutzer muss einige statische Formeln berechnen, wenn er eine benutzerdefinierte Berechnungs-Engine implementiert.<br/>Für eine solche Situation muss der Benutzer dies mit den bereitgestellten Berechnungsdaten angeben<br/> für [`AbstractCalculationEngine.calculate`](/cells/python-net/de/aspose.cells/abstractcalculationengine/calculate).|
###  Bemerkungen

Die Formel wird so berechnet, wie sie auf die angegebene Basiszelle festgelegt wurde.
Und die Formel wird als normale Formel verwendet. Wenn Sie möchten, muss die Formel als Array-Formel berechnet werden
und um ein Array für das berechnete Ergebnis zu erhalten, verwenden Sie bitte
Stattdessen [`Worksheet.calculate_array_formula`](/cells/python-net/de/aspose.cells/worksheet/calculate_array_formula).


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
