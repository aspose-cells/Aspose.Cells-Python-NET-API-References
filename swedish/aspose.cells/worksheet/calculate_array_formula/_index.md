---
title: calculate_array_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula {#str-aspose.cells.CalculationOptions}
Beräknar en formel som matrisformel.



```python
def calculate_array_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formel|


##  calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}
Beräknar en formel som matrisformel.


###  Returnerar

Beräknat formelresultat.


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formel|
| max_row_count | int | maximalt antal rader av resulterande data.<br/> Om det är icke-positivt eller större än det faktiska radantalet, kommer det faktiska radantalet att användas.|
| max_column_count | int | det maximala kolumnantal av resulterande data.<br/> Om det är icke-positivt eller större än det faktiska radantalet, kommer det faktiska kolumnräkningen att användas.|
###  Anmärkningar

Formeln kommer att tas som en dynamisk matrisformel för att beräkna dimensionen och resultatet.
Användarspecificerad maximal dimension används för de fall det beräknade resultatet är en stor datamängd
(till exempel kan det beräknade resultatet motsvara en hel rad eller kolumndata)
men användaren behöver inte en så stor array enligt affärskrav eller för prestandaöverväganden.

##  calculate_array_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Beräknar en formel som matrisformel.


###  Returnerar

Beräknat formelresultat.


```python
def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formel|
| c_opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formel|
| base_cell_row | int | Bascellens radindex.|
| base_cell_column | int | Kolumnindex för bascellen.|
| max_row_count | int | Maximalt antal rader för resulterande data.<br/> Om det är icke-positivt eller större än det faktiska radantalet, kommer det faktiska radantalet att användas.|
| max_column_count | int | Det maximala kolumnantal av resulterande data.<br/> Om det är icke-positivt eller större än det faktiska radantalet, kommer det faktiska kolumnräkningen att användas.|
| calculation_data | [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata) | Beräkningsdata. Det används för situationen<br/>att användaren behöver beräkna några statiska formler när man implementerar anpassad beräkningsmotor.<br/>För en sådan typ av situation måste användaren specificera det med beräkningsdata som tillhandahålls<br/> för [`AbstractCalculationEngine.calculate`](/cells/python-net/sv/aspose.cells/abstractcalculationengine/calculate).|
###  Anmärkningar

Formeln kommer att tas som en dynamisk matrisformel för att beräkna dimensionen och resultatet.
Användarspecificerad maximal dimension används för de fall det beräknade resultatet är en stor datamängd
(till exempel kan det beräknade resultatet motsvara en hel rad eller kolumndata)
men användaren behöver inte en så stor array enligt affärskrav eller för prestandaöverväganden.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
