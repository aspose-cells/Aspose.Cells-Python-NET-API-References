﻿---
title: start_sheet method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.cells/lightcellsdataprovider/start_sheet/
is_root: false
---

## start_sheet {#int}

Starts to save a worksheet.


### Returns 


true if this provider will provide data for the given sheet; false if given sheet should use its normal data model(Cells).


```python
def start_sheet(self, sheet_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sheet_index | int | index of current sheet to be saved. |
### Remarks

It will be called at the beginning of saving a worksheet during saving a workbook.
If the provider needs to refer to *`sheetIndex`*  later
in startRow(Row) or startCell(Cell) method,
that is, if the process needs to know which worksheet is being processed, 
the implementation should retain the *`sheetIndex`*  value here.


### See Also
* module [`aspose.cells`](../../)
* class [`LightCellsDataProvider`](/cells/python-net/aspose.cells/lightcellsdataprovider)
