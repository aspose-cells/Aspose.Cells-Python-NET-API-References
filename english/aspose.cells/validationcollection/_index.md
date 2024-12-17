﻿---
title: ValidationCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1690
url: /aspose.cells/validationcollection/
is_root: false
---

## ValidationCollection class

Represents data validation collection.



The ValidationCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [capacity](/cells/python-net/aspose.cells/validationcollection/capacity) | Gets or sets the number of elements that the array list can contain. |


### Methods
| Method | Description |
| :- | :- |
| [add](/cells/python-net/aspose.cells/validationcollection/add/#) | Adds a data validation to the collection. |
| [add](/cells/python-net/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Adds a data validation to the collection. |
| [copy_to](/cells/python-net/aspose.cells/validationcollection/copy_to/#list) | Copies the entire array list to a compatible one-dimensional array list, starting at the beginning of the target array list. |
| [copy_to](/cells/python-net/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Copies a range of elements from the array list to a compatible one-dimensional array list, starting at the specified index of the target array list. |
| [index_of](/cells/python-net/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element. |
| [index_of](/cells/python-net/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements. |
| [last_index_of](/cells/python-net/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list. |
| [last_index_of](/cells/python-net/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index. |
| [last_index_of](/cells/python-net/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index. |
| [remove_a_cell](/cells/python-net/aspose.cells/validationcollection/remove_a_cell/#int-int) | Removes all validation setting on the cell. |
| [remove_area](/cells/python-net/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Removes all validation setting on the range.. |
| [get_validation_in_cell](/cells/python-net/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Gets the validation applied to given cell. |
| [binary_search](/cells/python-net/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Searches the entire sorted array list for an element using the default comparer and returns the zero-based index of the element. |



### Example 


```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

### See Also
* module [`aspose.cells`](..)
