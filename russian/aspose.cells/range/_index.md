---
title: Range класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1180
url: /ru/aspose.cells/range/
is_root: false
---
##  Range класс
Инкапсулирует объект, представляющий диапазон ячеек в электронной таблице.



Тип Range предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [current_region](/cells/python-net/ru/aspose.cells/range/current_region) | Возвращает объект Range, представляющий текущий регион.<br/> Текущая область — это диапазон, ограниченный любой комбинацией пустых строк и пустых столбцов.|
| [hyperlinks](/cells/python-net/ru/aspose.cells/range/hyperlinks) | Получает все гиперссылки в диапазоне.|
| [row_count](/cells/python-net/ru/aspose.cells/range/row_count) | Получает количество строк в диапазоне.|
| [column_count](/cells/python-net/ru/aspose.cells/range/column_count) | Получает количество столбцов в диапазоне.|
| [name](/cells/python-net/ru/aspose.cells/range/name) | Получает или задает имя диапазона.|
| [refers_to](/cells/python-net/ru/aspose.cells/range/refers_to) | Получает диапазон, на который ссылается.|
| [address](/cells/python-net/ru/aspose.cells/range/address) | Получает адрес диапазона.|
| [left](/cells/python-net/ru/aspose.cells/range/left) | Получает расстояние в точках от левого края столбца A до левого края диапазона.|
| [top](/cells/python-net/ru/aspose.cells/range/top) | Получает расстояние в точках от верхнего края строки 1 до верхнего края диапазона.|
| [width](/cells/python-net/ru/aspose.cells/range/width) | Получает ширину диапазона в пунктах.|
| [height](/cells/python-net/ru/aspose.cells/range/height) | Получает ширину диапазона в пунктах.|
| [first_row](/cells/python-net/ru/aspose.cells/range/first_row) | Получает индекс первой строки диапазона.|
| [first_column](/cells/python-net/ru/aspose.cells/range/first_column) | Получает индекс первого столбца диапазона.|
| [value](/cells/python-net/ru/aspose.cells/range/value) | Получает и задает значение диапазона.|
| [column_width](/cells/python-net/ru/aspose.cells/range/column_width) | Устанавливает или получает ширину столбца этого диапазона|
| [row_height](/cells/python-net/ru/aspose.cells/range/row_height) | Устанавливает или получает высоту строк в этом диапазоне|
| [entire_column](/cells/python-net/ru/aspose.cells/range/entire_column) |Возвращает объект Range, представляющий весь столбец (или столбцы), содержащий указанный диапазон.|
| [entire_row](/cells/python-net/ru/aspose.cells/range/entire_row) | Возвращает объект Range, представляющий всю строку (или строки), содержащую указанный диапазон.|
| [worksheet](/cells/python-net/ru/aspose.cells/range/worksheet) | Получает объект [`Range.worksheet`](/cells/python-net/ru/aspose.cells/range#worksheet), содержащий этот диапазон.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/ru/aspose.cells/range/auto_fill/#aspose.cells.range) | Автоматически заполнить целевой диапазон.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/ru/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Автоматически заполнить целевой диапазон.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/ru/aspose.cells/range/set_style/#aspose.cells.style-bool) | Примените стиль ячейки.|
| [`set_style(self, style)`](/cells/python-net/ru/aspose.cells/range/set_style/#aspose.cells.style) | Задает стиль диапазона.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/ru/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Устанавливает границы контура вокруг диапазона ячеек с одинаковым стилем и цветом границ.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/ru/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Устанавливает границы контура вокруг диапазона ячеек с одинаковым стилем и цветом границ.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/ru/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Устанавливает границы линий вокруг диапазона ячеек.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/ru/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Устанавливает границу контура вокруг диапазона ячеек.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/ru/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Устанавливает границу контура вокруг диапазона ячеек.|
| [`copy(self, range, options)`](/cells/python-net/ru/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Копирование диапазона с использованием опций специальной вставки.|
| [`copy(self, range)`](/cells/python-net/ru/aspose.cells/range/copy/#aspose.cells.range) | Копирует данные (включая формулы), форматирование, объекты чертежей и т. д. из исходного диапазона.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/ru/aspose.cells/range/add_hyperlink/#str-str-str) | Добавляет гиперссылку к указанной ячейке или диапазону ячеек.|
| [`is_intersect(self, range)`](/cells/python-net/ru/aspose.cells/range/is_intersect/#aspose.cells.range) | Указывает, пересекается ли диапазон.|
| [`intersect(self, range)`](/cells/python-net/ru/aspose.cells/range/intersect/#aspose.cells.range) | Возвращает объект [`Range`](/cells/python-net/ru/aspose.cells/range), представляющий собой прямоугольное пересечение двух диапазонов.|
| [`union_rang(self, range)`](/cells/python-net/ru/aspose.cells/range/union_rang/#aspose.cells.range) | Возвращает результат объединения двух диапазонов.|
| [`union_ranges(self, ranges)`](/cells/python-net/ru/aspose.cells/range/union_ranges/#list) | Возвращает результат объединения двух диапазонов.|
| [`union(self, range)`](/cells/python-net/ru/aspose.cells/range/union/#aspose.cells.range) | Возвращает объединение двух диапазонов.|
| [`is_blank(self)`](/cells/python-net/ru/aspose.cells/range/is_blank/#) | Указывает, содержит ли диапазон значения.|
| [`merge(self)`](/cells/python-net/ru/aspose.cells/range/merge/#) |Объединяет ряд ячеек в одну ячейку.|
| [`un_merge(self)`](/cells/python-net/ru/aspose.cells/range/un_merge/#) | Разделяет объединенные ячейки данного диапазона.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/ru/aspose.cells/range/put_value/#str-bool-bool) | Помещает значение в диапазон, при необходимости значение будет преобразовано в другой тип данных, а числовой формат ячейки будет сброшен.|
| [`apply_style(self, style, flag)`](/cells/python-net/ru/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Применяет форматы для всего диапазона.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/ru/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Установить внутри границ диапазона.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/ru/aspose.cells/range/move_to/#int-int) | Переместить текущий диапазон в целевой диапазон.|
| [`copy_data(self, range)`](/cells/python-net/ru/aspose.cells/range/copy_data/#aspose.cells.range) | Копирует данные ячеек (включая формулы) из исходного диапазона.|
| [`copy_value(self, range)`](/cells/python-net/ru/aspose.cells/range/copy_value/#aspose.cells.range) | Копирует значение ячейки из исходного диапазона.|
| [`copy_style(self, range)`](/cells/python-net/ru/aspose.cells/range/copy_style/#aspose.cells.range) | Копирует настройки стиля из исходного диапазона.|
| [`transpose(self)`](/cells/python-net/ru/aspose.cells/range/transpose/#) | Транспонировать (повернуть) данные из строк в столбцы и наоборот.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/ru/aspose.cells/range/get/#int-int) | Добавьте API for Python через .Net.since this[int, int] не поддерживается|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/ru/aspose.cells/range/get_cell_or_null/#int-int) | Получает объект [`Cell`](/cells/python-net/ru/aspose.cells/cell) или значение NULL в этом диапазоне.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/ru/aspose.cells/range/get_offset/#int-int) | Получает диапазон [`Range`](/cells/python-net/ru/aspose.cells/range) по смещению.|
| [`to_image(self, options)`](/cells/python-net/ru/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Преобразует диапазон в изображение.|
| [`to_json(self, options)`](/cells/python-net/ru/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Преобразовать диапазон в значение JSON.|
| [`to_html(self, save_options)`](/cells/python-net/ru/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Конвертировать диапазон в html.|
| [`clear(self)`](/cells/python-net/ru/aspose.cells/range/clear/#) | Очищает этот диапазон.|
| [`clear_contents(self)`](/cells/python-net/ru/aspose.cells/range/clear_contents/#) | Очищает содержимое этого диапазона.|
| [`clear_formats(self)`](/cells/python-net/ru/aspose.cells/range/clear_formats/#) | Очищает форматы этого диапазона.|
| [`clear_comments(self)`](/cells/python-net/ru/aspose.cells/range/clear_comments/#) | Очищает комментарии этого диапазона.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/ru/aspose.cells/range/clear_hyperlinks/#bool) | Удаляет только гиперссылки.|



###  Примечания

Класс Range обозначает область электронной таблицы Excel.
С его помощью можно форматировать и задавать значение диапазона.
И вы также можете просто скопировать диапазон Excel.

###  Пример

В следующем примере показано, как создать диапазон и задать значение диапазона Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
