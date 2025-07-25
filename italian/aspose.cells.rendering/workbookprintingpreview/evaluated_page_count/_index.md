---
title: evaluated_page_count proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells.rendering/workbookprintingpreview/evaluated_page_count/
is_root: false
---
##  evaluated_page_count proprietà

Valuta il numero totale di pagine di questa cartella di lavoro

###  Esempio

Il codice seguente mostra il modo più veloce per ottenere il conteggio delle pagine di una cartella di lavoro.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, WorkbookPrintingPreview

workbook = Workbook("Book1.xlsx")
workbookPrintingPreview = WorkbookPrintingPreview(workbook, ImageOrPrintOptions())
# fastest way to get page count especailly when there are massive data in workbook.
print(workbookPrintingPreview.evaluated_page_count)

```
###  Definizione:
```python
@property
def evaluated_page_count(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`WorkbookPrintingPreview`](/cells/python-net/it/aspose.cells.rendering/workbookprintingpreview)
