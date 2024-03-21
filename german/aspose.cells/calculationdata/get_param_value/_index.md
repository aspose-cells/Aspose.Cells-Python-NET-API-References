---
title: get_param_value Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
Ruft das dargestellte Wertobjekt des Parameters am angegebenen Index ab.


###  Kehrt zurück

Der berechnete Wert des Parameters.


```python
def get_param_value(self, index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | Der Index des Parameters (0-basiert)|
###  Bemerkungen

Für einen Parameter:

Wenn es sich um einen einfachen Wert handelt, wird der einfache Wert selbst zurückgegeben.


Wenn es sich um eine Referenz handelt, wird das ReferredArea-Objekt zurückgegeben.


Wenn auf Datensätze mit mehreren Werten verwiesen wird, wird ein Array von Objekten zurückgegeben.



Wenn es sich um einen Ausdruck handelt, der berechnet werden muss, erfolgt die Berechnung im Wertmodus
und im Allgemeinen wird ein einzelner Wert entsprechend der aktuellen Zellbasis zurückgegeben. Zum Beispiel,
Wenn ein Parameter der Formel von D2 A:A+B:B ist, wird A2+B2 berechnet und zurückgegeben.
Wenn dieser Parameter jedoch als Array-Modus angegeben wurde
(bis [`Workbook.update_custom_function_definition`](/cells/python-net/de/aspose.cells/workbook/update_custom_function_definition)
oder [`FormulaParseOptions.custom_function_definition`](/cells/python-net/de/aspose.cells/formulaparseoptions#custom_function_definition)),
dann wird ein Array(object[][]) zurückgegeben, dessen Elemente A1+B1,A2+B2,... sind.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata)
