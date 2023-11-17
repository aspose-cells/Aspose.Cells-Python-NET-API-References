﻿---
title: page_index property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 200
url: /aspose.cells/paginatedsaveoptions/page_index/
is_root: false
---

## page_index property


Gets or sets the 0-based index of the first page to save.

### Remarks 


Default is 0.

### Example 


The following example shows how to render a range of pages (3 and 4) in a Microsoft Excel file to PDF.

```python
from aspose.cells import PdfSaveOptions, Workbook

# Open an Excel file
wb = Workbook("Book1.xlsx")
options = PdfSaveOptions()
# Print only Page 3 and Page 4 in the output PDF
# Starting page index (0-based index)
options.page_index = 3
# Number of pages to be printed
options.page_count = 2
# Save the PDF file
wb.save("output.pdf", options)

```
### Definition:
```python
@property
def page_index(self):
    ...
@page_index.setter
def page_index(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions)
