﻿---
title: set_locked_property method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 220
url: /aspose.cells.drawing/timelineshape/set_locked_property/
is_root: false
---

## set_locked_property(self, type, value) {#aspose.cells.drawing.ShapeLockType-bool}

Set the locked property.



```python

def set_locked_property(self, type, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/aspose.cells.drawing/shapelocktype) | The locked type. |
| value | bool | The value of the property. |

### Example 


```python
from aspose.cells.drawing import ShapeLockType

shape.set_locked_property(ShapeLockType.ADJUST_HANDLES, True)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`TimelineShape`](/cells/python-net/aspose.cells.drawing/timelineshape)
