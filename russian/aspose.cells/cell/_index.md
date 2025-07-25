---
title: Cell класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells/cell/
is_root: false
---
##  Cell класс
Инкапсулирует объект, представляющий одну ячейку рабочей книги.



Тип Cell предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [worksheet](/cells/python-net/ru/aspose.cells/cell/worksheet) | Получает родительский рабочий лист.|
| [date_time_value](/cells/python-net/ru/aspose.cells/cell/date_time_value) | Получает значение DateTime, содержащееся в ячейке.|
| [row](/cells/python-net/ru/aspose.cells/cell/row) | Возвращает номер строки (начиная с нуля) ячейки.|
| [column](/cells/python-net/ru/aspose.cells/cell/column) | Возвращает номер столбца (начиная с нуля) ячейки.|
| [is_formula](/cells/python-net/ru/aspose.cells/cell/is_formula) | Показывает, содержит ли указанная ячейка формулу.|
| [has_custom_function](/cells/python-net/ru/aspose.cells/cell/has_custom_function) |Проверяет, есть ли в формуле ячейки пользовательская функция (неподдерживаемая функция).|
| [type](/cells/python-net/ru/aspose.cells/cell/type) | Представляет тип значения ячейки.|
| [name](/cells/python-net/ru/aspose.cells/cell/name) | Получает имя ячейки.|
| [is_error_value](/cells/python-net/ru/aspose.cells/cell/is_error_value) | Проверяет, является ли значение данной ячейки ошибкой.|
| [is_numeric_value](/cells/python-net/ru/aspose.cells/cell/is_numeric_value) | Указывает, является ли значение этой ячейки числовым (int, double и datetime)|
| [string_value](/cells/python-net/ru/aspose.cells/cell/string_value) | Возвращает строковое значение, содержащееся в ячейке. Если тип ячейки — строка, возвращает само строковое значение.<br/>Для других типов ячеек будет возвращено форматированное строковое значение (отформатированное с использованием указанного стиля данной ячейки).<br/>Отформатированное значение ячейки такое же, как то, что вы можете получить из Excel при копировании ячейки как текста (например,<br/> копирование ячейки в текстовый редактор или экспорт в csv).|
| [string_value_without_format](/cells/python-net/ru/aspose.cells/cell/string_value_without_format) | Получает значение ячейки в виде строки без какого-либо формата.|
| [number_category_type](/cells/python-net/ru/aspose.cells/cell/number_category_type) | Представляет тип категории числового форматирования этой ячейки.|
| [display_string_value](/cells/python-net/ru/aspose.cells/cell/display_string_value) | Получает отформатированное строковое значение этой ячейки по стилю отображения ячейки.|
| [int_value](/cells/python-net/ru/aspose.cells/cell/int_value) | Получает целое значение, содержащееся в ячейке.|
| [double_value](/cells/python-net/ru/aspose.cells/cell/double_value) | Получает двойное значение, содержащееся в ячейке.|
| [float_value](/cells/python-net/ru/aspose.cells/cell/float_value) | Возвращает плавающее значение, содержащееся в ячейке.|
| [bool_value](/cells/python-net/ru/aspose.cells/cell/bool_value) | Получает логическое значение, содержащееся в ячейке.|
| [has_custom_style](/cells/python-net/ru/aspose.cells/cell/has_custom_style) | Указывает, имеет ли эта ячейка пользовательские настройки стиля (отличные от унаследованных по умолчанию<br/>из соответствующей строки, столбца или рабочей книги).|
| [shared_style_index](/cells/python-net/ru/aspose.cells/cell/shared_style_index) | Получает общий индекс стиля ячейки в пуле стилей.|
| [formula](/cells/python-net/ru/aspose.cells/cell/formula) | Получает или задает формулу [`Cell`](/cells/python-net/ru/aspose.cells/cell).|
| [formula_local](/cells/python-net/ru/aspose.cells/cell/formula_local) | Получите формулу ячейки, отформатированную в соответствии с локалью.|
| [r1c1_formula](/cells/python-net/ru/aspose.cells/cell/r1c1_formula) | Получает или задает формулу R1C1 для [`Cell`](/cells/python-net/ru/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/ru/aspose.cells/cell/contains_external_link) | Указывает, содержит ли эта ячейка внешнюю ссылку.<br/> Применяется только в том случае, если ячейка является ячейкой формулы.|
| [is_array_header](/cells/python-net/ru/aspose.cells/cell/is_array_header) | Указывает, что формула ячейки является формулой массива.<br/> и это первая ячейка массива.|
| [is_dynamic_array_formula](/cells/python-net/ru/aspose.cells/cell/is_dynamic_array_formula) | Указывает, является ли формула ячейки динамической формулой массива (истина) или устаревшей формулой массива (ложь).|
| [is_array_formula](/cells/python-net/ru/aspose.cells/cell/is_array_formula) | Указывает, является ли формула ячейки формулой массива.|
| [is_in_array](/cells/python-net/ru/aspose.cells/cell/is_in_array) | Указывает, является ли формула ячейки формулой массива.|
| [is_shared_formula](/cells/python-net/ru/aspose.cells/cell/is_shared_formula) | Указывает, является ли формула ячейки частью общей формулы.|
| [is_table_formula](/cells/python-net/ru/aspose.cells/cell/is_table_formula) | Указывает, является ли эта ячейка частью формулы таблицы.|
| [is_in_table](/cells/python-net/ru/aspose.cells/cell/is_in_table) | Указывает, является ли эта ячейка частью формулы таблицы.|
| [value](/cells/python-net/ru/aspose.cells/cell/value) | Получает/задает значение, содержащееся в этой ячейке.|
| [is_style_set](/cells/python-net/ru/aspose.cells/cell/is_style_set) | Указывает, задан ли стиль ячейки. Если возвращается значение false, это означает, что ячейка имеет формат по умолчанию.|
| [is_merged](/cells/python-net/ru/aspose.cells/cell/is_merged) | Проверяет, является ли ячейка частью объединенного диапазона.|
| [comment](/cells/python-net/ru/aspose.cells/cell/comment) |Получает комментарий этой ячейки.|
| [html_string](/cells/python-net/ru/aspose.cells/cell/html_string) | Получает и задает HTML-строку, содержащую данные и некоторые форматы в этой ячейке.|
| [is_check_box_style](/cells/python-net/ru/aspose.cells/cell/is_check_box_style) | Указывает, установлена ли эта ячейка как флажок.|
| [embedded_image](/cells/python-net/ru/aspose.cells/cell/embedded_image) | Получает и задает встроенное изображение в ячейке.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/ru/aspose.cells/cell/put_value/#bool) | Помещает в ячейку логическое значение.|
| [`put_value(self, int_value)`](/cells/python-net/ru/aspose.cells/cell/put_value/#int) | Помещает в ячейку целочисленное значение.|
| [`put_value(self, double_value)`](/cells/python-net/ru/aspose.cells/cell/put_value/#float) | Помещает в ячейку двойное значение.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/ru/aspose.cells/cell/put_value/#str-bool-bool) | Помещает значение в ячейку, при необходимости значение будет преобразовано в другой тип данных, а числовой формат ячейки будет сброшен.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/ru/aspose.cells/cell/put_value/#str-bool) | Помещает строковое значение в ячейку и при необходимости преобразует значение в другой тип данных.|
| [`put_value(self, string_value)`](/cells/python-net/ru/aspose.cells/cell/put_value/#str) | Помещает строковое значение в ячейку.|
| [`put_value(self, date_time)`](/cells/python-net/ru/aspose.cells/cell/put_value/#datetime) | Помещает значение DateTime в ячейку.|
| [`put_value(self, object_value)`](/cells/python-net/ru/aspose.cells/cell/put_value/#any) | Помещает значение объекта в ячейку.|
| [`get_display_style(self)`](/cells/python-net/ru/aspose.cells/cell/get_display_style/#) | Получает стиль отображения этой ячейки.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/ru/aspose.cells/cell/get_display_style/#bool) | Получает стиль отображения этой ячейки.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/ru/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Получает стиль отображения этой ячейки.|
| [`get_style(self)`](/cells/python-net/ru/aspose.cells/cell/get_style/#) | Получает стиль ячейки.|
| [`get_style(self, check_borders)`](/cells/python-net/ru/aspose.cells/cell/get_style/#bool) | Если checkBorders имеет значение true, проверьте, повлияют ли границы других ячеек на стиль этой ячейки.|
| [`set_style(self, style)`](/cells/python-net/ru/aspose.cells/cell/set_style/#aspose.cells.style) | Задает стиль ячейки.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/ru/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Применить измененное свойство стиля к ячейке.|
| [`set_style(self, style, flag)`](/cells/python-net/ru/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Применить стиль ячеек на основе флагов.|
| [`set_formula(self, formula, value)`](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-any) | Задайте формулу и значение (вычисленный результат) формулы.|
| [`set_formula(self, formula, options)`](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Задайте формулу и значение (вычисленный результат) формулы.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-bool-bool-any) | Задайте формулу и значение формулы.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/ru/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Задайте формулу и значение (вычисленный результат) формулы.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Устанавливает формулу массива для диапазона ячеек.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int) | Устанавливает формулу массива (устаревшую формулу массива, введенную с помощью CTRL+SHIFT+ENTER в MS Excel) для диапазона ячеек.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Устанавливает формулу массива для диапазона ячеек.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/ru/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Устанавливает формулу массива для диапазона ячеек.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Устанавливает формулу для диапазона ячеек.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int) | Устанавливает общие формулы для диапазона ячеек.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Устанавливает общие формулы для диапазона ячеек.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/ru/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Устанавливает общие формулы для диапазона ячеек.|
| [`get_leafs(self)`](/cells/python-net/ru/aspose.cells/cell/get_leafs/#) | Получить все ячейки, которые напрямую ссылаются на данную ячейку и должны быть обновлены при изменении данной ячейки.|
| [`get_leafs(self, recursive)`](/cells/python-net/ru/aspose.cells/cell/get_leafs/#bool) | Получить все ячейки, которые будут обновлены при изменении данной ячейки.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/ru/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Задает динамическую формулу массива и заставляет формулу распространяться на соседние ячейки, если это возможно.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/ru/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Задает динамическую формулу массива и заставляет формулу распространяться на соседние ячейки, если это возможно.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/ru/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Задает динамическую формулу массива и заставляет формулу распространяться на соседние ячейки, если это возможно.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Создать таблицу данных с двумя переменными для заданного диапазона, начиная с этой ячейки.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Создать таблицу данных с одной переменной для заданного диапазона, начиная с этой ячейки.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Создать таблицу данных с двумя переменными для заданного диапазона, начиная с этой ячейки.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/ru/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Создать таблицу данных с одной переменной для заданного диапазона, начиная с этой ячейки.|
| [`get_characters(self)`](/cells/python-net/ru/aspose.cells/cell/get_characters/#) | Возвращает все объекты Characters<br/> который представляет собой диапазон символов в тексте ячейки.|
| [`get_characters(self, flag)`](/cells/python-net/ru/aspose.cells/cell/get_characters/#bool) | Возвращает все объекты Characters<br/> который представляет собой диапазон символов в тексте ячейки.|
| [`calculate(self, options)`](/cells/python-net/ru/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Вычисляет формулу ячейки.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/ru/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Получает строковое значение по определенной отформатированной стратегии.|
| [`get_width_of_value(self)`](/cells/python-net/ru/aspose.cells/cell/get_width_of_value/#) | Получает ширину значения в пикселях.|
| [`get_height_of_value(self)`](/cells/python-net/ru/aspose.cells/cell/get_height_of_value/#) | Получает высоту значения в пикселях.|
| [`get_format_conditions(self)`](/cells/python-net/ru/aspose.cells/cell/get_format_conditions/#) | Получает условия форматирования, применяемые к этой ячейке.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/cell/get_formula/#bool-bool) | Получите формулу этой ячейки.|
| [`get_precedents(self)`](/cells/python-net/ru/aspose.cells/cell/get_precedents/#) | Получает все ссылки, встречающиеся в формуле этой ячейки.|
| [`get_dependents(self, is_all)`](/cells/python-net/ru/aspose.cells/cell/get_dependents/#bool) | Получить все ячейки, формула которых напрямую ссылается на эту ячейку.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/ru/aspose.cells/cell/get_precedents_in_calculation/#) | Возвращает все прецеденты (ссылки на ячейки в текущей книге), используемые формулой этой ячейки при ее вычислении.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation/#bool) | Получает все ячейки, вычисленный результат которых зависит от этой ячейки.|
| [`get_array_range(self)`](/cells/python-net/ru/aspose.cells/cell/get_array_range/#) | Возвращает диапазон массива, если формула ячейки является формулой массива.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/ru/aspose.cells/cell/remove_array_formula/#bool) | Удалить формулу массива.|
| [`copy(self, cell)`](/cells/python-net/ru/aspose.cells/cell/copy/#aspose.cells.cell) | Копирует данные из исходной ячейки.|
| [`characters(self, start_index, length)`](/cells/python-net/ru/aspose.cells/cell/characters/#int-int) | Возвращает объект Characters, представляющий диапазон символов в тексте ячейки.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/ru/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Заменить текст ячейки параметрами.|
| [`insert_text(self, index, text)`](/cells/python-net/ru/aspose.cells/cell/insert_text/#int-str) | Вставьте несколько символов в ячейку.<br/> Если ячейка имеет расширенный формат, этот метод может сохранить исходное форматирование.|
| [`is_rich_text(self)`](/cells/python-net/ru/aspose.cells/cell/is_rich_text/#) |Указывает, является ли строковое значение этой ячейки текстом в расширенном формате.|
| [`set_characters(self, characters)`](/cells/python-net/ru/aspose.cells/cell/set_characters/#list) | Устанавливает расширенный текстовый формат ячейки.|
| [`get_merged_range(self)`](/cells/python-net/ru/aspose.cells/cell/get_merged_range/#) | Возвращает объект [`Range`](/cells/python-net/ru/aspose.cells/range), представляющий объединенный диапазон.|
| [`get_html_string(self, html5)`](/cells/python-net/ru/aspose.cells/cell/get_html_string/#bool) | Получает HTML-строку, содержащую данные и некоторые форматы в этой ячейке.|
| [`to_json(self)`](/cells/python-net/ru/aspose.cells/cell/to_json/#) | Преобразовать структурные данные [`Cell`](/cells/python-net/ru/aspose.cells/cell) в JSON.|
| [`equals(self, cell)`](/cells/python-net/ru/aspose.cells/cell/equals/#aspose.cells.cell) | Проверяет, ссылается ли данный объект на ту же ячейку, что и другой объект ячейки.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/ru/aspose.cells/cell/get_conditional_formatting_result/#) | Получите результат условного форматирования.|
| [`get_validation(self)`](/cells/python-net/ru/aspose.cells/cell/get_validation/#) | Получает проверку, примененную к этой ячейке.|
| [`get_validation_value(self)`](/cells/python-net/ru/aspose.cells/cell/get_validation_value/#) | Получает значение проверки, примененной к этой ячейке.|
| [`get_table(self)`](/cells/python-net/ru/aspose.cells/cell/get_table/#) | Получает таблицу, содержащую эту ячейку.|
| [`get_rich_value(self)`](/cells/python-net/ru/aspose.cells/cell/get_rich_value/#) | Получает богатое значение ячейки.|



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
