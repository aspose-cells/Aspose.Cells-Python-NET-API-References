---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/worksheetcollection/add/
is_root: false
---
##  add(self) {#}
Aggiunge un foglio di lavoro alla raccolta.


###  ritorna

[`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) indice oggetto.


```python

def add(self):
    ...
```




##  add(self, type) {#aspose.cells.SheetType}
Aggiunge un foglio di lavoro alla raccolta.


###  ritorna

[`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) indice oggetto.


```python

def add(self, type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`SheetType`](/cells/python-net/it/aspose.cells/sheettype) | Tipo di foglio di lavoro.|

###  Esempio

```python
from aspose.cells import SheetType, Workbook
from aspose.cells.charts import ChartType

workbook = Workbook()
workbook.worksheets.add(SheetType.CHART)
cells = workbook.worksheets[0].cells
cells.get("c2").put_value(5000)
cells.get("c3").put_value(3000)
cells.get("c4").put_value(4000)
cells.get("c5").put_value(5000)
cells.get("c6").put_value(6000)
charts = workbook.worksheets[1].charts
chartIndex = charts.add(ChartType.COLUMN, 10, 10, 20, 20)
chart = charts[chartIndex]
chart.n_series.add("Sheet1!C2:C6", True)

```


##  add(self, sheet_name) {#str}
Aggiunge un foglio di lavoro alla raccolta.


###  ritorna

[`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) oggetto.


```python

def add(self, sheet_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| sheet_name | str | Nome del foglio di lavoro|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
* classe [`WorksheetCollection`](/cells/python-net/it/aspose.cells/worksheetcollection)
