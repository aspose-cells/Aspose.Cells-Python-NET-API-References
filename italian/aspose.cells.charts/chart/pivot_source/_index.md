---
title: pivot_source proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 430
url: /it/aspose.cells.charts/chart/pivot_source/
is_root: false
---
##  pivot_source proprietà

La fonte sono i dati della tabella pivot.
Se PivotSource non è vuoto, il grafico è PivotChart.

###  Osservazioni

Se la tabella pivot "PivotTable1" nel foglio di lavoro "Sheet1" nel file "Book1.xls".
pivotSource potrebbe essere "[Book1.xls]Sheet1!PivotTable1" se il grafico e la tabella pivot non si trovano nella stessa cartella di lavoro.
Se si imposta questa proprietà, le impostazioni precedenti dell'origine dati andranno perse.
###  Definizione:
```python
@property
def pivot_source(self):
    ...
@pivot_source.setter
def pivot_source(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`Chart`](/cells/python-net/it/aspose.cells.charts/chart)
