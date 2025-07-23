---
title: ToggleButtonActiveXControl sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl sınıfı
ToggleButton ActiveX denetimini temsil eder.



**Miras:** [`ToggleButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



ToggleButtonActiveXControl türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [workbook](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | ActiveX denetiminin türünü alır.|
| [width](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Bir kontrolde görünen açıklayıcı metni alır ve ayarlar.|
| [picture_position](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Kontrolün resminin başlığına göre konumunu alır ve ayarlar.|
| [special_effect](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Kontrolün özel efektini alır ve ayarlar.|
| [picture](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Resmin verilerini alır ve ayarlar.|
| [accelerator](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Kontrol için hızlandırıcı tuşunu alır ve ayarlar.|
| [value](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Kontrolün işaretli olup olmadığını gösterir.|
| [is_triple_state](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Belirtilen denetimin Null değerlerini nasıl görüntüleyeceğini belirtir.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.drawing.activexcontrols`](..)
* sınıf [`ToggleButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
