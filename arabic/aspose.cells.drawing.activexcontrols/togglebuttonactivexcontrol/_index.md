---
title: ToggleButtonActiveXControl صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl صف
يمثل عنصر التحكم ToggleButton ActiveX.



**الميراث:** [`ToggleButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



يكشف النوع ToggleButtonActiveXControl عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | يحصل على نوع عنصر التحكم ActiveX.|
| [width](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | يحصل على النص الوصفي الذي يظهر على عنصر التحكم ويقوم بتعيينه.|
| [picture_position](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |يحصل على موقع صورة عنصر التحكم ويحدده بالنسبة لتسميتها التوضيحية.|
| [special_effect](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | يحصل على التأثير الخاص لعنصر التحكم ويقوم بتعيينه.|
| [picture](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | يحصل على بيانات الصورة ويضبطها.|
| [accelerator](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | يحصل على مفتاح التسريع للتحكم ويقوم بتعيينه.|
| [value](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | يشير إلى ما إذا كان التحكم محددًا أم لا.|
| [is_triple_state](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | يشير إلى كيفية عرض عنصر التحكم المحدد للقيم الفارغة.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.activexcontrols`](..)
* فئة [`ToggleButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
