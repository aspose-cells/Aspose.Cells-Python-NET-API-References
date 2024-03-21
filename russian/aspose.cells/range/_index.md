---
title: Range класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1290
url: /ru/aspose.cells/range/
is_root: false
---
##  Range класс
Инкапсулирует объект, представляющий диапазон ячеек в электронной таблице.



Тип Range предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [current_region](/cells/python-net/ru/aspose.cells/range/current_region) |Возвращает объект Range, представляющий текущий регион.<br/> Текущий регион представляет собой диапазон, ограниченный любой комбинацией пустых строк и пустых столбцов.|
| [hyperlinks](/cells/python-net/ru/aspose.cells/range/hyperlinks) | Получает все гиперссылки в диапазоне.|
| [row_count](/cells/python-net/ru/aspose.cells/range/row_count) | Получает количество строк в диапазоне.|
| [column_count](/cells/python-net/ru/aspose.cells/range/column_count) | Получает количество столбцов в диапазоне.|
| [name](/cells/python-net/ru/aspose.cells/range/name) | Получает или задает имя диапазона.|
| [refers_to](/cells/python-net/ru/aspose.cells/range/refers_to) | Получает ссылку на диапазон.|
| [address](/cells/python-net/ru/aspose.cells/range/address) | Получает адрес диапазона.|
| [left](/cells/python-net/ru/aspose.cells/range/left) | Получает расстояние в пунктах от левого края столбца A до левого края диапазона.|
| [top](/cells/python-net/ru/aspose.cells/range/top) | Получает расстояние в пунктах от верхнего края строки 1 до верхнего края диапазона.|
| [width](/cells/python-net/ru/aspose.cells/range/width) | Получает ширину диапазона в пунктах.|
| [height](/cells/python-net/ru/aspose.cells/range/height) | Получает ширину диапазона в пунктах.|
| [first_row](/cells/python-net/ru/aspose.cells/range/first_row) | Получает индекс первой строки диапазона.|
| [first_column](/cells/python-net/ru/aspose.cells/range/first_column) | Получает индекс первого столбца диапазона.|
| [value](/cells/python-net/ru/aspose.cells/range/value) | Получает и задает значение диапазона.|
| [column_width](/cells/python-net/ru/aspose.cells/range/column_width) | Устанавливает или получает ширину столбца этого диапазона.|
| [row_height](/cells/python-net/ru/aspose.cells/range/row_height) | Устанавливает или получает высоту строк в этом диапазоне|
| [entire_column](/cells/python-net/ru/aspose.cells/range/entire_column) | Получает объект Range, представляющий весь столбец (или столбцы), содержащий указанный диапазон.|
| [entire_row](/cells/python-net/ru/aspose.cells/range/entire_row) |Получает объект Range, представляющий всю строку (или строки), содержащую указанный диапазон.|
| [worksheet](/cells/python-net/ru/aspose.cells/range/worksheet) | Получает объект [`Range.worksheet`](/cells/python-net/ru/aspose.cells/range#worksheet), содержащий этот диапазон.|


###  Методы
| Метод| Описание|
| :- | :- |
| [auto_fill](/cells/python-net/ru/aspose.cells/range/auto_fill/#aspose.cells.Range) | Автоматическое заполнение целевого диапазона.|
| [auto_fill](/cells/python-net/ru/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Автоматическое заполнение целевого диапазона.|
| [set_style](/cells/python-net/ru/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Примените стиль ячейки.|
| [set_style](/cells/python-net/ru/aspose.cells/range/set_style/#aspose.cells.Style) | Устанавливает стиль диапазона.|
| [set_outline_borders](/cells/python-net/ru/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Устанавливает контурные границы вокруг диапазона ячеек с одинаковым стилем и цветом границы.|
| [set_outline_borders](/cells/python-net/ru/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Устанавливает контурные границы вокруг диапазона ячеек с одинаковым стилем и цветом границы.|
| [set_outline_borders](/cells/python-net/ru/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Устанавливает границы линий вокруг диапазона ячеек.|
| [set_outline_border](/cells/python-net/ru/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Устанавливает контурную границу вокруг диапазона ячеек.|
| [set_outline_border](/cells/python-net/ru/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Устанавливает контурную границу вокруг диапазона ячеек.|
| [copy](/cells/python-net/ru/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Копирование диапазона со специальными параметрами вставки.|
| [copy](/cells/python-net/ru/aspose.cells/range/copy/#aspose.cells.Range) | Копирует данные (включая формулы), форматирование, рисование объектов и т. д. из исходного диапазона.|
| [add_hyperlink](/cells/python-net/ru/aspose.cells/range/add_hyperlink/#str-str-str) | Добавляет гиперссылку в указанную ячейку или диапазон ячеек.|
| [get_enumerator](/cells/python-net/ru/aspose.cells/range/get_enumerator/#) | Получает перечислитель для ячеек в этом диапазоне.|
| [is_intersect](/cells/python-net/ru/aspose.cells/range/is_intersect/#aspose.cells.Range) | Указывает, является ли диапазон пересечением.|
| [intersect](/cells/python-net/ru/aspose.cells/range/intersect/#aspose.cells.Range) | Возвращает объект [`Range`](/cells/python-net/ru/aspose.cells/range), представляющий прямоугольное пересечение двух диапазонов.|
| [union_rang](/cells/python-net/ru/aspose.cells/range/union_rang/#aspose.cells.Range) | Возвращает результат объединения двух диапазонов.|
| [union](/cells/python-net/ru/aspose.cells/range/union/#aspose.cells.Range) | Возвращает объединение двух диапазонов.|
| [is_blank](/cells/python-net/ru/aspose.cells/range/is_blank/#) | Указывает, содержит ли диапазон значения.|
| [merge](/cells/python-net/ru/aspose.cells/range/merge/#) | Объединяет диапазон ячеек в одну ячейку.|
| [un_merge](/cells/python-net/ru/aspose.cells/range/un_merge/#) |Разъединяет объединенные ячейки этого диапазона.|
| [put_value](/cells/python-net/ru/aspose.cells/range/put_value/#str-bool-bool) | Помещает значение в диапазон. При необходимости значение будет преобразовано в другой тип данных, а числовой формат ячейки будет сброшен.|
| [apply_style](/cells/python-net/ru/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Применяет форматы для всего диапазона.|
| [set_inside_borders](/cells/python-net/ru/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Устанавливается внутри границ диапазона.|
| [move_to](/cells/python-net/ru/aspose.cells/range/move_to/#int-int) | Переместить текущий диапазон в целевой диапазон.|
| [copy_data](/cells/python-net/ru/aspose.cells/range/copy_data/#aspose.cells.Range) | Копирует данные ячеек (включая формулы) из исходного диапазона.|
| [copy_value](/cells/python-net/ru/aspose.cells/range/copy_value/#aspose.cells.Range) | Копирует значение ячейки из исходного диапазона.|
| [copy_style](/cells/python-net/ru/aspose.cells/range/copy_style/#aspose.cells.Range) | Копирует настройки стиля из исходного диапазона.|
| [get_cell_or_null](/cells/python-net/ru/aspose.cells/range/get_cell_or_null/#int-int) | Получает объект [`Cell`](/cells/python-net/ru/aspose.cells/cell) или значение NULL в этом диапазоне.|
| [get_offset](/cells/python-net/ru/aspose.cells/range/get_offset/#int-int) | Получает диапазон [`Range`](/cells/python-net/ru/aspose.cells/range) по смещению.|



###  Примечания

Класс Range обозначает область электронной таблицы Excel.
Благодаря этому вы можете форматировать и устанавливать значение диапазона.
И вы также можете просто скопировать диапазон Excel.

###  Пример

В следующем примере показано, как создать диапазон и установить значение диапазона Excel.

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
