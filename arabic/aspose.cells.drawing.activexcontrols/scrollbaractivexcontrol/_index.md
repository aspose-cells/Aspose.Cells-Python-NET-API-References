---
title: ScrollBarActiveXControl صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl صف
يمثل عنصر التحكم ScrollBar.



**الميراث:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



يكشف النوع ScrollBarActiveXControl عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | يحصل على نوع عنصر التحكم ActiveX.|
| [width](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | يحصل على الحد الأدنى للقيمة المقبولة ويحددها.|
| [max](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | يحصل على الحد الأقصى للقيمة المقبولة ويحددها.|
| [position](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | يحصل على القيمة ويحددها.|
| [small_change](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | يحصل على المبلغ الذي تتغير به خاصية الموضع ويحدده|
| [orientation](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | يحصل ويحدد ما إذا كان SpinButton أو ScrollBar موجهًا عموديًا أو أفقيًا.|
| [large_change](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | يحصل على المبلغ الذي تتغير به خاصية الموضع ويحدده|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.activexcontrols`](..)
* فئة [`ScrollBarActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* فئة [`SpinButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
