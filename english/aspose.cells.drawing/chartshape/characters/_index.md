﻿---
title: characters method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.cells.drawing/chartshape/characters/
is_root: false
---

## characters {#int-int}

Returns a Characters object that represents a range of characters within the text.


### Returns 


Characters object.


```python
def characters(self, start_index, length):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| start_index | int | The index of the start of the character. |
| length | int | The number of characters. |
### Remarks

This method only works on shape with title.
### Example 


```python

fontSetting = shape.characters(0, 4)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ChartShape`](/cells/python-net/aspose.cells.drawing/chartshape)
