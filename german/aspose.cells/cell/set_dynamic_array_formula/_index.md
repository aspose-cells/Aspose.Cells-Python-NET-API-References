---
title: set_dynamic_array_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 340
url: /de/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel, wenn möglich, in benachbarte Zellen überläuft.


###  Kehrt zurück

der Bereich, in den die Formel übergehen soll.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | der Formelausdruck|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Analysieren der Formel.<br/> Die Option „Analysieren“ wird ignoriert und die Formel wird immer sofort analysiert|
| calculate_value | bool | ob diese dynamische Arrayformel für die Zellen im verschütteten Bereich berechnet wird.|
###  Bemerkungen

der zurückgegebene Bereich ist möglicherweise nicht derselbe wie der tatsächliche Bereich, in den diese dynamische Arrayformel übergeht.
Wenn der Bereich nicht leere Zellen enthält, wird die Formel nur für die aktuelle Zelle festgelegt und als „#SPILL!“ gekennzeichnet.
Aber für solche Situationen geben wir immer noch den gesamten Bereich zurück, in den diese Formel übergehen sollte.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel, wenn möglich, in benachbarte Zellen überläuft.


###  Kehrt zurück

der Bereich, in den die Formel übergehen soll.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | der Formelausdruck|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Analysieren der Formel.<br/> Die Option „Analysieren“ wird ignoriert und die Formel wird immer sofort analysiert|
| values | list |Werte (berechnete Ergebnisse) für die Zellen mit der angegebenen dynamischen Array-Formel|
| calculate_range | bool | Ob der verschüttete Bereich für diese dynamische Arrayformel berechnet wird.<br/>Wenn der Parameter "values" nicht null ist und dieses Flag falsch ist,<br/> dann beträgt die Höhe des verschütteten Bereichs Werte.Länge und die Breite Werte[0].Länge.|
| calculate_value | bool | ob diese dynamische Array-Formel für die Zellen im verschütteten Bereich berechnet wird, wenn "Werte" null ist<br/> oder das entsprechende Element in „Werten“ für eine Zelle ist null.|
###  Bemerkungen

der zurückgegebene Bereich ist möglicherweise nicht derselbe wie der tatsächliche Bereich, in den diese dynamische Arrayformel übergeht.
Wenn der Bereich nicht leere Zellen enthält, wird die Formel nur für die aktuelle Zelle festgelegt und als „#SPILL!“ gekennzeichnet.
Aber für solche Situationen geben wir immer noch den gesamten Bereich zurück, in den diese Formel übergehen sollte.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel, wenn möglich, in benachbarte Zellen überläuft.


###  Kehrt zurück

der Bereich, in den die Formel übergehen soll.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | der Formelausdruck|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Analysieren der Formel.<br/> Die Option „Analysieren“ wird ignoriert und die Formel wird immer sofort analysiert|
| values | list |Werte (berechnete Ergebnisse) für die Zellen mit der angegebenen dynamischen Array-Formel|
| calculate_range | bool | Ob der verschüttete Bereich für diese dynamische Arrayformel berechnet wird.<br/>Wenn der Parameter "values" nicht null ist und dieses Flag falsch ist,<br/> dann beträgt die Höhe des verschütteten Bereichs Werte.Länge und die Breite Werte[0].Länge.|
| calculate_value | bool | ob diese dynamische Array-Formel für die Zellen im verschütteten Bereich berechnet wird, wenn "Werte" null ist<br/> oder das entsprechende Element in „Werten“ für eine Zelle ist null.|
| copts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Die Optionen zum Berechnen der Formel.<br/> Aus Leistungsgründen sollte die Eigenschaft [`CalculationOptions.recursive`](/cells/python-net/de/aspose.cells/calculationoptions#recursive) normalerweise auf „false“ gesetzt werden.|
###  Bemerkungen

der zurückgegebene Bereich ist möglicherweise nicht derselbe wie der tatsächliche Bereich, in den diese dynamische Arrayformel übergeht.
Wenn der Bereich nicht leere Zellen enthält, wird die Formel nur für die aktuelle Zelle festgelegt und als „#SPILL!“ gekennzeichnet.
Aber für solche Situationen geben wir immer noch den gesamten Bereich zurück, in den diese Formel übergehen sollte.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
