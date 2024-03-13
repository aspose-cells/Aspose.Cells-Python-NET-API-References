---
title: set_style method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 360
url: /aspose.cells/cell/set_style/
is_root: false
---

## set_style {#aspose.cells.Style}

Sets the cell style.



```python
def set_style(self, style):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| style | [`Style`](/cells/python-net/aspose.cells/style) | The cell style. |
### Remarks

If the border settings are changed, the border of adjust cells will be updated too.

## set_style {#aspose.cells.Style-bool}

Apply the changed property of style to the cell.



```python
def set_style(self, style, explicit_flag):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| style | [`Style`](/cells/python-net/aspose.cells/style) | The cell style. |
| explicit_flag | bool | True, only overwriting formatting which is explicitly set. |


## set_style {#aspose.cells.Style-aspose.cells.StyleFlag}

Apply the cell style based on flags.



```python
def set_style(self, style, flag):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| style | [`Style`](/cells/python-net/aspose.cells/style) | The cell style. |
| flag | [`StyleFlag`](/cells/python-net/aspose.cells/styleflag) | The style flag. |



### See Also
* module [`aspose.cells`](../../)
* class [`Cell`](/cells/python-net/aspose.cells/cell)
