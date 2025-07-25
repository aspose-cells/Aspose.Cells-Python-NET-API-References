---
title: SparklineGroup clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 290
url: /es/aspose.cells.charts/sparklinegroup/
is_root: false
---
##  SparklineGroup clase
El archivo [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline) está organizado en un grupo de minigráficos. El archivo SparklineGroup contiene un número variable de elementos de minigráficos.
Un grupo de minigráficos especifica el tipo, la configuración de visualización y la configuración del eje para los minigráficos.



El tipo SparklineGroup expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [preset_style](/cells/python-net/es/aspose.cells.charts/sparklinegroup/preset_style) | Obtiene y establece el tipo de estilo preestablecido del grupo de minigráficos.|
| [sparkline_collection](/cells/python-net/es/aspose.cells.charts/sparklinegroup/sparkline_collection) | Obtiene la colección del objeto [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline).|
| [sparklines](/cells/python-net/es/aspose.cells.charts/sparklinegroup/sparklines) | Obtiene la colección del objeto [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline).|
| [type](/cells/python-net/es/aspose.cells.charts/sparklinegroup/type) | Indica el tipo de minigráfico del grupo de minigráficos.|
| [plot_empty_cells_type](/cells/python-net/es/aspose.cells.charts/sparklinegroup/plot_empty_cells_type) | Indica cómo trazar celdas vacías.|
| [display_hidden](/cells/python-net/es/aspose.cells.charts/sparklinegroup/display_hidden) | Indica si se deben mostrar datos en filas y columnas ocultas.|
| [show_high_point](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_high_point) | Indica si se deben resaltar los puntos más altos de los datos en el grupo de minigráficos.|
| [high_point_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/high_point_color) | Obtiene y establece el color de los puntos más altos de datos en el grupo de minigráficos.|
| [show_low_point](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_low_point) | Indica si se deben resaltar los puntos más bajos de los datos en el grupo de minigráficos.|
| [low_point_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/low_point_color) | Obtiene y establece el color de los puntos de datos más bajos en el grupo de minigráficos.|
| [show_negative_points](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_negative_points) |Indica si se deben resaltar los valores negativos en el grupo de minigráficos con un color o marcador diferente.|
| [negative_points_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/negative_points_color) | Obtiene y establece el color de los valores negativos en el grupo de minigráficos.|
| [show_first_point](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_first_point) | Indica si se debe resaltar el primer punto de datos en el grupo de minigráficos.|
| [first_point_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/first_point_color) | Obtiene y establece el color del primer punto de datos en el grupo de minigráficos.|
| [show_last_point](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_last_point) | Indica si se debe resaltar el último punto de datos en el grupo de minigráficos.|
| [last_point_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/last_point_color) | Obtiene y establece el color del último punto de datos en el grupo de minigráficos.|
| [show_markers](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_markers) | Indica si se debe resaltar cada punto en cada minigráfico de línea del grupo de minigráficos.|
| [markers_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/markers_color) | Obtiene y establece el color de los puntos en cada minigráfico de línea del grupo de minigráficos.|
| [series_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/series_color) | Obtiene y establece el color de los minigráficos en el grupo de minigráficos.|
| [plot_right_to_left](/cells/python-net/es/aspose.cells.charts/sparklinegroup/plot_right_to_left) | Indica si los datos de la gráfica son de derecha a izquierda.|
| [line_weight](/cells/python-net/es/aspose.cells.charts/sparklinegroup/line_weight) | Obtiene y establece el grosor de línea en cada minigráfico de línea del grupo de minigráficos, en la unidad de puntos.|
| [horizontal_axis_color](/cells/python-net/es/aspose.cells.charts/sparklinegroup/horizontal_axis_color) |Obtiene y establece el color del eje horizontal en el grupo de minigráficos.|
| [show_horizontal_axis](/cells/python-net/es/aspose.cells.charts/sparklinegroup/show_horizontal_axis) | Indica si se debe mostrar el eje horizontal del minigráfico.<br/> El eje horizontal aparece si el gráfico de líneas tiene datos que cruzan el eje cero.|
| [horizontal_axis_date_range](/cells/python-net/es/aspose.cells.charts/sparklinegroup/horizontal_axis_date_range) | Representa el rango que contiene los valores de fecha para los datos del gráfico de minigráficos.|
| [vertical_axis_max_value_type](/cells/python-net/es/aspose.cells.charts/sparklinegroup/vertical_axis_max_value_type) | Representa el tipo de valor máximo del eje vertical.|
| [vertical_axis_max_value](/cells/python-net/es/aspose.cells.charts/sparklinegroup/vertical_axis_max_value) | Obtiene y establece el valor máximo personalizado para el eje vertical.|
| [vertical_axis_min_value_type](/cells/python-net/es/aspose.cells.charts/sparklinegroup/vertical_axis_min_value_type) | Representa el tipo de valor mínimo del eje vertical.|
| [vertical_axis_min_value](/cells/python-net/es/aspose.cells.charts/sparklinegroup/vertical_axis_min_value) | Obtiene y establece el valor mínimo personalizado para el eje vertical.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`reset_ranges(self, data_range, is_vertical, location_range)`](/cells/python-net/es/aspose.cells.charts/sparklinegroup/reset_ranges/#str-bool-aspose.cells.cellarea) | Restablece el rango de datos y el rango de ubicación del grupo de minigráficos.<br/> Este método borrará los elementos de sparkline originales en el grupo y creará nuevos elementos de sparkline para los nuevos rangos.|



###  Ejemplo

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType
from aspose.pydrawing import Color

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
#  Create CellsColor
clr = book.create_cells_color()
clr.color = Color.orange
group.series_color = clr
#  set the high points are colored green and the low points are colored red
group.show_high_point = True
group.show_low_point = True
group.high_point_color.color = Color.green
group.low_point_color.color = Color.red
#  set line weight
group.line_weight = 1.0
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Ver también
* módulo [`aspose.cells.charts`](..)
* clase [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline)
