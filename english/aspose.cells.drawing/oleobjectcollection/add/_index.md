---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.drawing/oleobjectcollection/add/
is_root: false
---

## add(self, top_row, left_column, height, width, image_data) {#int-int-int-int-bytes}

Adds an OleObject to the collection.


### Returns 


[`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject) object index.


```python

def add(self, top_row, left_column, height, width, image_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| height | int | Height of oleObject, in unit of pixel. |
| width | int | Width of oleObject, in unit of pixel. |
| image_data | bytes | Image of ole object as byte array. |


## add(self, top_row, left_column, height, width, image_data, linked_file) {#int-int-int-int-bytes-System.String}

Adds a linked OleObject to the collection.


### Returns 


[`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject) object index.


```python

def add(self, top_row, left_column, height, width, image_data, linked_file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| left_column | int | Upper left column index. |
| height | int | Height of oleObject, in unit of pixel. |
| width | int | Width of oleObject, in unit of pixel. |
| image_data | bytes | Image of ole object as byte array. |
| linked_file | System.String |  |



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject)
* class [`OleObjectCollection`](/cells/python-net/aspose.cells.drawing/oleobjectcollection)
