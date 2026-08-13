---
title: get_actual_box method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells.drawing/textbox/get_actual_box/
is_root: false
---

## get_actual_box(self) {#}

Get the actual position and size of the shape (after applying rotation, flip, etc.)


### Returns 


Returns the position and size in the order of x, y, w, h


```python

def get_actual_box(self):
    ...
```


### Remarks

Note:The interface is not fully functional, especially the location information is not correct.It is recommended not to use this interface until the function is complete.
### Example 


```python

box = shape.get_actual_box()
print("x = "  + str(box[0]))
print("y = "  + str(box[1]))
print("w = "  + str(box[2]))
print("h = "  + str(box[3]))

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`TextBox`](/cells/python-net/aspose.cells.drawing/textbox)
