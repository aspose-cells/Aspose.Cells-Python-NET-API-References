---
title: calculate_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
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


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Beräknar ett formeluttryck direkt.


###  Returnerar

Beräknat resultat av given formel.
Det returnerade objektet kan vara av möjliga typer av [`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value), eller ReferredArea.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formel|
###  Anmärkningar

Formeln kommer att beräknas precis som den har ställts in på cell A1.
Och formeln kommer att tas som normal formel.
Om du behöver att formeln ska beräknas som en matrisformel och för att få en matris för det beräknade resultatet,
använd [`Worksheet.calculate_array_formula`](/cells/python-net/sv/aspose.cells/worksheet/calculate_array_formula) istället.

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Beräknar alla formler i detta kalkylblad.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för beräkning|
| recursive | bool | Sant betyder att om kalkylbladets celler beror på cellerna i andra kalkylblad,<br/>de beroende cellerna i andra kalkylblad kommer också att beräknas.<br/> Falskt betyder att alla formler i kalkylbladet har beräknats och att värdena är rätt.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Beräknar ett formeluttryck direkt.


###  Returnerar

Beräknat resultat av given formel.
Det returnerade objektet kan vara av möjliga typer av [`Cell.value`](/cells/python-net/sv/aspose.cells/cell#value), eller ReferredArea.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formel.|
| c_opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formel.|
| base_cell_row | int | Bascellens radindex.|
| base_cell_column | int | Kolumnindex för bascellen.|
| calculation_data | [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata) | Beräkningsdata. Det används för situationen<br/>att användaren behöver beräkna några statiska formler när man implementerar anpassad beräkningsmotor.<br/>För en sådan typ av situation måste användaren specificera det med beräkningsdata som tillhandahålls<br/> för [`AbstractCalculationEngine.calculate`](/cells/python-net/sv/aspose.cells/abstractcalculationengine/calculate).|
###  Anmärkningar

Formeln kommer att beräknas precis som den har ställts in på den angivna bascellen.
Och formeln kommer att tas som normal formel. Om du behöver beräknas formeln som en matrisformel
och för att få en array för det beräknade resultatet, använd
[`Worksheet.calculate_array_formula`](/cells/python-net/sv/aspose.cells/worksheet/calculate_array_formula) istället.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
