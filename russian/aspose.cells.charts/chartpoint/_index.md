---
title: ChartPoint класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells.charts/chartpoint/
is_root: false
---
##  ChartPoint класс
Представляет отдельную точку в серии на диаграмме.



Тип ChartPoint предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [explosion](/cells/python-net/ru/aspose.cells.charts/chartpoint/explosion) |Расстояние от центра круговой диаграммы до открытого сектора круговой диаграммы выражается в процентах от диаметра круга.|
| [shadow](/cells/python-net/ru/aspose.cells.charts/chartpoint/shadow) | Истина, если у точки карты есть тень.|
| [border](/cells/python-net/ru/aspose.cells.charts/chartpoint/border) | Получает [`Line`](/cells/python-net/ru/aspose.cells.drawing/line).|
| [area](/cells/python-net/ru/aspose.cells.charts/chartpoint/area) | Получает [`ChartPoint.area`](/cells/python-net/ru/aspose.cells.charts/chartpoint#area).|
| [marker](/cells/python-net/ru/aspose.cells.charts/chartpoint/marker) | Получает [`ChartPoint.marker`](/cells/python-net/ru/aspose.cells.charts/chartpoint#marker).|
| [data_labels](/cells/python-net/ru/aspose.cells.charts/chartpoint/data_labels) | Возвращает объект [`ChartPoint.data_labels`](/cells/python-net/ru/aspose.cells.charts/chartpoint#data_labels), представляющий метку данных, связанную с этой точкой диаграммы.|
| [y_value](/cells/python-net/ru/aspose.cells.charts/chartpoint/y_value) | Возвращает или задает значение Y точки диаграммы.|
| [y_value_type](/cells/python-net/ru/aspose.cells.charts/chartpoint/y_value_type) | Возвращает тип значения Y точки диаграммы.|
| [x_value](/cells/python-net/ru/aspose.cells.charts/chartpoint/x_value) | Возвращает или задает значение X точки диаграммы.|
| [x_value_type](/cells/python-net/ru/aspose.cells.charts/chartpoint/x_value_type) | Получает тип значения X точки диаграммы.|
| [shape_properties](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_properties) | Получает объект [`ShapePropertyCollection`](/cells/python-net/ru/aspose.cells.drawing/shapepropertycollection), содержащий визуальные свойства формы ChartPoint.|
| [is_in_secondary_plot](/cells/python-net/ru/aspose.cells.charts/chartpoint/is_in_secondary_plot) | Возвращает или задает значение, указывающее, находятся ли эти точки данных во второй круговой или столбчатой диаграмме.<br/> на круговой диаграмме или столбчатой круговой диаграмме|
| [shape_x](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_x) | Получает координату x верхнего левого угла в единицах 1/4000 ширины диаграммы после вызова метода Chart.Calculate().|
| [shape_y](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_y) | Получает координату y верхнего левого угла в единицах 1/4000 высоты диаграммы после вызова метода Chart.Calculate().|
| [shape_width](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_width) |Получает ширину в единицах 1/4000 ширины диаграммы после вызова метода Chart.Calculate().|
| [shape_height](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_height) | Получает высоту в единицах 1/4000 высоты диаграммы после вызова метода Chart.Calculate().|
| [shape_x_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_x_px) | Получает координату x верхнего левого угла в пикселях после вызова метода Chart.Calculate().|
| [shape_y_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_y_px) | Получает координату y верхнего левого угла в пикселях после вызова метода Chart.Calculate().|
| [shape_width_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_width_px) | Получает ширину в пикселях после вызова метода Chart.Calculate().|
| [shape_height_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/shape_height_px) | Получает высоту в пикселях после вызова метода Chart.Calculate().|
| [border_width_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/border_width_px) | Получает ширину границы в пикселях после вызова метода Chart.Calculate().|
| [radius_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/radius_px) | Получает радиус пузыря, пирога или пончика в пикселях после вызова метода Chart.Calculate().|
| [doughnut_inner_radius](/cells/python-net/ru/aspose.cells.charts/chartpoint/doughnut_inner_radius) | Возвращает внутренний радиус сегмента пончика в пикселях после вызова метода Chart.Calculate().<br/> Применимо к кольцевой диаграмме.|
| [inner_radius_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/inner_radius_px) | Возвращает внутренний радиус сегмента пончика в пикселях после вызова метода Chart.Calculate().<br/> Применимо к кольцевой диаграмме.|
| [start_angle](/cells/python-net/ru/aspose.cells.charts/chartpoint/start_angle) |Возвращает начальный угол для сектора круга, измеряемый в градусах по часовой стрелке от оси x после вызова метода Chart.Calculate().<br/> Применимо к круговой диаграмме.|
| [end_angle](/cells/python-net/ru/aspose.cells.charts/chartpoint/end_angle) | Возвращает конечный угол для сектора круга, измеряемый в градусах по часовой стрелке от оси x после вызова метода Chart.Calculate().<br/> Применимо к круговой диаграмме.|
| [arc_start_point_x_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/arc_start_point_x_px) | Получает координату x начальной точки для сектора круга после вызова метода Chart.Calculate().<br/> Применимо к круговым и кольцевым диаграммам.|
| [arc_start_point_y_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/arc_start_point_y_px) | Получает координату Y начальной точки для сектора круга после вызова метода Chart.Calculate().<br/> Применимо к круговым и кольцевым диаграммам.|
| [arc_end_point_x_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/arc_end_point_x_px) | Получает координату x конечной точки сектора круга после вызова метода Chart.Calculate().<br/> Применимо к круговым и кольцевым диаграммам.|
| [arc_end_point_y_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/arc_end_point_y_px) | Получает координату Y конечной точки сектора круга после вызова метода Chart.Calculate().<br/> Применимо к круговым и кольцевым диаграммам.|
| [inner_arc_start_point_x_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/inner_arc_start_point_x_px) | Получает координату x начальной точки для сектора круга после вызова метода Chart.Calculate().<br/> Применимо к кольцевой диаграмме.|
| [inner_arc_start_point_y_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/inner_arc_start_point_y_px) | Получает координату Y начальной точки для сектора круга после вызова метода Chart.Calculate().<br/> Применимо к кольцевой диаграмме.|
| [inner_arc_end_point_x_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/inner_arc_end_point_x_px) | Получает координату x конечной точки сектора круга после вызова метода Chart.Calculate().<br/> Применимо к кольцевой диаграмме.|
| [inner_arc_end_point_y_px](/cells/python-net/ru/aspose.cells.charts/chartpoint/inner_arc_end_point_y_px) | Получает координату Y конечной точки сектора круга после вызова метода Chart.Calculate().<br/> Применимо к кольцевой диаграмме.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_top_point_count(self)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_top_point_count/#) | Получает количество верхних точек после вызова метода Chart.Calculate().|
| [`get_top_point_x_px(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_top_point_x_px/#int) | Получает x-координату верхней точки фигуры после вызова метода Chart.Calculate().<br/>Применяет 3D-диаграммы: Column3D, Bar3D, Cone, Cylinder, Pyramid и Area3D|
| [`get_top_point_y_px(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_top_point_y_px/#int) | Получает y-координату верхней точки фигуры после вызова метода Chart.Calculate().<br/>Применяет 3D-диаграммы: Column3D, Bar3D, Cone, Cylinder, Pyramid и Area3D|
| [`get_bottom_point_count(self)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_bottom_point_count/#) | Получает количество нижних точек после вызова метода Chart.Calculate().|
| [`get_bottom_point_x_px(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_bottom_point_x_px/#int) | Получает x-координату нижней точки фигуры после вызова метода Chart.Calculate().<br/> Применяет 3D-диаграммы: Column3D, Bar3D, Cone, Cylinder, Pyramid|
| [`get_bottom_point_y_px(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_bottom_point_y_px/#int) | Получает y-координату нижней точки фигуры после вызова метода Chart.Calculate().<br/> Применяет 3D-диаграммы: Column3D, Bar3D, Cone, Cylinder, Pyramid|
| [`get_on_category_axis_point_count(self)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_on_category_axis_point_count/#) | Получает количество точек на оси категорий после вызова метода Chart.Calculate(). Применимо только к диаграммам с областями.|
| [`get_on_category_axis_point_x_px(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_on_category_axis_point_x_px/#int) | Получает x-координату точки на оси категорий после вызова метода Chart.Calculate(). Применимо только к площадным диаграммам.|
| [`get_on_category_axis_point_y_px(self, index)`](/cells/python-net/ru/aspose.cells.charts/chartpoint/get_on_category_axis_point_y_px/#int) | Получает координату Y точки на оси категорий после вызова метода Chart.Calculate(). Применимо только к диаграммам с областями.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
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
chartIndex = worksheet.charts.add(ChartType.PIE_EXPLODED, 5, 0, 25, 10)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
# Show Data Labels
chart.n_series[0].data_labels.show_value = True
for i in range(chart.n_series[0].points.count):
    # Get Data Point
    point = chart.n_series[0].points[i]
    # Set Pir Explosion
    point.explosion = 15
    # Set Border Color
    point.border.color = Color.red
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`Line`](/cells/python-net/ru/aspose.cells.drawing/line)
* класс [`ShapePropertyCollection`](/cells/python-net/ru/aspose.cells.drawing/shapepropertycollection)
