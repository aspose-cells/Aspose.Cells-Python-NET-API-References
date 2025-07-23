---
title: SpinButtonActiveXControl类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
## SpinButtonActiveXControl类
表示 SpinButton 控件。



**继承：** [`SpinButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



SpinButtonActiveXControl 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [workbook](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) |获取 ActiveX 控件的类型。|
| [width](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) |获取并设置可接受的最小值。|
| [max](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) |获取并设置最大可接受值。|
| [position](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) |获取并设置值。|
| [small_change](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) |获取并设置 Position 属性的变化量|
| [orientation](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) |获取并设置 SpinButton 或 ScrollBar 是垂直方向还是水平方向。|



### 例子

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, SpinButtonActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.SPIN_BUTTON, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(SpinButtonActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing.activexcontrols`](..)
* 类 [`SpinButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
