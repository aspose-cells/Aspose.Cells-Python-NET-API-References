﻿---
title: DataSorter class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 440
url: /aspose.cells/datasorter/
is_root: false
---

## DataSorter class

Summary description for DataSorter.



The DataSorter type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [keys](/cells/python-net/aspose.cells/datasorter/keys) | Gets the key list of data sorter. |
| [has_headers](/cells/python-net/aspose.cells/datasorter/has_headers) | Represents whether the range has headers. |
| [key1](/cells/python-net/aspose.cells/datasorter/key1) | Represents first sorted column index(absolute position, column A is 0, B is 1, ...). |
| [order1](/cells/python-net/aspose.cells/datasorter/order1) | Represents sort order of the first key. |
| [key2](/cells/python-net/aspose.cells/datasorter/key2) | Represents second sorted column index(absolute position, column A is 0, B is 1, ...). |
| [order2](/cells/python-net/aspose.cells/datasorter/order2) | Represents sort order of the second key. |
| [key3](/cells/python-net/aspose.cells/datasorter/key3) | Represents third sorted column index(absolute position, column A is 0, B is 1, ...). |
| [order3](/cells/python-net/aspose.cells/datasorter/order3) | Represents sort order of the third key. |
| [sort_left_to_right](/cells/python-net/aspose.cells/datasorter/sort_left_to_right) | True means that sorting orientation is from left to right.<br/>False means that sorting orientation is from top to bottom.<br/>The default value is false. |
| [case_sensitive](/cells/python-net/aspose.cells/datasorter/case_sensitive) | Gets and sets whether case sensitive when comparing string. |
| [sort_as_number](/cells/python-net/aspose.cells/datasorter/sort_as_number) | Indicates whether sorting anything that looks like a number. |


### Methods
| Method | Description |
| :- | :- |
| [add_key](/cells/python-net/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder) | Adds sorted column index and sort order. |
| [add_key](/cells/python-net/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder-str) | Adds sorted column index and sort order with custom sort list. |
| [add_key](/cells/python-net/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any) | Adds sorted column index and sort order with custom sort list. |
| [add_key](/cells/python-net/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder-list) | Adds sorted column index and sort order with custom sort list. |
| [sort](/cells/python-net/aspose.cells/datasorter/sort/#aspose.cells.Cells-int-int-int-int) | Sorts the data of the area. |
| [sort](/cells/python-net/aspose.cells/datasorter/sort/#aspose.cells.Cells-aspose.cells.CellArea) | Sort the data of the area. |
| [sort](/cells/python-net/aspose.cells/datasorter/sort/#) | Sort the data in the range. |
| [clear](/cells/python-net/aspose.cells/datasorter/clear/#) | Clear all settings. |



### Example 


```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

### See Also
* module [`aspose.cells`](..)
