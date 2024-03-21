---
title: set_dynamic_array_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 330
url: /de/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel nach Möglichkeit in benachbarte Zellen übergeht.


###  Kehrt zurück

der Bereich, in den die Formel gelangen soll.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str |der Formelausdruck|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.<br/> Die Option „Parsen“ wird ignoriert und die Formel wird immer sofort analysiert|
| calculate_value | bool | ob diese dynamische Array-Formel für die Zellen im übersprungenen Bereich berechnet wird.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel nach Möglichkeit in benachbarte Zellen übergeht.


###  Kehrt zurück

der Bereich, in den die Formel gelangen soll.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str |der Formelausdruck|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.<br/> Die Option „Parsen“ wird ignoriert und die Formel wird immer sofort analysiert|
| values | list | Werte (berechnete Ergebnisse) für die Zellen mit der angegebenen dynamischen Array-Formel|
| calculate_range | bool | Ob der Spill-Bereich für diese dynamische Array-Formel berechnet wird.<br/>Wenn der Parameter „values“ nicht null ist und dieses Flag „false“ ist,<br/> dann beträgt die Höhe des verschütteten Bereichs Werte. Länge und Breite betragen Werte[0].Länge.|
| calculate_value | bool | Ob diese dynamische Array-Formel für die Zellen im übersprungenen Bereich berechnet wird, wenn „Werte“ null ist<br/> oder das entsprechende Element in „Werte“ für eine Zelle ist null.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel nach Möglichkeit in benachbarte Zellen übergeht.


###  Kehrt zurück

der Bereich, in den die Formel gelangen soll.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str |der Formelausdruck|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.<br/> Die Option „Parsen“ wird ignoriert und die Formel wird immer sofort analysiert|
| values | list | Werte (berechnete Ergebnisse) für die Zellen mit der angegebenen dynamischen Array-Formel|
| calculate_range | bool | Ob der Spill-Bereich für diese dynamische Array-Formel berechnet wird.<br/>Wenn der Parameter „values“ nicht null ist und dieses Flag „false“ ist,<br/> dann beträgt die Höhe des verschütteten Bereichs Werte. Länge und Breite betragen Werte[0].Länge.|
| calculate_value | bool | Ob diese dynamische Array-Formel für die Zellen im übersprungenen Bereich berechnet wird, wenn „Werte“ null ist<br/> oder das entsprechende Element in „Werte“ für eine Zelle ist null.|
| copts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Die Optionen zur Berechnungsformel.<br/> Aus Leistungsgründen sollte die Eigenschaft [`CalculationOptions.recursive`](/cells/python-net/de/aspose.cells/calculationoptions#recursive) im Allgemeinen falsch sein.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
