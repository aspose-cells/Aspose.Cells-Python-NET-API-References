---
title: Area класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.drawing/area/
is_root: false
---
##  Area класс
Инкапсулирует объект, представляющий формат области.



Тип Area предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [background_color](/cells/python-net/ru/aspose.cells.drawing/area/background_color) | Получает или задает цвет фона для [`Area`](/cells/python-net/ru/aspose.cells.drawing/area).|
| [foreground_color](/cells/python-net/ru/aspose.cells.drawing/area/foreground_color) | Получает или задает цвет переднего плана.|
| [formatting](/cells/python-net/ru/aspose.cells.drawing/area/formatting) | Представляет форматирование области.|
| [invert_if_negative](/cells/python-net/ru/aspose.cells.drawing/area/invert_if_negative) | Если свойство истинно и значение точки диаграммы — отрицательное число,<br/> цвет переднего плана и цвет фона поменяются местами.|
| [fill_format](/cells/python-net/ru/aspose.cells.drawing/area/fill_format) | Представляет объект [`Area.fill_format`](/cells/python-net/ru/aspose.cells.drawing/area#fill_format), содержащий свойства форматирования заливки для указанной диаграммы или фигуры.|
| [transparency](/cells/python-net/ru/aspose.cells.drawing/area/transparency) |Возвращает или задает степень прозрачности области как значение от 0,0 (непрозрачная) до 1,0 (прозрачная).|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
# Setting the foreground color of the plot area
chart.plot_area.area.foreground_color = Color.blue
# Setting the foreground color of the chart area
chart.chart_area.area.foreground_color = Color.yellow
# Setting the foreground color of the 1st NSeries area
chart.n_series[0].area.foreground_color = Color.red
# Setting the foreground color of the area of the 1st NSeries point
chart.n_series[0].points[0].area.foreground_color = Color.cyan
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`Area`](/cells/python-net/ru/aspose.cells.drawing/area)
