﻿---
title: CheckBoxCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 100
url: /aspose.cells.drawing/checkboxcollection/
is_root: false
---

## CheckBoxCollection class

Represents a collection of [CheckBox](/cells/python-net/aspose.cells.drawing/checkbox) objects in a worksheet.



The CheckBoxCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [capacity](/cells/python-net/aspose.cells.drawing/checkboxcollection/capacity) | Gets or sets the number of elements that the array list can contain. |


### Methods
| Method | Description |
| :- | :- |
| [copy_to(array)](/cells/python-net/aspose.cells.drawing/checkboxcollection/copy_to/#list) | Copies the entire array list to a compatible one-dimensional array list, starting at the beginning of the target array list. |
| [copy_to(index, array, array_index, count)](/cells/python-net/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) | Copies a range of elements from the array list to a compatible one-dimensional array list, starting at the specified index of the target array list. |
| [index_of(item, index)](/cells/python-net/aspose.cells.drawing/checkboxcollection/index_of/#CheckBox-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element. |
| [index_of(item, index, count)](/cells/python-net/aspose.cells.drawing/checkboxcollection/index_of/#CheckBox-int-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements. |
| [last_index_of(item)](/cells/python-net/aspose.cells.drawing/checkboxcollection/last_index_of/#CheckBox) | Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list. |
| [last_index_of(item, index)](/cells/python-net/aspose.cells.drawing/checkboxcollection/last_index_of/#CheckBox-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index. |
| [last_index_of(item, index, count)](/cells/python-net/aspose.cells.drawing/checkboxcollection/last_index_of/#CheckBox-int-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index. |
| [add(upper_left_row, upper_left_column, height, width)](/cells/python-net/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Adds a checkBox to the collection. |
| [binary_search(item)](/cells/python-net/aspose.cells.drawing/checkboxcollection/binary_search/#CheckBox) | Searches the entire sorted array list for an element using the default comparer and returns the zero-based index of the element. |



### Example 


```python
from aspose.cells import Workbook

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet in the workbook.
sheet = workbook.worksheets[0]
index = sheet.check_boxes.add(15, 15, 20, 100)
checkBox = sheet.check_boxes[index]
checkBox.text = "Check Box 1"

```

### See Also
* module [aspose.cells.drawing](..)
* class [CheckBox](/cells/python-net/aspose.cells.drawing/checkbox)
