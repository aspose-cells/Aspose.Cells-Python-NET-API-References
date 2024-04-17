﻿---
title: custom_document_properties property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 300
url: /aspose.cells/worksheetcollection/custom_document_properties/
is_root: false
---

## custom_document_properties property


Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) collection that represents all the custom document properties of the spreadsheet.

### Example 


```python
from aspose.cells import Workbook

workbook = Workbook()
workbook.worksheets.custom_document_properties.add("Checked by", "Jane")

```
### Definition:
```python
@property
def custom_document_properties(self):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`CustomDocumentPropertyCollection`](/cells/python-net/aspose.cells.properties/customdocumentpropertycollection)
* class [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty)
* class [`WorksheetCollection`](/cells/python-net/aspose.cells/worksheetcollection)
