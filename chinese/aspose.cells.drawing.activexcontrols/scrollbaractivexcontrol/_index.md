---
title: ScrollBarActiveXControl类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
## ScrollBarActiveXControl类
表示 ScrollBar 控件。



**继承：** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



ScrollBarActiveXControl 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [workbook](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) |获取 ActiveX 控件的类型。|
| [width](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) |获取并设置可接受的最小值。|
| [max](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) |获取并设置最大可接受值。|
| [position](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) |获取并设置值。|
| [small_change](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) |获取并设置 Position 属性的变化量|
| [orientation](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) |获取并设置 SpinButton 或 ScrollBar 是垂直方向还是水平方向。|
| [large_change](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) |获取并设置 Position 属性的变化量|



### 例子

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, ScrollBarActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.SCROLL_BAR, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(ScrollBarActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing.activexcontrols`](..)
* 类 [`ScrollBarActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* 类 [`SpinButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
