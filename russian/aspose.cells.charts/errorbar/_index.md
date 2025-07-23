---
title: ErrorBar класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 160
url: /ru/aspose.cells.charts/errorbar/
is_root: false
---
##  ErrorBar класс
Представляет собой планку погрешностей ряда данных.



**Наследование:** [`ErrorBar`](/cells/python-net/aspose.cells.charts/errorbar) → 
[`Line`](/cells/python-net/ru/aspose.cells.drawing/line)



Тип ErrorBar предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [compound_type](/cells/python-net/ru/aspose.cells.charts/errorbar/compound_type) | Указывает тип составной линии|
| [dash_type](/cells/python-net/ru/aspose.cells.charts/errorbar/dash_type) | Определяет тип пунктирной линии|
| [cap_type](/cells/python-net/ru/aspose.cells.charts/errorbar/cap_type) | Указывает конечные заглавные буквы.|
| [join_type](/cells/python-net/ru/aspose.cells.charts/errorbar/join_type) | Указывает соединительные заглушки.|
| [begin_type](/cells/python-net/ru/aspose.cells.charts/errorbar/begin_type) | Указывает стрелку в начале линии.|
| [end_type](/cells/python-net/ru/aspose.cells.charts/errorbar/end_type) | Задает стрелку в конце линии.|
| [begin_arrow_length](/cells/python-net/ru/aspose.cells.charts/errorbar/begin_arrow_length) | Задает длину стрелки в начале линии.|
| [end_arrow_length](/cells/python-net/ru/aspose.cells.charts/errorbar/end_arrow_length) | Задает длину стрелки на конце линии.|
| [begin_arrow_width](/cells/python-net/ru/aspose.cells.charts/errorbar/begin_arrow_width) | Задает ширину стрелки в начале линии.|
| [end_arrow_width](/cells/python-net/ru/aspose.cells.charts/errorbar/end_arrow_width) | Задает ширину стрелки на конце линии.|
| [theme_color](/cells/python-net/ru/aspose.cells.charts/errorbar/theme_color) | Получает и задает цвет темы.|
| [color](/cells/python-net/ru/aspose.cells.charts/errorbar/color) | Представляет цвет линии.|
| [transparency](/cells/python-net/ru/aspose.cells.charts/errorbar/transparency) | Возвращает или задает степень прозрачности линии как значение от 0,0 (непрозрачная) до 1,0 (прозрачная).|
| [style](/cells/python-net/ru/aspose.cells.charts/errorbar/style) | Представляет стиль линии.|
| [weight](/cells/python-net/ru/aspose.cells.charts/errorbar/weight) | Возвращает или задает [`WeightType`](/cells/python-net/ru/aspose.cells.drawing/weighttype) строки.|
| [weight_pt](/cells/python-net/ru/aspose.cells.charts/errorbar/weight_pt) |Возвращает или задает вес линии в точках.|
| [weight_px](/cells/python-net/ru/aspose.cells.charts/errorbar/weight_px) | Возвращает или задает вес линии в пикселях.|
| [formatting_type](/cells/python-net/ru/aspose.cells.charts/errorbar/formatting_type) | Получает или задает тип формата.|
| [is_automatic_color](/cells/python-net/ru/aspose.cells.charts/errorbar/is_automatic_color) | Указывает, назначается ли цвет линии автоматически.|
| [is_visible](/cells/python-net/ru/aspose.cells.charts/errorbar/is_visible) | Показывает, видна ли линия.|
| [is_auto](/cells/python-net/ru/aspose.cells.charts/errorbar/is_auto) | Указывает, назначается ли этот стиль линии автоматически.|
| [gradient_fill](/cells/python-net/ru/aspose.cells.charts/errorbar/gradient_fill) | Представляет собой градиентную заливку.|
| [type](/cells/python-net/ru/aspose.cells.charts/errorbar/type) | Представляет тип величины планки погрешностей.|
| [display_type](/cells/python-net/ru/aspose.cells.charts/errorbar/display_type) | Представляет собой тип отображения панели погрешностей.|
| [amount](/cells/python-net/ru/aspose.cells.charts/errorbar/amount) | Представляет собой величину планки погрешности.|
| [show_marker_t_top](/cells/python-net/ru/aspose.cells.charts/errorbar/show_marker_t_top) | Указывает, форматируются ли полосы погрешностей с Т-образным верхом.|
| [plus_value](/cells/python-net/ru/aspose.cells.charts/errorbar/plus_value) | Представляет положительную величину ошибки, если тип планки погрешностей — Пользовательский.|
| [minus_value](/cells/python-net/ru/aspose.cells.charts/errorbar/minus_value) | Представляет собой отрицательную величину ошибки, если тип планки погрешностей — Пользовательский.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, ErrorBarDisplayType, ErrorBarType

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("a1").put_value(2)
cells.get("a2").put_value(5)
cells.get("a3").put_value(3)
cells.get("a4").put_value(6)
cells.get("b1").put_value(4)
cells.get("b2").put_value(3)
cells.get("b3").put_value(6)
cells.get("b4").put_value(7)
cells.get("C1").put_value("Q1")
cells.get("C2").put_value("Q2")
cells.get("C3").put_value("Y1")
cells.get("C4").put_value("Y2")
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 11, 0, 27, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:B4", True)
chart.n_series.category_data = "C1:C4"
for i in range(len(chart.n_series)):
    aseries = chart.n_series[i]
    aseries.y_error_bar.display_type = ErrorBarDisplayType.MINUS
    aseries.y_error_bar.type = ErrorBarType.FIXED_VALUE
    aseries.y_error_bar.amount = 5.0

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`ErrorBar`](/cells/python-net/ru/aspose.cells.charts/errorbar)
* класс [`Line`](/cells/python-net/ru/aspose.cells.drawing/line)
* класс [`WeightType`](/cells/python-net/ru/aspose.cells.drawing/weighttype)
