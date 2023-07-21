﻿---
title: HyperlinkCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 820
url: /aspose.cells/hyperlinkcollection/
is_root: false
---

## HyperlinkCollection class

Encapsulates a collection of [`Hyperlink`](/cells/python-net/aspose.cells/hyperlink) objects.



The HyperlinkCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [capacity](/cells/python-net/aspose.cells/hyperlinkcollection/capacity) | Gets or sets the number of elements that the array list can contain. |


### Methods
| Method | Description |
| :- | :- |
| [add](/cells/python-net/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Adds a hyperlink to a specified cell or a range of cells. |
| [add](/cells/python-net/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Adds a hyperlink to a specified cell or a range of cells. |
| [add](/cells/python-net/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Adds a hyperlink to a specified cell or a range of cells. |
| [copy_to](/cells/python-net/aspose.cells/hyperlinkcollection/copy_to/#list) | Copies the entire array list to a compatible one-dimensional array list, starting at the beginning of the target array list. |
| [copy_to](/cells/python-net/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Copies a range of elements from the array list to a compatible one-dimensional array list, starting at the specified index of the target array list. |
| [index_of](/cells/python-net/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element. |
| [index_of](/cells/python-net/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements. |
| [last_index_of](/cells/python-net/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list. |
| [last_index_of](/cells/python-net/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index. |
| [last_index_of](/cells/python-net/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index. |
| [binary_search](/cells/python-net/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | Searches the entire sorted array list for an element using the default comparer and returns the zero-based index of the element. |



### Example 


```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

### See Also
* module [`aspose.cells`](..)
* class [`Hyperlink`](/cells/python-net/aspose.cells/hyperlink)
