---
title: SpinButtonActiveXControl sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl sınıfı
SpinButton denetimini temsil eder.



**Miras:** [`SpinButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



SpinButtonActiveXControl türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [workbook](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | ActiveX denetiminin türünü alır.|
| [width](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Kabul edilebilir minimum değeri alır ve ayarlar.|
| [max](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Kabul edilebilir maksimum değeri alır ve ayarlar.|
| [position](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Değeri alır ve ayarlar.|
| [small_change](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Position özelliğinin ne kadar değiştiğini alır ve ayarlar|
| [orientation](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | SpinButton veya ScrollBar'ın dikey mi yoksa yatay mı yönlendirildiğini alır ve ayarlar.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.drawing.activexcontrols`](..)
* sınıf [`SpinButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
