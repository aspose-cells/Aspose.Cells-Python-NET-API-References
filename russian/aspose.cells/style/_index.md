---
title: Style класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1350
url: /ru/aspose.cells/style/
is_root: false
---
##  Style класс
Представляет стиль отображения документа Excel, такой как шрифт, цвет, выравнивание, граница и т. д.
Объект Style содержит все атрибуты стиля (шрифт, формат чисел, выравнивание и т. д.) в качестве свойств.



Тип Style предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/style/__init__/#) | Инициализирует новый экземпляр класса [`Style`](/cells/python-net/ru/aspose.cells/style).|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [background_theme_color](/cells/python-net/ru/aspose.cells/style/background_theme_color) | Получает и задает цвет фоновой темы.|
| [foreground_theme_color](/cells/python-net/ru/aspose.cells/style/foreground_theme_color) | Получает и задает цвет темы переднего плана.|
| [name](/cells/python-net/ru/aspose.cells/style/name) | Получает или задает имя стиля.|
| [pattern](/cells/python-net/ru/aspose.cells/style/pattern) | Получает или задает тип узора фона ячейки.|
| [borders](/cells/python-net/ru/aspose.cells/style/borders) | Получает [`BorderCollection`](/cells/python-net/ru/aspose.cells/bordercollection) стиля.|
| [background_color](/cells/python-net/ru/aspose.cells/style/background_color) | Получает или задает цвет фона стиля.|
| [background_argb_color](/cells/python-net/ru/aspose.cells/style/background_argb_color) | Получает и задает цвет фона с помощью 32-битного значения ARGB.|
| [foreground_color](/cells/python-net/ru/aspose.cells/style/foreground_color) | Получает или задает цвет переднего плана стиля.|
| [foreground_argb_color](/cells/python-net/ru/aspose.cells/style/foreground_argb_color) | Получает и задает цвет переднего плана с 32-битным значением ARGB.|
| [has_borders](/cells/python-net/ru/aspose.cells/style/has_borders) | Проверяет, установлены ли границы для стиля.|
| [parent_style](/cells/python-net/ru/aspose.cells/style/parent_style) | Получает родительский стиль данного стиля.|
| [is_number_format_applied](/cells/python-net/ru/aspose.cells/style/is_number_format_applied) | Укажите, следует ли применять форматирование чисел.|
| [is_font_applied](/cells/python-net/ru/aspose.cells/style/is_font_applied) |Укажите, следует ли применять форматирование шрифта.|
| [is_alignment_applied](/cells/python-net/ru/aspose.cells/style/is_alignment_applied) | Укажите, следует ли применять форматирование выравнивания.|
| [is_border_applied](/cells/python-net/ru/aspose.cells/style/is_border_applied) | Укажите, следует ли применять форматирование границ.|
| [is_fill_applied](/cells/python-net/ru/aspose.cells/style/is_fill_applied) | Укажите, следует ли применять форматирование заливки.|
| [is_protection_applied](/cells/python-net/ru/aspose.cells/style/is_protection_applied) | Укажите, следует ли применять защитное форматирование.|
| [indent_level](/cells/python-net/ru/aspose.cells/style/indent_level) | Уровень отступа ячейки или диапазона. Может быть целым числом от 0 до 250.|
| [font](/cells/python-net/ru/aspose.cells/style/font) | Получает объект [`Style.font`](/cells/python-net/ru/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/ru/aspose.cells/style/rotation_angle) | Представляет угол поворота текста.|
| [horizontal_alignment](/cells/python-net/ru/aspose.cells/style/horizontal_alignment) | Возвращает или задает тип горизонтального выравнивания текста в ячейке.|
| [vertical_alignment](/cells/python-net/ru/aspose.cells/style/vertical_alignment) | Возвращает или задает тип вертикального выравнивания текста в ячейке.|
| [is_text_wrapped](/cells/python-net/ru/aspose.cells/style/is_text_wrapped) | Возвращает или задает значение, указывающее, переносится ли текст внутри ячейки.|
| [number](/cells/python-net/ru/aspose.cells/style/number) | Возвращает или задаёт формат отображения чисел и дат. Шаблоны форматирования различаются в разных регионах.|
| [is_locked](/cells/python-net/ru/aspose.cells/style/is_locked) | Возвращает или задает значение, указывающее, можно ли изменить ячейку или нет.|
| [custom](/cells/python-net/ru/aspose.cells/style/custom) | Представляет строку пользовательского числового формата этого объекта стиля.<br/>Если пользовательский числовой формат не установлен (например, числовой формат встроен), будет возвращено "".|
| [culture_custom](/cells/python-net/ru/aspose.cells/style/culture_custom) | Получает и задает строку шаблона, зависящую от языка и региональных параметров, для числового формата.<br/>Если для данного объекта не установлен числовой формат, будет возвращено значение null.<br/> Если формат числа встроен, будет возвращена строка шаблона, соответствующая встроенному числу.|
| [invariant_custom](/cells/python-net/ru/aspose.cells/style/invariant_custom) | Получает строку шаблона, не зависящую от языка и региональных параметров, для числового формата.<br/>Если для данного объекта не установлен числовой формат, будет возвращено значение null.<br/> Если формат числа встроен, будет возвращена строка шаблона, соответствующая встроенному числу.|
| [is_formula_hidden](/cells/python-net/ru/aspose.cells/style/is_formula_hidden) | Указывает, будет ли формула скрыта, если рабочий лист защищен.|
| [shrink_to_fit](/cells/python-net/ru/aspose.cells/style/shrink_to_fit) | Показывает, сжимается ли текст автоматически, чтобы уместиться в доступной ширине столбца.|
| [text_direction](/cells/python-net/ru/aspose.cells/style/text_direction) | Представляет порядок чтения текста.|
| [is_justify_distributed](/cells/python-net/ru/aspose.cells/style/is_justify_distributed) | Указывает, следует ли использовать выравнивание по ширине ячеек или распределенное выравнивание в последней строке текста.|
| [quote_prefix](/cells/python-net/ru/aspose.cells/style/quote_prefix) | Указывает, начинается ли значение ячейки с одинарной кавычки.|
| [is_gradient](/cells/python-net/ru/aspose.cells/style/is_gradient) | Указывает, является ли затенение ячеек градиентным узором.|
| [is_percent](/cells/python-net/ru/aspose.cells/style/is_percent) | Указывает, является ли формат числа процентным.|
| [is_date_time](/cells/python-net/ru/aspose.cells/style/is_date_time) | Указывает, является ли формат числа форматом даты.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/ru/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Устанавливает границы стиля.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/ru/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Устанавливает границы стиля.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/ru/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Устанавливает цвет фона.|
| [`copy(self, style)`](/cells/python-net/ru/aspose.cells/style/copy/#aspose.cells.style) | Копирует данные из другого объекта стиля|
| [`update(self)`](/cells/python-net/ru/aspose.cells/style/update/#) | Применить именованный стиль к стилям ячеек, которые используют этот именованный стиль.<br/>Это работает так же, как нажатие кнопки «ОК» после завершения изменения стиля.<br/> Применимо только к именованному стилю.|
| [`is_modified(self, modify_flag)`](/cells/python-net/ru/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Проверяет, были ли изменены указанные свойства стиля.<br/> Используется для стиля ConditionalFormattings, чтобы проверить, следует ли использовать указанные свойства этого стиля при применении ConditionalFormattings к ячейке.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/ru/aspose.cells/style/set_custom/#str-bool) | Задает строку пользовательского числового формата ячейки.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/ru/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Устанавливает указанную заливку в виде двухцветного градиента.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/ru/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | Получите настройку двухцветного градиента.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/ru/aspose.cells/style/get_two_color_gradient_setting/#) | Получите настройку двухцветного градиента.|
| [`to_json(self)`](/cells/python-net/ru/aspose.cells/style/to_json/#) | Преобразовать структурные данные [`Style`](/cells/python-net/ru/aspose.cells/style) в JSON.|



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
