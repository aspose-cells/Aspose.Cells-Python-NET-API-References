---
title: custom_document_properties propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 280
url: /es/aspose.cells/worksheetcollection/custom_document_properties/
is_root: false
---
##  custom_document_properties propiedad

Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades del documento personalizado de la hoja de cálculo.

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
workbook.worksheets.custom_document_properties.add("Checked by", "Jane")

```
###  Definición:
```python
@property
def custom_document_properties(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CustomDocumentPropertyCollection`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection)
* clase [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
