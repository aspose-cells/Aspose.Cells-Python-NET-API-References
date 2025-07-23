---
title: AutoFilter класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter класс
Представляет собой автофильтрацию для указанного рабочего листа.



Тип AutoFilter предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [sorter](/cells/python-net/ru/aspose.cells/autofilter/sorter) | Получает сортировщик данных.|
| [range](/cells/python-net/ru/aspose.cells/autofilter/range) | Представляет диапазон, к которому применяется указанный автофильтр.|
| [show_filter_button](/cells/python-net/ru/aspose.cells/autofilter/show_filter_button) | Указывает, видна ли кнопка «Автофильтр» для этого столбца.|
| [filter_columns](/cells/python-net/ru/aspose.cells/autofilter/filter_columns) | Получает коллекцию столбцов фильтра.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/ru/aspose.cells/autofilter/get_cell_area/#) | Получает [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea), к которому применяется этот автофильтр.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/ru/aspose.cells/autofilter/get_cell_area/#bool) | Возвращает [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea), к которому применяется указанный автофильтр.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/ru/aspose.cells/autofilter/remove_filter/#int-str) | Удаляет фильтр для столбца фильтра.|
| [`remove_filter(self, field_index)`](/cells/python-net/ru/aspose.cells/autofilter/remove_filter/#int) | Удалить конкретный фильтр.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/ru/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Фильтрует список по пользовательским критериям.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/ru/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Фильтрует список по пользовательским критериям.|
| [`refresh(self)`](/cells/python-net/ru/aspose.cells/autofilter/refresh/#) | Обновите автоматические фильтры, чтобы скрыть или отобразить строки.|
| [`refresh(self, hide_rows)`](/cells/python-net/ru/aspose.cells/autofilter/refresh/#bool) | Получает индексы всех скрытых строк.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/ru/aspose.cells/autofilter/set_range/#int-int-int) | Задает диапазон, к которому применяется указанный автофильтр.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/ru/aspose.cells/autofilter/add_filter/#int-str) | Добавляет фильтр для столбца фильтра.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/ru/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Добавляет фильтр по дате.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/ru/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Удаляет фильтр по дате.|
| [`filter(self, field_index, criteria)`](/cells/python-net/ru/aspose.cells/autofilter/filter/#int-str) | Фильтрует список по указанным критериям.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/ru/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Фильтрация 10 лучших элементов в списке|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/ru/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Добавляет динамический фильтр.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/ru/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Добавляет фильтр цвета шрифта.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/ru/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Добавляет фильтр цвета заливки.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/ru/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Добавляет фильтр значков.|
| [`match_blanks(self, field_index)`](/cells/python-net/ru/aspose.cells/autofilter/match_blanks/#int) | Совпадение со всеми пустыми ячейками в списке.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/ru/aspose.cells/autofilter/match_non_blanks/#int) | Совпасть со всеми непустыми ячейками в списке.|
| [`show_all(self)`](/cells/python-net/ru/aspose.cells/autofilter/show_all/#) | Показать все строки.|



###  Пример

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea)
