---
title: get_param_value_in_array_mode metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode(self, index, max_row_count, max_column_count) {#int-int-int}
Hämtar värdet/värdena för parametern vid givet index.
Om parametern är någon form av uttryck som behöver beräknas,
då kommer den att beräknas i arrayläge.


###  Returnerar

En array som innehåller alla objekt som representeras av den angivna parametern.


```python

def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | Parameterns index (0-baserat)|
| max_row_count | int | Radgränsen för den returnerade arrayen.<br/> Om det inte är positivt eller större än det faktiska radantalet, kommer det faktiska radantalet att användas.|
| max_column_count | int | Kolumngränsen för den returnerade arrayen.<br/> Om det inte är positivt eller större än det faktiska radantalet, kommer det faktiska kolumnantalet att användas.|
###  Anmärkningar

För ett uttryck som behöver beräknas, med A:A+B:B som exempel:
I värdeläge beräknas det till ett enda värde enligt den aktuella cellbasen.
Men i arrayläge kommer alla värden för A1+B1, A2+B2, A3+B3,... att beräknas och användas för att konstruera den returnerade arrayen.
Och för en sådan situation är det bättre att ange gränsen för antalet rader/kolumner.
(såsom enligt [`Cells.max_data_row`](/cells/python-net/sv/aspose.cells/cells#max_data_row) och [`Cells.max_data_column`](/cells/python-net/sv/aspose.cells/cells#max_data_column)),
annars kan den returnerade stora arrayen öka minneskostnaden med en stor mängd oanvändbar data.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata)
