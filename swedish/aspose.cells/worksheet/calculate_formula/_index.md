---
title: calculate_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(self, formula) {#str}
Beräknar en formel.


###  Returnerar

Beräknat formelresultat.


```python

def calculate_formula(self, formula):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|


##  calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Beräknar ett formeluttryck direkt.


###  Returnerar

Beräknat resultat av given formel.
Det returnerade objektet kan vara av de möjliga typerna [`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value) eller ReferredArea.


```python

def calculate_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formeln|
###  Anmärkningar

Formeln kommer att beräknas precis som den har ställts in i cell A1.
Och formeln kommer att tas som vanlig formel.
Om du behöver att formeln beräknas som en arrayformel och för att få en array för det beräknade resultatet,
använd [`Worksheet.calculate_array_formula`](/cells/python-net/sv/aspose.cells/worksheet/calculate_array_formula) istället.

##  calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}
Beräknar alla formler i detta kalkylblad.



```python

def calculate_formula(self, options, recursive):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för beräkning|
| recursive | bool | Sant betyder att om cellerna i kalkylbladet är beroende av cellerna i andra kalkylblad,<br/>De beroende cellerna i andra kalkylblad kommer också att beräknas.<br/> Falskt betyder att alla formler i kalkylbladet har beräknats och att värdena är korrekta.|


##  calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Beräknar ett formeluttryck direkt.


###  Returnerar

Beräknat resultat av given formel.
Det returnerade objektet kan vara av de möjliga typerna [`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value) eller ReferredArea.


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|
| c_opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formeln.|
| base_cell_row | int | Radindexet för bascellen.|
| base_cell_column | int | Kolumnindexet för bascellen.|
| calculation_data | [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata) | Beräkningsdata. Den används för situationen<br/>att användaren behöver beräkna några statiska formler när en anpassad beräkningsmotor implementeras.<br/>För en sådan situation måste användaren specificera det med de angivna beräkningsdata.<br/> för Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  Anmärkningar

Formeln kommer att beräknas precis som den har ställts in för den angivna bascellen.
Och formeln kommer att tas som en vanlig formel. Om du behöver beräkna formeln som en arrayformel
och för att få en array för det beräknade resultatet, använd
[`Worksheet.calculate_array_formula`](/cells/python-net/sv/aspose.cells/worksheet/calculate_array_formula) istället.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
