---
title: ErrorBar класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 160
url: /ru/aspose.cells.charts/errorbar/
is_root: false
---
##  ErrorBar класс
Представляет панель ошибок ряда данных.



**Наследование:** [`ErrorBar`](/cells/python-net/aspose.cells.charts/errorbar) → 
[`Line`](/cells/python-net/ru/aspose.cells.drawing/line)



Тип ErrorBar предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [compound_type](/cells/python-net/ru/aspose.cells.charts/errorbar/compound_type) | Указывает тип составной линии|
| [dash_type](/cells/python-net/ru/aspose.cells.charts/errorbar/dash_type) | Указывает тип пунктирной линии|
| [cap_type](/cells/python-net/ru/aspose.cells.charts/errorbar/cap_type) |Указывает конечные прописные буквы.|
| [join_type](/cells/python-net/ru/aspose.cells.charts/errorbar/join_type) | Указывает соединительные заглушки.|
| [begin_type](/cells/python-net/ru/aspose.cells.charts/errorbar/begin_type) | Указывает стрелку в начале строки.|
| [end_type](/cells/python-net/ru/aspose.cells.charts/errorbar/end_type) | Указывает стрелку в конце строки.|
| [begin_arrow_length](/cells/python-net/ru/aspose.cells.charts/errorbar/begin_arrow_length) | Указывает длину стрелки в начале строки.|
| [end_arrow_length](/cells/python-net/ru/aspose.cells.charts/errorbar/end_arrow_length) | Указывает длину стрелки в конце строки.|
| [begin_arrow_width](/cells/python-net/ru/aspose.cells.charts/errorbar/begin_arrow_width) | Определяет ширину стрелки в начале строки.|
| [end_arrow_width](/cells/python-net/ru/aspose.cells.charts/errorbar/end_arrow_width) | Определяет ширину стрелки в конце строки.|
| [theme_color](/cells/python-net/ru/aspose.cells.charts/errorbar/theme_color) | Получает и устанавливает цвет темы.|
| [color](/cells/python-net/ru/aspose.cells.charts/errorbar/color) | Представляет цвет линии.|
| [transparency](/cells/python-net/ru/aspose.cells.charts/errorbar/transparency) | Возвращает или задает степень прозрачности линии в диапазоне от 0,0 (непрозрачная) до 1,0 (прозрачная).|
| [style](/cells/python-net/ru/aspose.cells.charts/errorbar/style) | Представляет стиль линии.|
| [weight](/cells/python-net/ru/aspose.cells.charts/errorbar/weight) | Получает или задает [`WeightType`](/cells/python-net/ru/aspose.cells.drawing/weighttype) строки.|
| [weight_pt](/cells/python-net/ru/aspose.cells.charts/errorbar/weight_pt) | Получает или задает вес линии в точках.|
| [weight_px](/cells/python-net/ru/aspose.cells.charts/errorbar/weight_px) | Получает или задает вес линии в пикселях.|
| [formatting_type](/cells/python-net/ru/aspose.cells.charts/errorbar/formatting_type) | Получает или задает тип формата.|
| [is_automatic_color](/cells/python-net/ru/aspose.cells.charts/errorbar/is_automatic_color) | Указывает, назначается ли цвет линии автоматически.|
| [is_visible](/cells/python-net/ru/aspose.cells.charts/errorbar/is_visible) | Указывает, видна ли линия.|
| [is_auto](/cells/python-net/ru/aspose.cells.charts/errorbar/is_auto) |Указывает, назначается ли этот стиль линии автоматически.|
| [gradient_fill](/cells/python-net/ru/aspose.cells.charts/errorbar/gradient_fill) | Представляет градиентную заливку.|
| [type](/cells/python-net/ru/aspose.cells.charts/errorbar/type) | Представляет тип суммы панели ошибок.|
| [display_type](/cells/python-net/ru/aspose.cells.charts/errorbar/display_type) | Представляет тип отображения панели ошибок.|
| [amount](/cells/python-net/ru/aspose.cells.charts/errorbar/amount) | Представляет количество ошибок.<br/> Сумма должна быть больше или равна нулю.|
| [show_marker_t_top](/cells/python-net/ru/aspose.cells.charts/errorbar/show_marker_t_top) | Указывает, имеют ли полосы ошибок форматирования Т-образную форму.|
| [plus_value](/cells/python-net/ru/aspose.cells.charts/errorbar/plus_value) | Представляет положительную сумму ошибки, если тип панели ошибок — Пользовательский.|
| [minus_value](/cells/python-net/ru/aspose.cells.charts/errorbar/minus_value) | Представляет отрицательную сумму ошибки, если тип панели ошибок — Пользовательский.|



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
