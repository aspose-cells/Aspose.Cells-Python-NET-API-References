﻿---
title: process_cell method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/lightcellsdatahandler/process_cell/
is_root: false
---

## process_cell(cell) {#Cell}

Starts to process one cell.


### Returns 


whether this cell needs to be kept in cells model of current sheet.
Commonly it should be false so that all cells will not be kept in memory after being processed and then memory be saved.
For some special purpose such as user needs to access some cells later after the whole workbook having been processed,
user can make this method return true to keep those special cells in Cells model and access them later by APIs such as Cells[row, column].
However, keeping cells data in Cells model will requires more memory and if all cells are kept then reading template file
in LightCells mode will become same with reading it in normal way.


```python
def process_cell(self, cell):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cell | [Cell](/cells/python-net/aspose.cells/cell) | Cell object which is being processed currently |
### Remarks

It will be called after one cell's data has been read.


### See Also
* module [aspose.cells](../../)
* class [LightCellsDataHandler](/cells/python-net/aspose.cells/lightcellsdatahandler)
