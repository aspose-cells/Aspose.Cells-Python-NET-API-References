---
title: SpinButtonActiveXControl класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 90
url: /ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl класс
Представляет элемент управления SpinButton.



**Наследование:** [`SpinButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Тип SpinButtonActiveXControl предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [workbook](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | Получает тип элемента управления ActiveX.|
| [width](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Получает и задает минимально приемлемое значение.|
| [max](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Получает и задает максимально допустимое значение.|
| [position](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Получает и задает значение.|
| [small_change](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Возвращает и задает величину изменения свойства Position.|
| [orientation](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | Возвращает и задает вертикальную или горизонтальную ориентацию SpinButton или ScrollBar.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells.drawing.activexcontrols`](..)
* класс [`SpinButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
