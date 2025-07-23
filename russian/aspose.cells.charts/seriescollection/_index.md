---
title: SeriesCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 250
url: /ru/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection класс
Инкапсулирует коллекцию из [`Series`](/cells/python-net/ru/aspose.cells.charts/series) объектов.



Тип SeriesCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [category_data](/cells/python-net/ru/aspose.cells.charts/seriescollection/category_data) | Возвращает или задает диапазон значений оси категории.<br/> Это может быть диапазон ячеек (например, «d1:e10»),<br/> или последовательность значений (например, "{2,6,8,10}").|
| [second_category_data](/cells/python-net/ru/aspose.cells.charts/seriescollection/second_category_data) | Возвращает или задает диапазон значений оси второй категории.<br/> Это может быть диапазон ячеек (например, «d1:e10»),<br/> или последовательность значений (например, "{2,6,8,10}").<br/> Действует только в том случае, если некоторые ASeries построены на второй оси.|
| [is_color_varied](/cells/python-net/ru/aspose.cells.charts/seriescollection/is_color_varied) | Показывает, является ли цвет точек разным.|
| [capacity](/cells/python-net/ru/aspose.cells.charts/seriescollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, area, is_vertical)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/add/#str-bool) | Добавляет коллекцию [`Series`](/cells/python-net/ru/aspose.cells.charts/series) в диаграмму.|
| [`add(self, area, is_vertical, check_labels)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/add/#str-bool-bool) | Добавляет коллекцию [`Series`](/cells/python-net/ru/aspose.cells.charts/series) в диаграмму.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get_series_by_order(self, order)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/get_series_by_order/#int) | Получает элемент [`Series`](/cells/python-net/ru/aspose.cells.charts/series) по порядку.|
| [`change_series_order(self, source_index, dest_index)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/change_series_order/#int-int) | Напрямую изменяет порядок двух серий.|
| [`swap_series(self, source_index, dest_index)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/swap_series/#int-int) | Напрямую изменяет порядок двух серий.|
| [`set_series_names(self, start_index, area, is_vertical)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Задает название всех серий в диаграмме.|
| [`add_r1c1(self, area, is_vertical)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | Добавляет коллекцию [`Series`](/cells/python-net/ru/aspose.cells.charts/series) в диаграмму.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.series) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`Series`](/cells/python-net/ru/aspose.cells.charts/series)
