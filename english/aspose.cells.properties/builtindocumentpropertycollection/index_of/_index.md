﻿---
title: index_of method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells.properties/builtindocumentpropertycollection/index_of/
is_root: false
---

## index_of {#str}

Gets the index of a property by name.


### Returns 


The zero based index. Negative value if not found.


```python
def index_of(self, name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | str | The case-insensitive name of the property. |


## index_of {#aspose.cells.properties.DocumentProperty-int}

Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element.


### Returns 


The zero-based index of the first occurrence of value within the range of elements in the array list that extends from startIndex to the last element, if found; otherwise, -1.


```python
def index_of(self, item, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| item | [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) | The object to locate in the array list. The value can be null. |
| index | int | The zero-based starting index of the search. 0 (zero) is valid in an empty list. |


## index_of {#aspose.cells.properties.DocumentProperty-int-int}

Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements.


### Returns 


The zero-based index of the first occurrence of value within the range of elements in the array list that starts at startIndex and contains count number of elements, if found; otherwise, -1.


```python
def index_of(self, item, index, count):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| item | [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) | The object to locate in the array list. The value can be null. |
| index | int | The zero-based starting index of the search. 0 (zero) is valid in an empty list. |
| count | int | The number of elements in the section to search. |



### See Also
* module [`aspose.cells.properties`](../../)
* class [`BuiltInDocumentPropertyCollection`](/cells/python-net/aspose.cells.properties/builtindocumentpropertycollection)
