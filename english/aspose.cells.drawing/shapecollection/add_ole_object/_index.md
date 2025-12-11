---
title: add_ole_object method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 210
url: /aspose.cells.drawing/shapecollection/add_ole_object/
is_root: false
---

## add_ole_object(self, top_row, top, left_column, left, height, width, image_data) {#int-int-int-int-int-int-bytes}

Adds an OleObject.


### Returns 





```python

def add_ole_object(self, top_row, top, left_column, left, height, width, image_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int |  |
| top | int |  |
| left_column | int |  |
| left | int |  |
| height | int |  |
| width | int |  |
| image_data | bytes |  |

### Example 


```python
from aspose import pycore
import bytearray
import int

with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    oleObject = shapes.add_ole_object(4, 0, 5, 0, 300, 500, imageData)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
