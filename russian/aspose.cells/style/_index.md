---
title: Style класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1460
url: /ru/aspose.cells/style/
is_root: false
---
##  Style класс
Представляет стиль отображения документа Excel, например шрифт, цвет, выравнивание, границу и т. д.
Объект Style содержит все атрибуты стиля (шрифт, числовой формат, выравнивание и т. д.) в качестве свойств.



Тип Style предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/style/__init__/#) | Инициализирует новый экземпляр класса [`Style`](/cells/python-net/ru/aspose.cells/style).|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [background_theme_color](/cells/python-net/ru/aspose.cells/style/background_theme_color) | Получает и задает цвет фоновой темы.|
| [foreground_theme_color](/cells/python-net/ru/aspose.cells/style/foreground_theme_color) | Получает и задает цвет темы переднего плана.|
| [name](/cells/python-net/ru/aspose.cells/style/name) | Получает или задает имя стиля.|
| [pattern](/cells/python-net/ru/aspose.cells/style/pattern) |Получает или задает тип фонового узора ячейки.|
| [borders](/cells/python-net/ru/aspose.cells/style/borders) | Получает [`BorderCollection`](/cells/python-net/ru/aspose.cells/bordercollection) стиля.|
| [background_color](/cells/python-net/ru/aspose.cells/style/background_color) | Получает или задает цвет фона стиля.|
| [background_argb_color](/cells/python-net/ru/aspose.cells/style/background_argb_color) | Получает и задает цвет фона с помощью 32-битного значения ARGB.|
| [foreground_color](/cells/python-net/ru/aspose.cells/style/foreground_color) | Получает или задает цвет переднего плана стиля.|
| [foreground_argb_color](/cells/python-net/ru/aspose.cells/style/foreground_argb_color) | Получает и задает цвет переднего плана с 32-битным значением ARGB.|
| [has_borders](/cells/python-net/ru/aspose.cells/style/has_borders) | Проверяет, установлены ли для стиля границы.|
| [parent_style](/cells/python-net/ru/aspose.cells/style/parent_style) | Получает родительский стиль этого стиля.|
| [is_number_format_applied](/cells/python-net/ru/aspose.cells/style/is_number_format_applied) | Укажите, следует ли применять форматирование чисел.|
| [is_font_applied](/cells/python-net/ru/aspose.cells/style/is_font_applied) | Укажите, следует ли применять форматирование шрифта.|
| [is_alignment_applied](/cells/python-net/ru/aspose.cells/style/is_alignment_applied) | Укажите, следует ли применять форматирование выравнивания.|
| [is_border_applied](/cells/python-net/ru/aspose.cells/style/is_border_applied) | Укажите, следует ли применять форматирование границ.|
| [is_fill_applied](/cells/python-net/ru/aspose.cells/style/is_fill_applied) | Укажите, следует ли применять форматирование заливки.|
| [is_protection_applied](/cells/python-net/ru/aspose.cells/style/is_protection_applied) | Укажите, следует ли применять защитное форматирование.|
| [indent_level](/cells/python-net/ru/aspose.cells/style/indent_level) | Представляет уровень отступа для ячейки или диапазона. Может быть только целым числом от 0 до 250.|
| [font](/cells/python-net/ru/aspose.cells/style/font) | Получает объект [`Style.font`](/cells/python-net/ru/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/ru/aspose.cells/style/rotation_angle) | Представляет угол поворота текста.|
| [horizontal_alignment](/cells/python-net/ru/aspose.cells/style/horizontal_alignment) |Получает или задает тип горизонтального выравнивания текста в ячейке.|
| [vertical_alignment](/cells/python-net/ru/aspose.cells/style/vertical_alignment) | Получает или задает тип вертикального выравнивания текста в ячейке.|
| [is_text_wrapped](/cells/python-net/ru/aspose.cells/style/is_text_wrapped) | Получает или задает значение, указывающее, переносится ли текст внутри ячейки.|
| [number](/cells/python-net/ru/aspose.cells/style/number) | Получает или задает формат отображения чисел и дат. Шаблоны форматирования различны для разных регионов.|
| [is_locked](/cells/python-net/ru/aspose.cells/style/is_locked) | Получает или задает значение, указывающее, можно ли изменить ячейку или нет.|
| [custom](/cells/python-net/ru/aspose.cells/style/custom) | Представляет строку пользовательского числового формата этого объекта стиля.<br/> Если пользовательский числовой формат не установлен (например, числовой формат встроен), будет возвращено "".|
| [culture_custom](/cells/python-net/ru/aspose.cells/style/culture_custom) | Получает и задает строку шаблона, зависящую от языка и региональных параметров, для числового формата.<br/>Если для этого объекта не был установлен числовой формат, будет возвращено значение null.<br/> Если числовой формат является встроенным, будет возвращена строка шаблона, соответствующая встроенному числу.|
| [invariant_custom](/cells/python-net/ru/aspose.cells/style/invariant_custom) | Получает независимую от региональных параметров строку шаблона для числового формата.<br/>Если для этого объекта не был установлен числовой формат, будет возвращено значение null.<br/> Если числовой формат является встроенным, будет возвращена строка шаблона, соответствующая встроенному числу.|
| [is_formula_hidden](/cells/python-net/ru/aspose.cells/style/is_formula_hidden) |Указывает, будет ли формула скрыта, если лист защищен.|
| [shrink_to_fit](/cells/python-net/ru/aspose.cells/style/shrink_to_fit) | Указывает, сжимается ли текст автоматически, чтобы соответствовать доступной ширине столбца.|
| [text_direction](/cells/python-net/ru/aspose.cells/style/text_direction) | Представляет порядок чтения текста.|
| [is_justify_distributed](/cells/python-net/ru/aspose.cells/style/is_justify_distributed) | Указывает, следует ли использовать выравнивание ячеек по ширине или распределенное выравнивание в последней строке текста.|
| [quote_prefix](/cells/python-net/ru/aspose.cells/style/quote_prefix) | Указывает, начинается ли значение ячейки с одинарной кавычки.|
| [is_gradient](/cells/python-net/ru/aspose.cells/style/is_gradient) | Указывает, является ли затенение ячейки градиентным узором.|
| [is_percent](/cells/python-net/ru/aspose.cells/style/is_percent) | Указывает, является ли числовой формат процентным.|
| [is_date_time](/cells/python-net/ru/aspose.cells/style/is_date_time) | Указывает, является ли числовой формат форматом даты.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_border](/cells/python-net/ru/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Устанавливает границы стиля.|
| [set_border](/cells/python-net/ru/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Устанавливает границы стиля.|
| [set_pattern_color](/cells/python-net/ru/aspose.cells/style/set_pattern_color/#aspose.cells.BackgroundType-aspose.pydrawing.Color-aspose.pydrawing.Color) | Устанавливает цвет фона.|
| [copy](/cells/python-net/ru/aspose.cells/style/copy/#aspose.cells.Style) | Копирует данные из другого объекта стиля.|
| [update](/cells/python-net/ru/aspose.cells/style/update/#) | Примените именованный стиль к стилям ячеек, которые используют этот именованный стиль.<br/>Это работает так же, как нажатие кнопки «ОК» после завершения изменения стиля.<br/> Применяется только для именованного стиля.|
| [is_modified](/cells/python-net/ru/aspose.cells/style/is_modified/#aspose.cells.StyleModifyFlag) | Проверяет, были ли изменены указанные свойства стиля.<br/>Используется для стиля ConditionalFormattings, чтобы проверить, следует ли использовать указанные свойства этого стиля при применении ConditionalFormattings к ячейке.|
| [set_custom](/cells/python-net/ru/aspose.cells/style/set_custom/#str-bool) | Устанавливает строку произвольного числового формата ячейки.|
| [set_two_color_gradient](/cells/python-net/ru/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int) | Устанавливает для указанной заливки двухцветный градиент.|
| [get_two_color_gradient](/cells/python-net/ru/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.Color&-aspose.pydrawing.Color&-any-any) | Получите настройку двухцветного градиента.|
| [get_two_color_gradient_setting](/cells/python-net/ru/aspose.cells/style/get_two_color_gradient_setting/#) | Получите настройку двухцветного градиента.|
| [to_json](/cells/python-net/ru/aspose.cells/style/to_json/#) | Преобразуйте данные структуры [`Style`](/cells/python-net/ru/aspose.cells/style) в JSON.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`BorderCollection`](/cells/python-net/ru/aspose.cells/bordercollection)
* класс [`Style`](/cells/python-net/ru/aspose.cells/style)
