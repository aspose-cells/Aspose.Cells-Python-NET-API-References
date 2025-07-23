---
title: set_dynamic_array_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 340
url: /sv/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Ställer in dynamisk matrisformel och får formeln att spillas ut i angränsande celler om möjligt.


###  Returnerar

det intervall som formeln ska spilla inom.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | formeluttrycket|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | alternativ för att analysera formeln.<br/> Alternativet "Parse" ignoreras och formeln parsas alltid omedelbart.|
| calculate_value | bool | om denna dynamiska matrisformel ska beräknas för de cellerna i det spillda området.|
###  Anmärkningar

Det returnerade området kanske inte är detsamma som det faktiska området som denna dynamiska arrayformel spills in i.
Om det finns celler som inte är tomma i området kommer formeln endast att ställas in för den aktuella cellen och markeras som "#SPILL!".
Men för en sådan situation returnerar vi fortfarande hela det intervall som denna formel borde spilla över.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Ställer in dynamisk matrisformel och får formeln att spillas ut i angränsande celler om möjligt.


###  Returnerar

det intervall som formeln ska spilla inom.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | formeluttrycket|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | alternativ för att analysera formeln.<br/> Alternativet "Parse" ignoreras och formeln parsas alltid omedelbart.|
| values | list |värden (beräknade resultat) för de celler med given dynamisk matrisformel|
| calculate_range | bool | Om det utspillda området för denna dynamiska matrisformel ska beräknas.<br/>Om parametern "values" inte är null och denna flagga är falsk,<br/> då kommer det spillda områdets höjd att vara values.Length och width kommer att vara values[0].Length.|
| calculate_value | bool | om denna dynamiska matrisformel ska beräknas för de cellerna i det utspillda området när "värden" är null<br/> eller motsvarande objekt i "värden" för en cell är null.|
###  Anmärkningar

Det returnerade området kanske inte är detsamma som det faktiska området som denna dynamiska arrayformel spills in i.
Om det finns celler som inte är tomma i området kommer formeln endast att ställas in för den aktuella cellen och markeras som "#SPILL!".
Men för en sådan situation returnerar vi fortfarande hela det intervall som denna formel borde spilla över.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Ställer in dynamisk matrisformel och får formeln att spillas ut i angränsande celler om möjligt.


###  Returnerar

det intervall som formeln ska spilla inom.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | formeluttrycket|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | alternativ för att analysera formeln.<br/> Alternativet "Parse" ignoreras och formeln parsas alltid omedelbart.|
| values | list |värden (beräknade resultat) för de celler med given dynamisk matrisformel|
| calculate_range | bool | Om det utspillda området för denna dynamiska matrisformel ska beräknas.<br/>Om parametern "values" inte är null och denna flagga är falsk,<br/> då kommer det spillda områdets höjd att vara values.Length och width kommer att vara values[0].Length.|
| calculate_value | bool | om denna dynamiska matrisformel ska beräknas för de cellerna i det utspillda området när "värden" är null<br/> eller motsvarande objekt i "värden" för en cell är null.|
| copts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formeln.<br/> Vanligtvis, av prestandahänsyn, bör egenskapen [`CalculationOptions.recursive`](/cells/python-net/sv/aspose.cells/calculationoptions#recursive) vara falsk.|
###  Anmärkningar

Det returnerade området kanske inte är detsamma som det faktiska området som denna dynamiska arrayformel spills in i.
Om det finns celler som inte är tomma i området kommer formeln endast att ställas in för den aktuella cellen och markeras som "#SPILL!".
Men för en sådan situation returnerar vi fortfarande hela det intervall som denna formel borde spilla över.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
