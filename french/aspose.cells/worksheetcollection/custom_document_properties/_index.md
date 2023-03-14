---
title: custom_document_properties propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells/worksheetcollection/custom_document_properties/
is_root: false
---
##  custom_document_properties propriété

Renvoie une collection [DocumentProperty](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document personnalisées de la feuille de calcul.

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
workbook.worksheets.custom_document_properties.add("Checked by", "Jane")

```
###  Définition:
```python
@property
def custom_document_properties(self):
    ...
```

###  Voir également
* module [aspose.cells](../../)
* classe [CustomDocumentPropertyCollection](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection)
* classe [DocumentProperty](/cells/python-net/fr/aspose.cells.properties/documentproperty)
* classe [WorksheetCollection](/cells/python-net/fr/aspose.cells/worksheetcollection)
