---
title: Cell класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 140
url: /ru/aspose.cells/cell/
is_root: false
---
##  Cell класс
Инкапсулирует объект, представляющий одну ячейку книги.



Тип Cell предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [worksheet](/cells/python-net/ru/aspose.cells/cell/worksheet) |Получает родительский лист.|
| [date_time_value](/cells/python-net/ru/aspose.cells/cell/date_time_value) | Получает значение DateTime, содержащееся в ячейке.|
| [row](/cells/python-net/ru/aspose.cells/cell/row) | Получает номер строки (отсчитываемый от нуля) ячейки.|
| [column](/cells/python-net/ru/aspose.cells/cell/column) | Получает номер столбца (отсчитываемый от нуля) ячейки.|
| [is_formula](/cells/python-net/ru/aspose.cells/cell/is_formula) | Указывает, содержит ли указанная ячейка формулу.|
| [type](/cells/python-net/ru/aspose.cells/cell/type) | Представляет тип значения ячейки.|
| [name](/cells/python-net/ru/aspose.cells/cell/name) | Получает имя ячейки.|
| [is_error_value](/cells/python-net/ru/aspose.cells/cell/is_error_value) | Проверяет, является ли значение этой ячейки ошибкой.|
| [is_numeric_value](/cells/python-net/ru/aspose.cells/cell/is_numeric_value) | Указывает, является ли значение этой ячейки числовым (int, double и datetime).|
| [string_value](/cells/python-net/ru/aspose.cells/cell/string_value) | Получает строковое значение, содержащееся в ячейке. Если тип этой ячейки — строка, верните само строковое значение.<br/>Для других типов ячеек будет возвращено форматированное строковое значение (отформатированное с указанным стилем этой ячейки).<br/>Значение форматированной ячейки такое же, как и то, что вы можете получить из Excel при копировании ячейки в виде текста (например,<br/> копирование ячейки в текстовый редактор или экспорт в CSV).|
| [string_value_without_format](/cells/python-net/ru/aspose.cells/cell/string_value_without_format) | Получает значение ячейки в виде строки без какого-либо формата.|
| [number_category_type](/cells/python-net/ru/aspose.cells/cell/number_category_type) | Представляет тип категории форматирования чисел этой ячейки.|
| [display_string_value](/cells/python-net/ru/aspose.cells/cell/display_string_value) | Получает форматированное строковое значение этой ячейки в соответствии со стилем отображения ячейки.|
| [int_value](/cells/python-net/ru/aspose.cells/cell/int_value) | Получает целочисленное значение, содержащееся в ячейке.|
| [double_value](/cells/python-net/ru/aspose.cells/cell/double_value) | Получает двойное значение, содержащееся в ячейке.|
| [float_value](/cells/python-net/ru/aspose.cells/cell/float_value) | Получает значение с плавающей запятой, содержащееся в ячейке.|
| [bool_value](/cells/python-net/ru/aspose.cells/cell/bool_value) |Получает логическое значение, содержащееся в ячейке.|
| [has_custom_style](/cells/python-net/ru/aspose.cells/cell/has_custom_style) | Указывает, имеет ли эта ячейка собственные настройки стиля (отличные от унаследованного по умолчанию).<br/> из соответствующей строки, столбца или книги).|
| [shared_style_index](/cells/python-net/ru/aspose.cells/cell/shared_style_index) | Получает индекс общего стиля ячейки в пуле стилей.|
| [formula](/cells/python-net/ru/aspose.cells/cell/formula) | Получает или задает формулу [`Cell`](/cells/python-net/ru/aspose.cells/cell).|
| [formula_local](/cells/python-net/ru/aspose.cells/cell/formula_local) | Получите формулу ячейки в языковом формате.|
| [r1c1_formula](/cells/python-net/ru/aspose.cells/cell/r1c1_formula) | Получает или задает формулу R1C1 для номера [`Cell`](/cells/python-net/ru/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/ru/aspose.cells/cell/contains_external_link) | Указывает, содержит ли эта ячейка внешнюю ссылку.<br/> Применяется только в том случае, если ячейка является ячейкой формулы.|
| [is_array_header](/cells/python-net/ru/aspose.cells/cell/is_array_header) | Указывает, что формула ячейки является формулой массива.<br/> и это первая ячейка массива.|
| [is_dynamic_array_formula](/cells/python-net/ru/aspose.cells/cell/is_dynamic_array_formula) | Указывает, является ли формула ячейки формулой динамического массива (true) или устаревшей формулой массива (false).|
| [is_array_formula](/cells/python-net/ru/aspose.cells/cell/is_array_formula) | Указывает, является ли формула ячейки формулой массива.|
| [is_in_array](/cells/python-net/ru/aspose.cells/cell/is_in_array) | Указывает, является ли формула ячейки формулой массива.|
| [is_shared_formula](/cells/python-net/ru/aspose.cells/cell/is_shared_formula) | Указывает, является ли формула ячейки частью общей формулы.|
| [is_table_formula](/cells/python-net/ru/aspose.cells/cell/is_table_formula) | Указывает, является ли эта ячейка частью формулы таблицы.|
| [is_in_table](/cells/python-net/ru/aspose.cells/cell/is_in_table) | Указывает, является ли эта ячейка частью формулы таблицы.|
| [value](/cells/python-net/ru/aspose.cells/cell/value) | Получает/устанавливает значение, содержащееся в этой ячейке.|
| [is_style_set](/cells/python-net/ru/aspose.cells/cell/is_style_set) |Указывает, установлен ли стиль ячейки. Если возвращается false, это означает, что эта ячейка имеет формат ячейки по умолчанию.|
| [is_merged](/cells/python-net/ru/aspose.cells/cell/is_merged) | Проверяет, является ли ячейка частью объединенного диапазона или нет.|
| [comment](/cells/python-net/ru/aspose.cells/cell/comment) | Получает комментарий этой ячейки.|
| [html_string](/cells/python-net/ru/aspose.cells/cell/html_string) | Получает и задает строку HTML, содержащую данные и некоторые форматы в этой ячейке.|
| [embedded_image](/cells/python-net/ru/aspose.cells/cell/embedded_image) | Получает и задает внедренное изображение в ячейке.|


###  Методы
| Метод| Описание|
| :- | :- |
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#bool) | Помещает логическое значение в ячейку.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#int) | Помещает в ячейку целочисленное значение.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#float) | Помещает в ячейку двойное значение.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#str-bool-bool) | Помещает значение в ячейку. При необходимости значение будет преобразовано в другой тип данных, а числовой формат ячейки будет сброшен.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#str-bool) | Помещает строковое значение в ячейку и при необходимости преобразует значение в другой тип данных.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#str) | Помещает строковое значение в ячейку.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#DateTime) | Помещает в ячейку значение DateTime.|
| [put_value](/cells/python-net/ru/aspose.cells/cell/put_value/#any) | Помещает значение объекта в ячейку.|
| [get_display_style](/cells/python-net/ru/aspose.cells/cell/get_display_style/#) | Получает стиль отображения ячейки.<br/>Если на эту ячейку также влияют другие параметры, такие как условное форматирование, объекты списка и т. д.,<br/>тогда стиль отображения может отличаться от cell.GetStyle().|
| [get_display_style](/cells/python-net/ru/aspose.cells/cell/get_display_style/#bool) | Получает стиль отображения ячейки.<br/> Если ячейка имеет условное форматирование, стиль отображения отличается от стиля ячейки.GetStyle().|
| [get_style](/cells/python-net/ru/aspose.cells/cell/get_style/#) | Получает стиль ячейки.|
| [get_style](/cells/python-net/ru/aspose.cells/cell/get_style/#bool) | Если checkBorders имеет значение true, проверьте, будут ли границы других ячеек влиять на стиль этой ячейки.|
| [set_style](/cells/python-net/ru/aspose.cells/cell/set_style/#aspose.cells.Style) | Устанавливает стиль ячейки.|
| [set_style](/cells/python-net/ru/aspose.cells/cell/set_style/#aspose.cells.Style-bool) | Примените измененное свойство стиля к ячейке.|
| [set_style](/cells/python-net/ru/aspose.cells/cell/set_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Примените стиль ячейки на основе флагов.|
| [set_formula](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-any) | Установите формулу и значение (расчетный результат) формулы.|
| [set_formula](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-bool-bool-any) | Установите формулу и значение формулы.|
| [set_formula](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-aspose.cells.FormulaParseOptions-any) | Установите формулу и значение (расчетный результат) формулы.|
| [set_array_formula](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Устанавливает формулу массива в диапазон ячеек.|
| [set_array_formula](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int) | Устанавливает формулу массива (устаревшая формула массива, введенная с помощью CTRL+SHIFT+ENTER в MS Excel) в диапазон ячеек.|
| [set_array_formula](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Устанавливает формулу массива в диапазон ячеек.|
| [set_array_formula](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Устанавливает формулу массива в диапазон ячеек.|
| [set_shared_formula](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Устанавливает формулу в диапазон ячеек.|
| [set_shared_formula](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int) | Устанавливает общие формулы в диапазон ячеек.|
| [set_shared_formula](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Устанавливает общие формулы в диапазон ячеек.|
| [set_shared_formula](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Устанавливает общие формулы в диапазон ячеек.|
| [get_leafs](/cells/python-net/ru/aspose.cells/cell/get_leafs/#) | Получите все ячейки, которые напрямую ссылаются на эту ячейку и должны быть обновлены при изменении этой ячейки.|
| [get_leafs](/cells/python-net/ru/aspose.cells/cell/get_leafs/#bool) | Получите все ячейки, которые будут обновлены при изменении этой ячейки.|
| [set_dynamic_array_formula](/cells/python-net/ru/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-bool) |Устанавливает формулу динамического массива и, если это возможно, заставляет формулу распространяться на соседние ячейки.|
| [set_dynamic_array_formula](/cells/python-net/ru/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool) |Устанавливает формулу динамического массива и, если это возможно, заставляет формулу распространяться на соседние ячейки.|
| [set_dynamic_array_formula](/cells/python-net/ru/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions) |Устанавливает формулу динамического массива и, если это возможно, заставляет формулу распространяться на соседние ячейки.|
| [set_table_formula](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Создайте таблицу данных с двумя переменными для заданного диапазона, начиная с этой ячейки.|
| [set_table_formula](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Создайте таблицу данных с одной переменной для заданного диапазона, начиная с этой ячейки.|
| [set_table_formula](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Создайте таблицу данных с двумя переменными для заданного диапазона, начиная с этой ячейки.|
| [set_table_formula](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Создайте таблицу данных с одной переменной для заданного диапазона, начиная с этой ячейки.|
| [get_characters](/cells/python-net/ru/aspose.cells/cell/get_characters/#) | Возвращает все объекты символов<br/> который представляет собой диапазон символов в тексте ячейки.|
| [get_characters](/cells/python-net/ru/aspose.cells/cell/get_characters/#bool) | Возвращает все объекты символов<br/> который представляет собой диапазон символов в тексте ячейки.|
| [calculate](/cells/python-net/ru/aspose.cells/cell/calculate/#aspose.cells.CalculationOptions) | Вычисляет формулу ячейки.|
| [get_string_value](/cells/python-net/ru/aspose.cells/cell/get_string_value/#aspose.cells.CellValueFormatStrategy) | Получает строковое значение по определенной стратегии форматирования.|
| [get_width_of_value](/cells/python-net/ru/aspose.cells/cell/get_width_of_value/#) | Получает ширину значения в пикселях.|
| [get_height_of_value](/cells/python-net/ru/aspose.cells/cell/get_height_of_value/#) | Получает высоту значения в пикселях.|
| [get_format_conditions](/cells/python-net/ru/aspose.cells/cell/get_format_conditions/#) | Получает условия форматирования, применимые к этой ячейке.|
| [get_formula](/cells/python-net/ru/aspose.cells/cell/get_formula/#bool-bool) | Получите формулу этой ячейки.|
| [get_precedents](/cells/python-net/ru/aspose.cells/cell/get_precedents/#) | Получает все ссылки, встречающиеся в формуле этой ячейки.|
| [get_dependents](/cells/python-net/ru/aspose.cells/cell/get_dependents/#bool) | Получите все ячейки, формула которых напрямую ссылается на эту ячейку.|
| [get_precedents_in_calculation](/cells/python-net/ru/aspose.cells/cell/get_precedents_in_calculation/#) | Получает все прецеденты (ссылки на ячейки в текущей книге), используемые формулой этой ячейки при ее вычислении.|
| [get_dependents_in_calculation](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation/#bool) | Получает все ячейки, результат вычисления которых зависит от этой ячейки.|
| [get_array_range](/cells/python-net/ru/aspose.cells/cell/get_array_range/#) |Получает диапазон массива, если формула ячейки является формулой массива.|
| [remove_array_formula](/cells/python-net/ru/aspose.cells/cell/remove_array_formula/#bool) | Удалить формулу массива.|
| [copy](/cells/python-net/ru/aspose.cells/cell/copy/#aspose.cells.Cell) | Копирует данные из исходной ячейки.|
| [characters](/cells/python-net/ru/aspose.cells/cell/characters/#int-int) | Возвращает объект символов, представляющий диапазон символов в тексте ячейки.|
| [replace](/cells/python-net/ru/aspose.cells/cell/replace/#str-str-aspose.cells.ReplaceOptions) | Замените текст ячейки опциями.|
| [insert_text](/cells/python-net/ru/aspose.cells/cell/insert_text/#int-str) | Вставьте несколько символов в ячейку.<br/> Если ячейка имеет расширенное форматирование, этот метод может сохранить исходное форматирование.|
| [is_rich_text](/cells/python-net/ru/aspose.cells/cell/is_rich_text/#) | Указывает, является ли строковое значение этой ячейки форматированным текстом.|
| [set_characters](/cells/python-net/ru/aspose.cells/cell/set_characters/#list) | Устанавливает расширенный текстовый формат ячейки.|
| [get_merged_range](/cells/python-net/ru/aspose.cells/cell/get_merged_range/#) | Возвращает объект [`Range`](/cells/python-net/ru/aspose.cells/range), представляющий объединенный диапазон.|
| [get_html_string](/cells/python-net/ru/aspose.cells/cell/get_html_string/#bool) | Получает строку HTML, содержащую данные и некоторые форматы в этой ячейке.|
| [to_json](/cells/python-net/ru/aspose.cells/cell/to_json/#) | Преобразуйте данные структуры [`Cell`](/cells/python-net/ru/aspose.cells/cell) в JSON.|
| [equals](/cells/python-net/ru/aspose.cells/cell/equals/#aspose.cells.Cell) | Проверяет, ссылается ли этот объект на ту же ячейку, что и другой объект ячейки.|
| [get_conditional_formatting_result](/cells/python-net/ru/aspose.cells/cell/get_conditional_formatting_result/#) | Получите результат условного форматирования.|
| [get_validation](/cells/python-net/ru/aspose.cells/cell/get_validation/#) | Получает проверку, примененную к этой ячейке.|
| [get_validation_value](/cells/python-net/ru/aspose.cells/cell/get_validation_value/#) | Получает значение проверки, примененное к этой ячейке.|
| [get_table](/cells/python-net/ru/aspose.cells/cell/get_table/#) |Получает таблицу, содержащую эту ячейку.|



###  Пример

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
