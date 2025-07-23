---
title: ScrollBarActiveXControl класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl класс
Представляет элемент управления ScrollBar.



**Наследование:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Тип ScrollBarActiveXControl предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [workbook](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Получает тип элемента управления ActiveX.|
| [width](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Получает и задает минимально приемлемое значение.|
| [max](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Получает и задает максимально допустимое значение.|
| [position](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Получает и задает значение.|
| [small_change](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Возвращает и задает величину изменения свойства Position.|
| [orientation](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Возвращает и задает вертикальную или горизонтальную ориентацию SpinButton или ScrollBar.|
| [large_change](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Возвращает и задает величину изменения свойства Position.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells.drawing.activexcontrols`](..)
* класс [`ScrollBarActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* класс [`SpinButtonActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
