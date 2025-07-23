---
title: ListObject класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject класс
Представляет объект списка на рабочем листе.
 Объект ListObject является членом коллекции ListObjects.
Коллекция ListObjects содержит все объекты списка на рабочем листе.



Тип ListObject предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [start_row](/cells/python-net/ru/aspose.cells.tables/listobject/start_row) | Получает начальную строку диапазона.|
| [start_column](/cells/python-net/ru/aspose.cells.tables/listobject/start_column) | Получает начальный столбец диапазона.|
| [end_row](/cells/python-net/ru/aspose.cells.tables/listobject/end_row) | Получает конечную строку диапазона.|
| [end_column](/cells/python-net/ru/aspose.cells.tables/listobject/end_column) | Получает конечный столбец диапазона.|
| [list_columns](/cells/python-net/ru/aspose.cells.tables/listobject/list_columns) | Получает ListColumns объекта ListObject.|
| [show_header_row](/cells/python-net/ru/aspose.cells.tables/listobject/show_header_row) | Возвращает и задает, отображать ли этот ListObject строку заголовка.|
| [show_totals](/cells/python-net/ru/aspose.cells.tables/listobject/show_totals) | Возвращает и задает, отображать ли этот ListObject итоговую строку.|
| [data_range](/cells/python-net/ru/aspose.cells.tables/listobject/data_range) | Получает диапазон данных ListObject.|
| [query_table](/cells/python-net/ru/aspose.cells.tables/listobject/query_table) | Получает связанную QueryTable.|
| [data_source_type](/cells/python-net/ru/aspose.cells.tables/listobject/data_source_type) |Получает тип источника данных таблицы.|
| [auto_filter](/cells/python-net/ru/aspose.cells.tables/listobject/auto_filter) | Получает автоматический фильтр.|
| [display_name](/cells/python-net/ru/aspose.cells.tables/listobject/display_name) | Получает и задает отображаемое имя.|
| [comment](/cells/python-net/ru/aspose.cells.tables/listobject/comment) | Получает и задает комментарий к таблице.|
| [show_table_style_first_column](/cells/python-net/ru/aspose.cells.tables/listobject/show_table_style_first_column) | Указывает, следует ли применять стиль к первому столбцу таблицы.|
| [show_table_style_last_column](/cells/python-net/ru/aspose.cells.tables/listobject/show_table_style_last_column) | Указывает, следует ли применять стиль к последнему столбцу таблицы.|
| [show_table_style_row_stripes](/cells/python-net/ru/aspose.cells.tables/listobject/show_table_style_row_stripes) | Указывает, применяется ли форматирование полос строк.|
| [show_table_style_column_stripes](/cells/python-net/ru/aspose.cells.tables/listobject/show_table_style_column_stripes) | Указывает, применяется ли форматирование полос столбцов.|
| [table_style_type](/cells/python-net/ru/aspose.cells.tables/listobject/table_style_type) | Получает и встроенный стиль таблицы.|
| [table_style_name](/cells/python-net/ru/aspose.cells.tables/listobject/table_style_name) | Получает и задает имя стиля таблицы.|
| [xml_map](/cells/python-net/ru/aspose.cells.tables/listobject/xml_map) | Получает [`ListObject.xml_map`](/cells/python-net/ru/aspose.cells.tables/listobject#xml_map), используемый для этого списка.|
| [alternative_text](/cells/python-net/ru/aspose.cells.tables/listobject/alternative_text) | Получает и задает альтернативный текст.|
| [alternative_description](/cells/python-net/ru/aspose.cells.tables/listobject/alternative_description) | Получает и задает альтернативное описание.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/ru/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Введите значение в ячейку.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/ru/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Введите значение в ячейку.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/ru/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Вставьте формулу в ячейку таблицы.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/ru/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Вставьте формулу в ячейку таблицы.|
| [`convert_to_range(self)`](/cells/python-net/ru/aspose.cells.tables/listobject/convert_to_range/#) | Преобразовать таблицу в диапазон.|
| [`convert_to_range(self, options)`](/cells/python-net/ru/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Преобразовать таблицу в диапазон.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/ru/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Измените размер диапазона объекта списка.|
| [`update_column_name(self)`](/cells/python-net/ru/aspose.cells.tables/listobject/update_column_name/#) | Обновляет имена всех столбцов списка на листе.|
| [`filter(self)`](/cells/python-net/ru/aspose.cells.tables/listobject/filter/#) | Отфильтруйте таблицу.|
| [`apply_style_to_range(self)`](/cells/python-net/ru/aspose.cells.tables/listobject/apply_style_to_range/#) | Применить стиль таблицы к диапазону.|



###  Пример

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.tables`](..)
