---
title: ScrollBarActiveXControl класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 100
url: /ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl класс
Представляет элемент управления ScrollBar.



**Наследование:** [ScrollBarActiveXControl](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[SpinButtonActiveXControl](/cells/python-net/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol) → 
[ActiveXControl](/cells/python-net/aspose.cells.drawing.activexcontrols/activexcontrol) → 
[ActiveXControlBase](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/activexcontrolbase)



Тип ScrollBarActiveXControl предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [workbook](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) | Получает объект [ActiveXControlBase.workbook](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/activexcontrolbase#workbook).|
| [type](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Получает тип элемента управления ActiveX.|
| [width](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |Получает и задает ширину элемента управления в пунктах.|
| [height](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) | Получает и задает высоту элемента управления в пунктах.|
| [mouse_icon](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) | Получает и задает настраиваемый значок для отображения в качестве указателя мыши для элемента управления.|
| [mouse_pointer](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) | Получает и задает тип значка, отображаемого в качестве указателя мыши для элемента управления.|
| [fore_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) | Получает и задает основной цвет переднего плана.|
| [back_ole_color](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) | Получает и задает цвет фона.|
| [is_visible](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) | Указывает, виден ли этот элемент управления.|
| [shadow](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) | Указывает, показывать ли тень.|
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) | Получает и задает связанную ячейку.|
| [list_fill_range](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) | Получает и задает диапазон заполнения списка.|
| [data](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) | Получает и задает двоичные данные элемента управления.|
| [is_enabled](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) | Указывает, может ли элемент управления получать фокус и реагировать на события, созданные пользователем.|
| [is_locked](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) | Указывает, заблокированы ли данные в элементе управления для редактирования.|
| [is_transparent](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) | Указывает, является ли элемент управления прозрачным.|
| [is_auto_size](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) | Указывает, будет ли автоматически изменяться размер элемента управления для отображения всего его содержимого.|
| [ime_mode](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |Получает и задает режим времени выполнения по умолчанию редактора метода ввода для элемента управления, когда он получает фокус.|
| [font](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) | Представляет шрифт элемента управления.|
| [text_align](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) | Представляет, как выровнять текст, используемый элементом управления.|
| [min](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Получает и задает минимально допустимое значение.|
| [max](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Получает и задает максимально допустимое значение.|
| [position](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Получает и задает значение.|
| [small_change](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Получает и задает величину, на которую изменяется свойство Position.|
| [orientation](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Получает и задает вертикальную или горизонтальную ориентацию SpinButton или ScrollBar.|
| [large_change](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Получает и задает величину, на которую изменяется свойство Position.|



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
* модуль [aspose.cells.drawing.activexcontrols](..)
* класс [ActiveXControl](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/activexcontrol)
* класс [ActiveXControlBase](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/activexcontrolbase)
* класс [ScrollBarActiveXControl](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* класс [SpinButtonActiveXControl](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
