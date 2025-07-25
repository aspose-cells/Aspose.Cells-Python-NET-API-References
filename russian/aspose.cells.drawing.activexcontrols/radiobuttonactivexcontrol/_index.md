---
title: RadioButtonActiveXControl класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl класс
Представляет собой элемент управления ActiveX RadioButton.



**Наследование:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Тип RadioButtonActiveXControl предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [workbook](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | Получает тип элемента управления ActiveX.|
| [width](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Получает и задает описательный текст, отображаемый на элементе управления.|
| [picture_position](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Получает и задает расположение изображения элемента управления относительно его подписи.|
| [special_effect](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Получает и задает специальный эффект элемента управления.|
| [picture](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Получает и задает данные изображения.|
| [accelerator](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Получает и задает клавишу-акселератор для элемента управления.|
| [value](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Указывает, проверен ли элемент управления или нет.|
| [is_triple_state](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Указывает, как указанный элемент управления будет отображать значения NULL.|
| [group_name](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Получает и задает имя группы.|
| [alignment](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Получает и задает положение заголовка относительно элемента управления.|
| [is_word_wrapped](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Указывает, будет ли содержимое элемента управления автоматически переноситься в конце строки.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells.drawing.activexcontrols`](..)
* класс [`RadioButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* класс [`ToggleButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
