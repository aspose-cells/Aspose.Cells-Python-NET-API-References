---
title: pivot_source proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 430
url: /it/aspose.cells.charts/chart/pivot_source/
is_root: false
---
##  pivot_source proprietà

L'origine sono i dati della tabella pivot.
Se PivotSource non è vuoto, il grafico è Grafico pivot.

###  Osservazioni

Se la tabella pivot "PivotTable1" nel foglio di lavoro "Sheet1" nel file "Book1.xls".
pivotSource potrebbe essere "[Book1.xls]Sheet1!PivotTable1" se il grafico e la tabella pivot non si trovano nella stessa cartella di lavoro.
Se imposti questa proprietà, l'impostazione precedente dell'origine dati andrà persa.
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
