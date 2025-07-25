---
title: Line класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 270
url: /ru/aspose.cells.drawing/line/
is_root: false
---
##  Line класс
Инкапсулирует объект, представляющий формат строки.



Тип Line предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [compound_type](/cells/python-net/ru/aspose.cells.drawing/line/compound_type) | Указывает тип составной линии|
| [dash_type](/cells/python-net/ru/aspose.cells.drawing/line/dash_type) | Определяет тип пунктирной линии|
| [cap_type](/cells/python-net/ru/aspose.cells.drawing/line/cap_type) | Указывает конечные заглавные буквы.|
| [join_type](/cells/python-net/ru/aspose.cells.drawing/line/join_type) | Указывает соединительные заглушки.|
| [begin_type](/cells/python-net/ru/aspose.cells.drawing/line/begin_type) | Указывает стрелку в начале линии.|
| [end_type](/cells/python-net/ru/aspose.cells.drawing/line/end_type) | Задает стрелку в конце линии.|
| [begin_arrow_length](/cells/python-net/ru/aspose.cells.drawing/line/begin_arrow_length) | Задает длину стрелки в начале линии.|
| [end_arrow_length](/cells/python-net/ru/aspose.cells.drawing/line/end_arrow_length) | Задает длину стрелки на конце линии.|
| [begin_arrow_width](/cells/python-net/ru/aspose.cells.drawing/line/begin_arrow_width) | Задает ширину стрелки в начале линии.|
| [end_arrow_width](/cells/python-net/ru/aspose.cells.drawing/line/end_arrow_width) | Задает ширину стрелки на конце линии.|
| [theme_color](/cells/python-net/ru/aspose.cells.drawing/line/theme_color) | Получает и задает цвет темы.|
| [color](/cells/python-net/ru/aspose.cells.drawing/line/color) | Представляет цвет линии.|
| [transparency](/cells/python-net/ru/aspose.cells.drawing/line/transparency) | Возвращает или задает степень прозрачности линии как значение от 0,0 (непрозрачная) до 1,0 (прозрачная).|
| [style](/cells/python-net/ru/aspose.cells.drawing/line/style) | Представляет стиль линии.|
| [weight](/cells/python-net/ru/aspose.cells.drawing/line/weight) | Возвращает или задает [`WeightType`](/cells/python-net/ru/aspose.cells.drawing/weighttype) строки.|
| [weight_pt](/cells/python-net/ru/aspose.cells.drawing/line/weight_pt) |Возвращает или задает вес линии в точках.|
| [weight_px](/cells/python-net/ru/aspose.cells.drawing/line/weight_px) | Возвращает или задает вес линии в пикселях.|
| [formatting_type](/cells/python-net/ru/aspose.cells.drawing/line/formatting_type) | Получает или задает тип формата.|
| [is_automatic_color](/cells/python-net/ru/aspose.cells.drawing/line/is_automatic_color) | Указывает, назначается ли цвет линии автоматически.|
| [is_visible](/cells/python-net/ru/aspose.cells.drawing/line/is_visible) | Показывает, видна ли линия.|
| [is_auto](/cells/python-net/ru/aspose.cells.drawing/line/is_auto) | Указывает, назначается ли этот стиль линии автоматически.|
| [gradient_fill](/cells/python-net/ru/aspose.cells.drawing/line/gradient_fill) | Представляет собой градиентную заливку.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartMarkerType, ChartType
from aspose.cells.drawing import LineType, WeightType
from aspose.pydrawing import Color

workbook = Workbook()
sheet = workbook.worksheets[0]
cells = sheet.cells
cells.get(0, 1).put_value("Income")
cells.get(1, 0).put_value("Company A")
cells.get(2, 0).put_value("Company B")
cells.get(3, 0).put_value("Company C")
cells.get(1, 1).put_value(10000)
cells.get(2, 1).put_value(20000)
cells.get(3, 1).put_value(30000)
chartIndex = sheet.charts.add(ChartType.LINE, 9, 9, 21, 15)
chart = sheet.charts[chartIndex]
# Add series
chart.n_series.add("A2:B4", True)
# Set category data
chart.n_series.category_data = "=Sheet1!$A$2:$A$4"
# Applying a dotted line style on the lines of an NSeries
chart.n_series[0].border.style = LineType.DOT
chart.n_series[0].border.color = Color.red
# Applying a triangular marker style on the data markers of an NSeries
chart.n_series[0].marker.marker_style = ChartMarkerType.TRIANGLE
# Setting the weight of all lines in an NSeries to medium
chart.n_series[0].border.weight = WeightType.MEDIUM_LINE

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`WeightType`](/cells/python-net/ru/aspose.cells.drawing/weighttype)
