﻿---
title: last_index_of method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.cells.revisions/revisioncollection/last_index_of/
is_root: false
---

## last_index_of(self, item) {#Revision}

Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list.


### Returns 


The zero-based index of the last occurrence of value within the entire the array list, if found; otherwise, -1.


```python

def last_index_of(self, item):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| item | Revision | The object to locate in the array list. The value can be null. |


## last_index_of(self, item, index) {#Revision-int}

Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index.


### Returns 


The zero-based index of the last occurrence of value within the range of elements in the array list that extends from the first element to startIndex, if found; otherwise, -1.


```python

def last_index_of(self, item, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| item | Revision | The object to locate in the array list. The value can be null. |
| index | int | The zero-based starting index of the backward search. |


## last_index_of(self, item, index, count) {#Revision-int-int}

Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index.


### Returns 


The zero-based index of the last occurrence of value within the range of elements in the System.Collections. Array list that contains count number of elements and ends at startIndex, if found; otherwise, -1.


```python

def last_index_of(self, item, index, count):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| item | Revision | The object to locate in the array list. The value can be null. |
| index | int | The zero-based starting index of the backward search. |
| count | int | The number of elements in the section to search. |



### See Also
* module [`aspose.cells.revisions`](../../)
* class [`RevisionCollection`](/cells/python-net/aspose.cells.revisions/revisioncollection)
