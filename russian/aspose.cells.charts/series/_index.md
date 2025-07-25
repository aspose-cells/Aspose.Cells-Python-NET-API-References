---
title: Series класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 240
url: /ru/aspose.cells.charts/series/
is_root: false
---
##  Series класс
Инкапсулирует объект, представляющий отдельную серию данных в диаграмме.



Тип Series предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_filtered](/cells/python-net/ru/aspose.cells.charts/series/is_filtered) | Указывает, выбрана или отфильтрована серия. True означает, что эта серия отфильтрована и не будет отображаться на диаграмме.|
| [layout_properties](/cells/python-net/ru/aspose.cells.charts/series/layout_properties) | Представляет свойства макета.|
| [points](/cells/python-net/ru/aspose.cells.charts/series/points) | Получает набор точек в виде серии на диаграмме.|
| [area](/cells/python-net/ru/aspose.cells.charts/series/area) | Представляет фоновую область объекта Series.|
| [border](/cells/python-net/ru/aspose.cells.charts/series/border) | Представляет границу объекта Series.|
| [name](/cells/python-net/ru/aspose.cells.charts/series/name) | Возвращает или задает имя ряда данных.|
| [display_name](/cells/python-net/ru/aspose.cells.charts/series/display_name) | Получает название серии, отображаемое на графике диаграммы.|
| [count_of_data_values](/cells/python-net/ru/aspose.cells.charts/series/count_of_data_values) | Получает количество значений данных.|
| [is_vertical_values](/cells/python-net/ru/aspose.cells.charts/series/is_vertical_values) | Указывает, является ли источник данных вертикальным.|
| [values](/cells/python-net/ru/aspose.cells.charts/series/values) | Представляет значения Y этой серии диаграмм.|
| [values_format_code](/cells/python-net/ru/aspose.cells.charts/series/values_format_code) | Представляет код формата NumberList значений.|
| [x_values_format_code](/cells/python-net/ru/aspose.cells.charts/series/x_values_format_code) | Представляет код формата списка чисел X Values.|
| [x_values](/cells/python-net/ru/aspose.cells.charts/series/x_values) |Представляет значения x ряда диаграммы.|
| [bubble_sizes](/cells/python-net/ru/aspose.cells.charts/series/bubble_sizes) | Возвращает или задает значения размеров пузырьков в серии диаграммы.|
| [trend_lines](/cells/python-net/ru/aspose.cells.charts/series/trend_lines) | Возвращает все линии тренда этой серии.|
| [smooth](/cells/python-net/ru/aspose.cells.charts/series/smooth) | Представляет собой сглаживание кривой.<br/>True, если сглаживание кривых включено для линейной диаграммы или диаграммы рассеяния.<br/> Применимо только к линейным и точечным диаграммам, соединенным линиями.|
| [shadow](/cells/python-net/ru/aspose.cells.charts/series/shadow) | Истина, если у серии есть тень.|
| [has_3d_effect](/cells/python-net/ru/aspose.cells.charts/series/has_3d_effect) | Верно, если серия имеет трехмерный вид.<br/> Применимо только к пузырьковым диаграммам.|
| [bar_3d_shape_type](/cells/python-net/ru/aspose.cells.charts/series/bar_3d_shape_type) | Возвращает или задает тип трехмерной фигуры, используемой с трехмерной линейчатой или столбчатой диаграммой.|
| [data_labels](/cells/python-net/ru/aspose.cells.charts/series/data_labels) | Представляет объект DataLabels для указанной ASeries.|
| [type](/cells/python-net/ru/aspose.cells.charts/series/type) | Получает или задает тип ряда данных.|
| [marker](/cells/python-net/ru/aspose.cells.charts/series/marker) | Получает [`Series.marker`](/cells/python-net/ru/aspose.cells.charts/series#marker).|
| [plot_on_second_axis](/cells/python-net/ru/aspose.cells.charts/series/plot_on_second_axis) | Указывает, отображен ли этот ряд на второй оси значений.|
| [x_error_bar](/cells/python-net/ru/aspose.cells.charts/series/x_error_bar) | Представляет собой планку погрешности направления X для данной серии.|
| [y_error_bar](/cells/python-net/ru/aspose.cells.charts/series/y_error_bar) | Представляет собой планку погрешности направления Y для данной серии.|
| [has_hi_lo_lines](/cells/python-net/ru/aspose.cells.charts/series/has_hi_lo_lines) | Истина, если на линейном графике имеются линии максимума и минимума.<br/> Применимо только к линейным диаграммам.|
| [hi_lo_lines](/cells/python-net/ru/aspose.cells.charts/series/hi_lo_lines) | Возвращает объект HiLoLines, представляющий линии максимума и минимума для ряда на линейном графике.<br/> Применимо только к линейным диаграммам.|
| [has_series_lines](/cells/python-net/ru/aspose.cells.charts/series/has_series_lines) |Истина, если столбчатая диаграмма с накоплением или линейчатая диаграмма имеет линии ряда или<br/> если круговая диаграмма или линейчатая круговая диаграмма имеют соединительные линии между двумя секциями.<br/> Применимо только к столбчатым диаграммам с накоплением, линейчатым диаграммам, круговым диаграммам или линейчатым круговым диаграммам.|
| [series_lines](/cells/python-net/ru/aspose.cells.charts/series/series_lines) | Возвращает объект SeriesLines, представляющий линии ряда для столбчатой диаграммы с накоплением или столбчатой диаграммы с накоплением.<br/> Применимо только к столбчатым и линейчатым диаграммам с накоплением.|
| [has_drop_lines](/cells/python-net/ru/aspose.cells.charts/series/has_drop_lines) | Истина, если на диаграмме есть линии сброса.<br/> Применимо только к линейным диаграммам или диаграммам с областями.|
| [drop_lines](/cells/python-net/ru/aspose.cells.charts/series/drop_lines) | Возвращает объект [`Line`](/cells/python-net/ru/aspose.cells.drawing/line), представляющий линии отсчета для ряда на линейной диаграмме или диаграмме с областями.<br/> Применимо только к линейным диаграммам или диаграммам с областями.|
| [has_up_down_bars](/cells/python-net/ru/aspose.cells.charts/series/has_up_down_bars) | True, если линейный график имеет восходящие и нисходящие полосы.<br/> Применимо только к линейным диаграммам.|
| [up_bars](/cells/python-net/ru/aspose.cells.charts/series/up_bars) | Возвращает объект DropBars, представляющий восходящие столбцы на линейной диаграмме.<br/> Применимо только к линейным диаграммам.|
| [down_bars](/cells/python-net/ru/aspose.cells.charts/series/down_bars) | Возвращает объект [`DropBars`](/cells/python-net/ru/aspose.cells.charts/dropbars), представляющий нисходящие полосы на линейном графике.<br/> Применимо только к линейным диаграммам.|
| [is_color_varied](/cells/python-net/ru/aspose.cells.charts/series/is_color_varied) | Показывает, является ли цвет точек разным.<br/> Диаграмма должна содержать только одну серию.|
| [gap_width](/cells/python-net/ru/aspose.cells.charts/series/gap_width) | Возвращает или задает расстояние между кластерами полос или столбцов в процентах от ширины полосы или столбца.<br/> Значение этого свойства должно быть от 0 до 500.|
| [first_slice_angle](/cells/python-net/ru/aspose.cells.charts/series/first_slice_angle) | Возвращает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вертикали).<br/> Применимо только к круговым, трехмерным круговым и кольцевым диаграммам, от 0 до 360.|
| [overlap](/cells/python-net/ru/aspose.cells.charts/series/overlap) | Определяет, как располагаются полосы и столбцы.<br/>Может иметь значение от –100 до 100.<br/> Применимо только к двумерным столбчатым и двумерным линейчатым диаграммам.|
| [second_plot_size](/cells/python-net/ru/aspose.cells.charts/series/second_plot_size) |Возвращает или задает размер вторичной части круговой диаграммы или столбчатой круговой диаграммы.<br/>в процентах от размера основного пирога.<br/> Может иметь значение от 5 до 200.|
| [split_type](/cells/python-net/ru/aspose.cells.charts/series/split_type) | Возвращает или задает значение, которое позволяет определить, какие точки данных находятся на второй круговой диаграмме или столбчатой диаграмме круговой диаграммы или столбчатой диаграммы.<br/> круговая диаграмма.|
| [split_value](/cells/python-net/ru/aspose.cells.charts/series/split_value) | Возвращает или задает значение, которое будет использоваться для определения того, какие точки данных находятся во второй круговой или столбчатой диаграмме.<br/> круговая диаграмма или столбчатая круговая диаграмма.|
| [is_auto_split](/cells/python-net/ru/aspose.cells.charts/series/is_auto_split) | Указывает, является ли пороговое значение автоматическим.|
| [bubble_scale](/cells/python-net/ru/aspose.cells.charts/series/bubble_scale) | Возвращает или задает коэффициент масштабирования для пузырьков в указанной группе диаграммы.<br/> Это может быть целое число от 0 (нуля) до 300,<br/>соответствующий проценту от размера по умолчанию.<br/> Применимо только к пузырьковым диаграммам.|
| [size_represents](/cells/python-net/ru/aspose.cells.charts/series/size_represents) | Возвращает или задает размер пузырька на пузырьковой диаграмме.|
| [show_negative_bubbles](/cells/python-net/ru/aspose.cells.charts/series/show_negative_bubbles) | True, если для группы диаграмм отображаются отрицательные пузырьки. Действительно только для пузырьковых диаграмм.|
| [doughnut_hole_size](/cells/python-net/ru/aspose.cells.charts/series/doughnut_hole_size) | Возвращает или задает размер отверстия в группе кольцевых диаграмм.<br/> Размер отверстия выражается в процентах от размера диаграммы и составляет от 10 до 90 процентов.|
| [explosion](/cells/python-net/ru/aspose.cells.charts/series/explosion) |Расстояние от центра круговой диаграммы до открытого сектора круговой диаграммы выражается в процентах от диаметра круга.|
| [has_radar_axis_labels](/cells/python-net/ru/aspose.cells.charts/series/has_radar_axis_labels) | Истина, если на радиальной диаграмме есть метки осей категорий. Применимо только к радиальным диаграммам.|
| [has_leader_lines](/cells/python-net/ru/aspose.cells.charts/series/has_leader_lines) |Истина, если в серии имеются направляющие линии.|
| [leader_lines](/cells/python-net/ru/aspose.cells.charts/series/leader_lines) | Представляет собой линии-указатели на диаграмме. Линии-указатели соединяют метки данных с точками данных.<br/> Этот объект не является коллекцией; не существует объекта, представляющего отдельную линию-выноску.|
| [legend_entry](/cells/python-net/ru/aspose.cells.charts/series/legend_entry) | Получает запись легенды согласно этой серии.|
| [shape_properties](/cells/python-net/ru/aspose.cells.charts/series/shape_properties) | Получает объект [`ShapePropertyCollection`](/cells/python-net/ru/aspose.cells.drawing/shapepropertycollection), содержащий визуальные свойства формы серии.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`move(self, count)`](/cells/python-net/ru/aspose.cells.charts/series/move/#int) | Перемещает серию вверх или вниз.|



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
