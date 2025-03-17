﻿---
title: set_outline_borders method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells/unionrange/set_outline_borders/
is_root: false
---

## set_outline_borders(self, border_styles, border_colors) {#list-aspose.pydrawing.Color[]}

Sets out line borders around a range of cells.



```python

def set_outline_borders(self, border_styles, border_colors):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| border_styles | list | Border styles. |
| border_colors | aspose.pydrawing.Color[] | Border colors. |
### Remarks

Both the length of borderStyles and borderStyles must be 4.
The order of borderStyles and borderStyles must be top,bottom,left,right

## set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.pydrawing.Color}

Sets the outline borders around a range of cells with same border style and color.



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/aspose.cells/cellbordertype) | Border style. |
| border_color | aspose.pydrawing.Color | Border color. |



### See Also
* module [`aspose.cells`](../../)
* class [`UnionRange`](/cells/python-net/aspose.cells/unionrange)
