---
title: get_param_value_in_array_mode metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode {#int-int-int}
Hämtar värdet/värdena för parametern vid givet index.
Om parametern är något slags uttryck som behöver beräknas,
sedan kommer det att beräknas i array-läge.


###  Returnerar

En array som innehåller alla objekt som representeras av den angivna parametern.


```python
def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | Indexet för parametern(0 baserat)|
| max_row_count | int | Gränsen för antal rader för den returnerade matrisen.<br/> Om det är icke-positivt eller större än det faktiska radantalet, kommer det faktiska radantalet att användas.|
| max_column_count | int | Kolumnantalgränsen för den returnerade matrisen.<br/> Om det är icke-positivt eller större än det faktiska radantalet, kommer det faktiska kolumnräkningen att användas.|
###  Anmärkningar

För ett uttryck som behöver beräknas, ta A:A+B:B som ett exempel:
I värdeläge kommer det att beräknas till ett enda värde enligt aktuell cellbas.
Men i matrisläge kommer alla värden för A1+B1,A2+B2,A3+B3,... att beräknas och användas för att konstruera den returnerade matrisen.
Och för en sådan typ av situation är det bättre att ange gränsen för antalet rader/kolumner
(såsom enligt [`Cells.max_data_row`](/cells/python-net/sv/aspose.cells/cells#max_data_row) och [`Cells.max_data_column`](/cells/python-net/sv/aspose.cells/cells#max_data_column)),
annars kan den returnerade stora arrayen öka minneskostnaden med stora mängder värdelös data.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata)
