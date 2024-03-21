---
title: Series класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 240
url: /ru/aspose.cells.charts/series/
is_root: false
---
##  Series класс
Инкапсулирует объект, представляющий один ряд данных на диаграмме.



Тип Series предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_filtered](/cells/python-net/ru/aspose.cells.charts/series/is_filtered) | Указывает, выбрана ли серия или отфильтрована. Значение True означает, что эта серия отфильтрована и не будет отображаться на диаграмме.|
| [layout_properties](/cells/python-net/ru/aspose.cells.charts/series/layout_properties) | Представляет свойства макета.|
| [points](/cells/python-net/ru/aspose.cells.charts/series/points) | Получает коллекцию точек в серии на диаграмме.|
| [area](/cells/python-net/ru/aspose.cells.charts/series/area) | Представляет фоновую область объекта Series.|
| [border](/cells/python-net/ru/aspose.cells.charts/series/border) | Представляет границу объекта Series.|
| [name](/cells/python-net/ru/aspose.cells.charts/series/name) | Получает или задает имя ряда данных.|
| [display_name](/cells/python-net/ru/aspose.cells.charts/series/display_name) | Получает имя серии, которое отображается на графике диаграммы.|
| [count_of_data_values](/cells/python-net/ru/aspose.cells.charts/series/count_of_data_values) | Получает количество значений данных.|
| [is_vertical_values](/cells/python-net/ru/aspose.cells.charts/series/is_vertical_values) |Указывает, является ли источник данных вертикальным.|
| [values](/cells/python-net/ru/aspose.cells.charts/series/values) | Представляет данные серии диаграмм.|
| [values_format_code](/cells/python-net/ru/aspose.cells.charts/series/values_format_code) | Представляет код формата NumberList Values.|
| [x_values](/cells/python-net/ru/aspose.cells.charts/series/x_values) | Представляет значения x серии диаграммы.|
| [bubble_sizes](/cells/python-net/ru/aspose.cells.charts/series/bubble_sizes) | Получает или задает значения размеров пузырьков серии диаграмм.|
| [trend_lines](/cells/python-net/ru/aspose.cells.charts/series/trend_lines) | Возвращает объект, представляющий коллекцию всех линий тренда для ряда.|
| [smooth](/cells/python-net/ru/aspose.cells.charts/series/smooth) | Представляет сглаживание кривой.<br/>Истинно, если для линейной диаграммы или точечной диаграммы включено сглаживание кривой.<br/> Применяется только к линейным и точечным диаграммам, соединенным линиями.|
| [shadow](/cells/python-net/ru/aspose.cells.charts/series/shadow) | Верно, если в сериале есть тень.|
| [has_3d_effect](/cells/python-net/ru/aspose.cells.charts/series/has_3d_effect) | Правда, если сериал имеет трехмерный вид.<br/> Применяется только к пузырьковым диаграммам.|
| [bar_3d_shape_type](/cells/python-net/ru/aspose.cells.charts/series/bar_3d_shape_type) | Получает или задает тип трехмерной фигуры, используемой с трехмерной гистограммой или гистограммой.|
| [data_labels](/cells/python-net/ru/aspose.cells.charts/series/data_labels) | Представляет объект DataLabels для указанной серии ASeries.|
| [type](/cells/python-net/ru/aspose.cells.charts/series/type) | Получает или задает тип ряда данных.|
| [marker](/cells/python-net/ru/aspose.cells.charts/series/marker) | Получает [`Series.marker`](/cells/python-net/ru/aspose.cells.charts/series#marker).|
| [plot_on_second_axis](/cells/python-net/ru/aspose.cells.charts/series/plot_on_second_axis) | Указывает, отображается ли эта серия на второй оси значений.|
| [x_error_bar](/cells/python-net/ru/aspose.cells.charts/series/x_error_bar) | Представляет полосу ошибок направления X серии.|
| [y_error_bar](/cells/python-net/ru/aspose.cells.charts/series/y_error_bar) |Представляет полосу ошибок направления Y серии.|
| [has_hi_lo_lines](/cells/python-net/ru/aspose.cells.charts/series/has_hi_lo_lines) | Истинно, если на линейном графике есть линии максимума и минимума.<br/> Применяется только к линейным графикам.|
| [hi_lo_lines](/cells/python-net/ru/aspose.cells.charts/series/hi_lo_lines) | Возвращает объект HiLoLines, который представляет линии максимума и минимума серии на линейном графике.<br/> Применяется только к линейным графикам.|
| [has_series_lines](/cells/python-net/ru/aspose.cells.charts/series/has_series_lines) | Истинно, если гистограмма с накоплением или линейчатая диаграмма имеет ряды или<br/> если на круговой диаграмме или линейчатой диаграмме есть соединительные линии между двумя разделами.<br/> Применяется только к гистограммам с накоплением, линейчатым диаграммам, круговым диаграммам или линейчатым диаграммам.|
| [series_lines](/cells/python-net/ru/aspose.cells.charts/series/series_lines) | Возвращает объект SeriesLines, который представляет строки ряда для составной гистограммы или столбчатой диаграммы с накоплением.<br/> Применяется только к столбчатым и столбчатым диаграммам с накоплением.|
| [has_drop_lines](/cells/python-net/ru/aspose.cells.charts/series/has_drop_lines) | Истинно, если на диаграмме есть выпадающие линии.<br/> Применяется только к линейной диаграмме или диаграмме с областями.|
| [drop_lines](/cells/python-net/ru/aspose.cells.charts/series/drop_lines) | Возвращает объект [`Line`](/cells/python-net/ru/aspose.cells.drawing/line), который представляет линии сброса для ряда на линейной диаграмме или диаграмме с областями.<br/> Применяется только к линейной диаграмме или диаграмме с областями.|
| [has_up_down_bars](/cells/python-net/ru/aspose.cells.charts/series/has_up_down_bars) | Истинно, если на линейном графике есть полосы вверх и вниз.<br/> Применяется только к линейным графикам.|
| [up_bars](/cells/python-net/ru/aspose.cells.charts/series/up_bars) | Возвращает объект DropBars, представляющий восходящие бары на линейном графике.<br/> Применяется только к линейным графикам.|
| [down_bars](/cells/python-net/ru/aspose.cells.charts/series/down_bars) | Возвращает объект [`DropBars`](/cells/python-net/ru/aspose.cells.charts/dropbars), представляющий нисходящие бары на линейном графике.<br/> Применяется только к линейным графикам.|
| [is_color_varied](/cells/python-net/ru/aspose.cells.charts/series/is_color_varied) |Указывает, различается ли цвет точек.<br/> Диаграмма должна содержать только одну серию.|
| [gap_width](/cells/python-net/ru/aspose.cells.charts/series/gap_width) | Возвращает или задает расстояние между кластерами полос или столбцов в процентах от ширины полосы или столбца.<br/> Значение этого свойства должно находиться в диапазоне от 0 до 500.|
| [first_slice_angle](/cells/python-net/ru/aspose.cells.charts/series/first_slice_angle) | Получает или задает угол первого фрагмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от вертикали).<br/> Применяется только к круговым, трехмерным круговым и кольцевым диаграммам, от 0 до 360.|
| [overlap](/cells/python-net/ru/aspose.cells.charts/series/overlap) | Определяет расположение столбцов и столбцов.<br/> Может быть значением от – 100 до 100.<br/> Применяется только к двумерным гистограммам и столбчатым диаграммам.|
| [second_plot_size](/cells/python-net/ru/aspose.cells.charts/series/second_plot_size) | Возвращает или задает размер вторичного раздела круговой диаграммы или полосы круговой диаграммы.<br/>в процентах от размера основного пирога.<br/> Может принимать значения от 5 до 200.|
| [split_type](/cells/python-net/ru/aspose.cells.charts/series/split_type) | Возвращает или задает значение, позволяющее определить, какие точки данных находятся во второй круговой диаграмме или столбце диаграммы или столбца диаграммы.<br/> круговая диаграмма.|
| [split_value](/cells/python-net/ru/aspose.cells.charts/series/split_value) | Возвращает или задает значение, которое будет использоваться для определения того, какие точки данных находятся во второй круговой диаграмме или столбце на<br/> круговая диаграмма или круговая диаграмма.|
| [is_auto_split](/cells/python-net/ru/aspose.cells.charts/series/is_auto_split) | Указывает, является ли пороговое значение автоматическим.|
| [bubble_scale](/cells/python-net/ru/aspose.cells.charts/series/bubble_scale) | Получает или задает коэффициент масштабирования для пузырьков в указанной группе диаграмм.<br/> Это может быть целое число от 0 (нуля) до 300.<br/>соответствующий проценту от размера по умолчанию.<br/> Применяется только к пузырьковым диаграммам.|
| [size_represents](/cells/python-net/ru/aspose.cells.charts/series/size_represents) | Получает или задает то, что представляет размер пузырька на пузырьковой диаграмме.|
| [show_negative_bubbles](/cells/python-net/ru/aspose.cells.charts/series/show_negative_bubbles) |Истинно, если для группы диаграмм показаны отрицательные пузырьки. Действительно только для пузырьковых диаграмм.|
| [doughnut_hole_size](/cells/python-net/ru/aspose.cells.charts/series/doughnut_hole_size) | Возвращает или задает размер отверстия в группе кольцевых диаграмм.<br/> Размер отверстия выражается в процентах от размера диаграммы (от 10 до 90 процентов).|
| [explosion](/cells/python-net/ru/aspose.cells.charts/series/explosion) | Расстояние открытого фрагмента круговой диаграммы от центра круговой диаграммы выражается в процентах от диаметра круговой диаграммы.|
| [has_radar_axis_labels](/cells/python-net/ru/aspose.cells.charts/series/has_radar_axis_labels) | Истинно, если на лепестковой диаграмме есть метки осей категорий. Применяется только к радиолокационным картам.|
| [has_leader_lines](/cells/python-net/ru/aspose.cells.charts/series/has_leader_lines) | Верно, если в ряду есть линии-выноски.|
| [leader_lines](/cells/python-net/ru/aspose.cells.charts/series/leader_lines) | Представляет линии выноски на диаграмме. Линии-выноски соединяют метки данных с точками данных.<br/> Этот объект не является коллекцией; нет объекта, который представляет одну линию-выноску.|
| [legend_entry](/cells/python-net/ru/aspose.cells.charts/series/legend_entry) | Получает запись легенды согласно этой серии.|
| [shape_properties](/cells/python-net/ru/aspose.cells.charts/series/shape_properties) | Получает объект [`ShapePropertyCollection`](/cells/python-net/ru/aspose.cells.drawing/shapepropertycollection), содержащий свойства визуальной формы серии.|


###  Методы
| Метод| Описание|
| :- | :- |
| [move](/cells/python-net/ru/aspose.cells.charts/series/move/#int) | Перемещает серию вверх или вниз.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartMarkerType, ChartType, FormattingType
from aspose.pydrawing import Color

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
seriesIndex = chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
series = chart.n_series[seriesIndex]
# Setting the values of the series.
series.values = "=B1:B4"
# Changing the chart type of the series.
series.type = ChartType.LINE
# Setting marker properties.
series.marker.marker_style = ChartMarkerType.CIRCLE
series.marker.foreground_color_set_type = FormattingType.AUTOMATIC
series.marker.foreground_color = Color.black
series.marker.background_color_set_type = FormattingType.AUTOMATIC
# do your business
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`DropBars`](/cells/python-net/ru/aspose.cells.charts/dropbars)
* класс [`Line`](/cells/python-net/ru/aspose.cells.drawing/line)
* класс [`ShapePropertyCollection`](/cells/python-net/ru/aspose.cells.drawing/shapepropertycollection)
