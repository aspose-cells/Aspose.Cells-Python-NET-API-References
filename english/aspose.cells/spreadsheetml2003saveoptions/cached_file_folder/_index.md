﻿---
title: cached_file_folder property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells/spreadsheetml2003saveoptions/cached_file_folder/
is_root: false
---

## cached_file_folder property


The folder for temporary files that may be used as data cache.

### Remarks 


If the folder has not been specified,
the default value for it is [`CellsHelper.get_cache_folder`](/cells/python-net/aspose.cells/cellshelper/get_cache_folder).
If its default value is null or empty, or has been specified as null or empty,
then no cache file will be used when saving the workbook.
### Definition:
```python
@property
def cached_file_folder(self):
    ...
@cached_file_folder.setter
def cached_file_folder(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`SpreadsheetML2003SaveOptions`](/cells/python-net/aspose.cells/spreadsheetml2003saveoptions)
