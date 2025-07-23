---
title: SparklineGroupCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 300
url: /ru/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection класс
Инкапсулирует коллекцию из [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup) объектов.



Тип SparklineGroupCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, type)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | Добавляет в коллекцию [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup) с [`Sparkline`](/cells/python-net/ru/aspose.cells.charts/sparkline).|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | Добавляет [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup) с [`Sparkline`](/cells/python-net/ru/aspose.cells.charts/sparkline) в коллекцию.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | Очищает искрографики, находящиеся внутри области ячеек.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | Очищает группы спарклайнов, перекрывающие область ячеек.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`Sparkline`](/cells/python-net/ru/aspose.cells.charts/sparkline)
* класс [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup)
