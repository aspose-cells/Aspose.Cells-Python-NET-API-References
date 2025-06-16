﻿---
title: region property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 230
url: /aspose.cells.loading/dbfloadoptions/region/
is_root: false
---

## region property


Gets or sets the regional settings used for the Workbook that will be loaded.

### Remarks 


The regional settings may be used for initializing some features for the workbook
such as fonts, themes, and so on.
For text based file formats, such as CSV, HTML, ..., the regional setting
also will be used to detect number formats and parse text values to numeric
or datetime values for cells.
This setting will be kept for the instantiated workbook later, that is,
[`WorkbookSettings.region`](/cells/python-net/aspose.cells/workbooksettings#region) of the workbook will use the same region
with this property.
### Definition:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

### See Also
* module [`aspose.cells.loading`](../../)
* class [`CountryCode`](/cells/python-net/aspose.cells/countrycode)
* class [`DbfLoadOptions`](/cells/python-net/aspose.cells.loading/dbfloadoptions)
