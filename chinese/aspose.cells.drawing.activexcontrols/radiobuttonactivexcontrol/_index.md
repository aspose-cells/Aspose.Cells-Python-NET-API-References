---
title: RadioButtonActiveXControl类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
## RadioButtonActiveXControl类
表示一个 RadioButton ActiveX 控件。



**继承：** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



RadioButtonActiveXControl 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [workbook](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) |获取 ActiveX 控件的类型。|
| [width](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) |获取并设置控件上显示的描述性文本。|
| [picture_position](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |获取并设置控件图片相对于其标题的位置。|
| [special_effect](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) |获取和设置控件的特殊效果。|
| [picture](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) |获取和设置图片的数据。|
| [accelerator](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) |获取并设置控件的加速键。|
| [value](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) |指示控件是否被选中。|
| [is_triple_state](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) |指示指定的控件将如何显示空值。|
| [group_name](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) |获取并设置组的名称。|
| [alignment](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) |获取并设置 Caption 相对于控件的位置。|
| [is_word_wrapped](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) |指示控件的内容是否在行末自动换行。|



### 例子

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, RadioButtonActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.RADIO_BUTTON, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(RadioButtonActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing.activexcontrols`](..)
* 类 [`RadioButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* 类 [`ToggleButtonActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
