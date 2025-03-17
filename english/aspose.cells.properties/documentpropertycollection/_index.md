---
title: DocumentPropertyCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells.properties/documentpropertycollection/
is_root: false
---

## DocumentPropertyCollection class

Base class for [`BuiltInDocumentPropertyCollection`](/cells/python-net/aspose.cells.properties/builtindocumentpropertycollection) and [`CustomDocumentPropertyCollection`](/cells/python-net/aspose.cells.properties/customdocumentpropertycollection) collections.



The DocumentPropertyCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [capacity](/cells/python-net/aspose.cells.properties/documentpropertycollection/capacity) | Gets or sets the number of elements that the array list can contain. |


### Methods
| Method | Description |
| :- | :- |
| [`get(self, name)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/get/#str) | Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) object by the name of the property. |
| [`get(self, index)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/get/#int) | Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) object by index. |
| [`index_of(self, name)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/index_of/#str) | Gets the index of a property by name. |
| [`index_of(self, item, index)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element. |
| [`index_of(self, item, index, count)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements. |
| [`copy_to(self, array)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/copy_to/#list) | Copies the entire array list to a compatible one-dimensional array list, starting at the beginning of the target array list. |
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/copy_to/#int-list-int-int) | Copies a range of elements from the array list to a compatible one-dimensional array list, starting at the specified index of the target array list. |
| [`last_index_of(self, item)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list. |
| [`last_index_of(self, item, index)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index. |
| [`last_index_of(self, item, index, count)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index. |
| [`binary_search(self, item)`](/cells/python-net/aspose.cells.properties/documentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Searches the entire sorted array list for an element using the default comparer and returns the zero-based index of the element. |



### Example 


```python
from aspose.cells import Workbook

# Instantiate a Workbook object by calling its empty constructor
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties
# Accessng a custom document property by using the property index
customProperty1 = customProperties[3]
# Accessng a custom document property by using the property name
customProperty2 = customProperties.get("Owner")

```

### See Also
* module [`aspose.cells.properties`](..)
* class [`BuiltInDocumentPropertyCollection`](/cells/python-net/aspose.cells.properties/builtindocumentpropertycollection)
* class [`CustomDocumentPropertyCollection`](/cells/python-net/aspose.cells.properties/customdocumentpropertycollection)
* class [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty)
