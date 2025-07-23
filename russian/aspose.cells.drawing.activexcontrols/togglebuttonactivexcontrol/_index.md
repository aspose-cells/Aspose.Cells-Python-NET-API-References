---
title: ToggleButtonActiveXControl класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl класс
Представляет элемент управления ActiveX ToggleButton.



**Наследование:** [`ToggleButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Тип ToggleButtonActiveXControl предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [workbook](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | Получает тип элемента управления ActiveX.|
| [width](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Получает и задает описательный текст, отображаемый на элементе управления.|
| [picture_position](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Получает и задает расположение изображения элемента управления относительно его подписи.|
| [special_effect](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Получает и задает специальный эффект элемента управления.|
| [picture](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Получает и задает данные изображения.|
| [accelerator](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Получает и задает клавишу-акселератор для элемента управления.|
| [value](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Указывает, проверен ли элемент управления или нет.|
| [is_triple_state](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Указывает, как указанный элемент управления будет отображать значения NULL.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells.drawing.activexcontrols`](..)
* класс [`ToggleButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
