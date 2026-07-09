---
title: create_id property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 390
url: /aspose.cells.drawing/oleobject/create_id/
is_root: false
---

## create_id property


Gets and sets create id for this shape.

### Example 


```python
from uuid import uuid4

print(shape.create_id)
g = uuid4()
shape.create_id = g
print(shape.create_id)

```
### Definition:
```python
@property
def create_id(self):
    ...
@create_id.setter
def create_id(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject)
