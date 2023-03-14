﻿---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.drawing/oleobjectcollection/add/
is_root: false
---

## add(upper_left_row, upper_left_column, height, width, image_data) {#int-int-int-int-bytes}

Adds an OleObject to the collection.


### Returns 


[OleObject](/cells/python-net/aspose.cells.drawing/oleobject) object index.


```python
def add(self, upper_left_row, upper_left_column, height, width, image_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| upper_left_row | int | Upper left row index. |
| upper_left_column | int | Upper left column index. |
| height | int | Height of oleObject, in unit of pixel. |
| width | int | Width of oleObject, in unit of pixel. |
| image_data | bytes | Image of ole object as byte array. |


## add(upper_left_row, upper_left_column, height, width, image_data, linked_file) {#int-int-int-int-bytes-str}

Adds a linked OleObject to the collection.


### Returns 


[OleObject](/cells/python-net/aspose.cells.drawing/oleobject) object index.


```python
def add(self, upper_left_row, upper_left_column, height, width, image_data, linked_file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| upper_left_row | int | Upper left row index. |
| upper_left_column | int | Upper left column index. |
| height | int | Height of oleObject, in unit of pixel. |
| width | int | Width of oleObject, in unit of pixel. |
| image_data | bytes | Image of ole object as byte array. |
| linked_file | str |  |



### See Also
* module [aspose.cells.drawing](../../)
* class [OleObject](/cells/python-net/aspose.cells.drawing/oleobject)
* class [OleObjectCollection](/cells/python-net/aspose.cells.drawing/oleobjectcollection)
