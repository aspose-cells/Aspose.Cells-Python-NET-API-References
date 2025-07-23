---
title: calculate_array_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Beräknar en formel som en matrisformel.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formeln|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Beräknar en formel som en matrisformel.


###  Returnerar

Beräknat formelresultat.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formeln|
| max_row_count | int | det maximala radantalet för resulterande data.<br/> Om det inte är positivt eller större än det faktiska radantalet, kommer det faktiska radantalet att användas.|
| max_column_count | int | det maximala kolumnantalet för resulterande data.<br/> Om det inte är positivt eller större än det faktiska radantalet, kommer det faktiska kolumnantalet att användas.|
###  Anmärkningar

Formeln kommer att användas som en dynamisk matrisformel för att beräkna dimensionen och resultatet.
Användarspecificerad maximal dimension används i fall där det beräknade resultatet är en stor datamängd
(till exempel kan det beräknade resultatet motsvara en hel rad eller kolumn)
men användaren behöver inte en så stor array enligt affärskrav eller för prestandaöverväganden.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Beräknar en formel som en matrisformel.


###  Returnerar

Beräknat formelresultat.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) |Alternativ för att analysera formeln|
| c_opts | [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formeln|
| base_cell_row | int | Radindexet för bascellen.|
| base_cell_column | int | Kolumnindexet för bascellen.|
| max_row_count | int | Det maximala radantalet för resulterande data.<br/> Om det inte är positivt eller större än det faktiska radantalet, kommer det faktiska radantalet att användas.|
| max_column_count | int | Det maximala antalet kolumner för resulterande data.<br/> Om det inte är positivt eller större än det faktiska radantalet, kommer det faktiska kolumnantalet att användas.|
| calculation_data | [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata) | Beräkningsdata. Den används för situationen<br/>att användaren behöver beräkna några statiska formler när en anpassad beräkningsmotor implementeras.<br/>För en sådan situation måste användaren specificera det med de angivna beräkningsdata.<br/> för Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  Anmärkningar

Formeln kommer att användas som en dynamisk matrisformel för att beräkna dimensionen och resultatet.
Användarspecificerad maximal dimension används i fall där det beräknade resultatet är en stor datamängd
(till exempel kan det beräknade resultatet motsvara en hel rad eller kolumn)
men användaren behöver inte en så stor array enligt affärskrav eller för prestandaöverväganden.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
