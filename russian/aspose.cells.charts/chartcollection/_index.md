---
title: ChartCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection класс
Инкапсулирует коллекцию из [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart) объектов.



Тип ChartCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.charts/chartcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Добавляет диаграмму с предустановленным шаблоном.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [`get(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/get/#int) | Добавьте API for Python через .Net.since this[int index] не поддерживается|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/get/#str) | Добавьте API for Python через .Net.since this[string Chart] is not supported|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart)
