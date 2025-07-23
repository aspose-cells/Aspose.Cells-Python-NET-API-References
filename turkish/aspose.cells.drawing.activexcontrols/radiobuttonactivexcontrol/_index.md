---
title: RadioButtonActiveXControl sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl sınıfı
Bir RadioButton ActiveX denetimini temsil eder.



**Miras:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



RadioButtonActiveXControl türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [workbook](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | ActiveX denetiminin türünü alır.|
| [width](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Bir kontrolde görünen açıklayıcı metni alır ve ayarlar.|
| [picture_position](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Kontrolün resminin başlığına göre konumunu alır ve ayarlar.|
| [special_effect](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Kontrolün özel efektini alır ve ayarlar.|
| [picture](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Resmin verilerini alır ve ayarlar.|
| [accelerator](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Kontrol için hızlandırıcı tuşunu alır ve ayarlar.|
| [value](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Kontrolün işaretli olup olmadığını gösterir.|
| [is_triple_state](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Belirtilen denetimin Null değerlerini nasıl görüntüleyeceğini belirtir.|
| [group_name](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Grubun adını alır ve ayarlar.|
| [alignment](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Başlığın kontrole göre konumunu alır ve ayarlar.|
| [is_word_wrapped](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Denetimin içeriğinin satır sonunda otomatik olarak sarılıp sarılmayacağını belirtir.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.drawing.activexcontrols`](..)
* sınıf [`RadioButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* sınıf [`ToggleButtonActiveXControl`](/cells/python-net/tr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
