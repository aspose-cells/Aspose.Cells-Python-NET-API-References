---
title: TrendlineCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 350
url: /ru/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection класс
Представляет коллекцию всех объектов [`Trendline`](/cells/python-net/ru/aspose.cells.charts/trendline) для указанного ряда данных.



Тип TrendlineCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType) | Добавляет в эту коллекцию объект [`Trendline`](/cells/python-net/ru/aspose.cells.charts/trendline) указанного типа.|
| [add](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType-str) | Добавляет в эту коллекцию объект [`Trendline`](/cells/python-net/ru/aspose.cells.charts/trendline) с указанным типом и именем.|
| [copy_to](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [binary_search](/cells/python-net/ru/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.Trendline) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`Trendline`](/cells/python-net/ru/aspose.cells.charts/trendline)
