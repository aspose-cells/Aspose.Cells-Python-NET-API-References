---
title: RadioButtonActiveXControl صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl صف
يمثل عنصر تحكم ActiveX RadioButton.



**الميراث:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



يكشف النوع RadioButtonActiveXControl عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | يحصل على نوع عنصر التحكم ActiveX.|
| [width](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | يحصل على النص الوصفي الذي يظهر على عنصر التحكم ويقوم بتعيينه.|
| [picture_position](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |يحصل على موقع صورة عنصر التحكم ويحدده بالنسبة لتسميتها التوضيحية.|
| [special_effect](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | يحصل على التأثير الخاص لعنصر التحكم ويقوم بتعيينه.|
| [picture](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | يحصل على بيانات الصورة ويضبطها.|
| [accelerator](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | يحصل على مفتاح التسريع للتحكم ويقوم بتعيينه.|
| [value](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | يشير إلى ما إذا كان التحكم محددًا أم لا.|
| [is_triple_state](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | يشير إلى كيفية عرض عنصر التحكم المحدد للقيم الفارغة.|
| [group_name](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | يحصل على اسم المجموعة ويحدده.|
| [alignment](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | يحصل على موضع التسمية التوضيحية ويحدده بالنسبة لعنصر التحكم.|
| [is_word_wrapped](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | يشير إلى ما إذا كان محتوى عنصر التحكم يلتف تلقائيًا في نهاية السطر.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.activexcontrols`](..)
* فئة [`RadioButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* فئة [`ToggleButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
