---
title: SpinButtonActiveXControl صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl صف
يمثل عنصر التحكم SpinButton.



**الميراث:** [`SpinButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



يكشف النوع SpinButtonActiveXControl عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [workbook](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | يحصل على نوع عنصر التحكم ActiveX.|
| [width](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | يحصل على الحد الأدنى للقيمة المقبولة ويحددها.|
| [max](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | يحصل على الحد الأقصى للقيمة المقبولة ويحددها.|
| [position](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | يحصل على القيمة ويحددها.|
| [small_change](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | يحصل على المبلغ الذي تتغير به خاصية الموضع ويحدده|
| [orientation](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | يحصل ويحدد ما إذا كان SpinButton أو ScrollBar موجهًا عموديًا أو أفقيًا.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.activexcontrols`](..)
* فئة [`SpinButtonActiveXControl`](/cells/python-net/ar/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
