---
title: ToggleButtonActiveXControl类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
## ToggleButtonActiveXControl类
表示 ToggleButton ActiveX 控件。



**继承：** [`ToggleButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



ToggleButtonActiveXControl 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [workbook](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) |获取 ActiveX 控件的类型。|
| [width](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) |获取并设置控件上显示的描述性文本。|
| [picture_position](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |获取并设置控件图片相对于其标题的位置。|
| [special_effect](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) |获取和设置控件的特殊效果。|
| [picture](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) |获取和设置图片的数据。|
| [accelerator](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) |获取并设置控件的加速键。|
| [value](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) |指示控件是否被选中。|
| [is_triple_state](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) |指示指定的控件将如何显示空值。|



### 例子

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, ToggleButtonActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.TOGGLE_BUTTON, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(ToggleButtonActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing.activexcontrols`](..)
* 类 [`ToggleButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
