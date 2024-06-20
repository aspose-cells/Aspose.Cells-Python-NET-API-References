﻿---
title: VbaModuleCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.vba/vbamodulecollection/
is_root: false
---

## VbaModuleCollection class

Represents the list of [`VbaModule`](/cells/python-net/aspose.cells.vba/vbamodule)



The VbaModuleCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [capacity](/cells/python-net/aspose.cells.vba/vbamodulecollection/capacity) | Gets or sets the number of elements that the array list can contain. |


### Methods
| Method | Description |
| :- | :- |
| [add](/cells/python-net/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.Worksheet) | Adds module for a worksheet. |
| [add](/cells/python-net/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.VbaModuleType-str) | Adds module. |
| [copy_to](/cells/python-net/aspose.cells.vba/vbamodulecollection/copy_to/#list) | Copies the entire array list to a compatible one-dimensional array list, starting at the beginning of the target array list. |
| [copy_to](/cells/python-net/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Copies a range of elements from the array list to a compatible one-dimensional array list, starting at the specified index of the target array list. |
| [index_of](/cells/python-net/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element. |
| [index_of](/cells/python-net/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements. |
| [last_index_of](/cells/python-net/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule) | Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list. |
| [last_index_of](/cells/python-net/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index. |
| [last_index_of](/cells/python-net/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index. |
| [add_designer_storage](/cells/python-net/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage](/cells/python-net/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Represents the data of Designer. |
| [add_user_form](/cells/python-net/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Inser user form into VBA Project. |
| [remove_by_worksheet](/cells/python-net/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.Worksheet) | Removes module for a worksheet. |
| [remove_by_name](/cells/python-net/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Remove the module by the name |
| [binary_search](/cells/python-net/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.VbaModule) | Searches the entire sorted array list for an element using the default comparer and returns the zero-based index of the element. |



### Example 


```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

### See Also
* module [`aspose.cells.vba`](..)
* class [`VbaModule`](/cells/python-net/aspose.cells.vba/vbamodule)
