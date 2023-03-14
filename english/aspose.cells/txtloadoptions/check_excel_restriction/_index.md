﻿---
title: check_excel_restriction property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.cells/txtloadoptions/check_excel_restriction/
is_root: false
---

## check_excel_restriction property


Whether check restriction of excel file when user modify cells related objects.
For example, excel does not allow inputting string value longer than 32K.
When you input a value longer than 32K such as by Cell.PutValue(string), if this property is true, you will get an Exception.
If this property is false, we will accept your input string value as the cell's value so that later
you can output the complete string value for other file formats such as CSV.
However, if you have set such kind of value that is invalid for excel file format,
you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file.
### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### See Also
* module [aspose.cells](../../)
* class [TxtLoadOptions](/cells/python-net/aspose.cells/txtloadoptions)
