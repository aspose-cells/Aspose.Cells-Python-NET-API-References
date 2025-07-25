---
title: custom_document_properties proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 300
url: /it/aspose.cells/worksheetcollection/custom_document_properties/
is_root: false
---
##  custom_document_properties proprietà

Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà personalizzate del documento del foglio di calcolo.

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
workbook.worksheets.custom_document_properties.add("Checked by", "Jane")

```
###  Definizione:
```python
@property
def custom_document_properties(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CustomDocumentPropertyCollection`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection)
* classe [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty)
* classe [`WorksheetCollection`](/cells/python-net/it/aspose.cells/worksheetcollection)
