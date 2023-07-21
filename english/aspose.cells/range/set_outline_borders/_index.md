---
title: set_outline_borders method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 180
url: /aspose.cells/range/set_outline_borders/
is_root: false
---

## set_outline_borders {#aspose.cells.CellBorderType-aspose.cells.CellsColor}

Sets the outline borders around a range of cells with same border style and color.



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/aspose.cells/cellbordertype) | Border style. |
| border_color | [`CellsColor`](/cells/python-net/aspose.cells/cellscolor) | Border color. |


## set_outline_borders {#aspose.cells.CellBorderType-aspose.pydrawing.Color}

Sets the outline borders around a range of cells with same border style and color.



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/aspose.cells/cellbordertype) | Border style. |
| border_color | aspose.pydrawing.Color | Border color. |


## set_outline_borders {#list-aspose.pydrawing.Color[]}

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


### See Also
* module [`aspose.cells`](../../)
* class [`Range`](/cells/python-net/aspose.cells/range)
