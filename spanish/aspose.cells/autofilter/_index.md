---
title: AutoFilter clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter clase
Representa el filtrado automático para la hoja de trabajo especificada.



El tipo AutoFilter expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [sorter](/cells/python-net/es/aspose.cells/autofilter/sorter) | Obtiene el clasificador de datos.|
| [range](/cells/python-net/es/aspose.cells/autofilter/range) | Representa el rango al que se aplica el filtro automático especificado.|
| [show_filter_button](/cells/python-net/es/aspose.cells/autofilter/show_filter_button) | Indica si el botón Autofiltro para esta columna está visible.|
| [filter_columns](/cells/python-net/es/aspose.cells/autofilter/filter_columns) | Obtiene la colección de las columnas de filtro.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/es/aspose.cells/autofilter/get_cell_area/#) | Obtiene el [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) donde se aplica este filtro automático.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/es/aspose.cells/autofilter/get_cell_area/#bool) | Obtiene el [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) donde se aplica el filtro automático especificado.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/es/aspose.cells/autofilter/remove_filter/#int-str) | Elimina un filtro para una columna de filtro.|
| [`remove_filter(self, field_index)`](/cells/python-net/es/aspose.cells/autofilter/remove_filter/#int) | Retire el filtro específico.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/es/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Filtra una lista con un criterio personalizado.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/es/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Filtra una lista con criterios personalizados.|
| [`refresh(self)`](/cells/python-net/es/aspose.cells/autofilter/refresh/#) | Actualice los filtros automáticos para ocultar o mostrar las filas.|
| [`refresh(self, hide_rows)`](/cells/python-net/es/aspose.cells/autofilter/refresh/#bool) | Obtiene los índices de todas las filas ocultas.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/es/aspose.cells/autofilter/set_range/#int-int-int) | Establece el rango al que se aplica el filtro automático especificado.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/es/aspose.cells/autofilter/add_filter/#int-str) | Agrega un filtro para una columna de filtro.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/es/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Agrega un filtro de fecha.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/es/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Elimina un filtro de fecha.|
| [`filter(self, field_index, criteria)`](/cells/python-net/es/aspose.cells/autofilter/filter/#int-str) | Filtra una lista con criterios específicos.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/es/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Filtrar los 10 elementos principales de la lista|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/es/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Añade un filtro dinámico.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/es/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Agrega un filtro de color de fuente.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/es/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Agrega un filtro de color de relleno.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/es/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Agrega un filtro de iconos.|
| [`match_blanks(self, field_index)`](/cells/python-net/es/aspose.cells/autofilter/match_blanks/#int) | Coincidir con todas las celdas en blanco de la lista.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/es/aspose.cells/autofilter/match_non_blanks/#int) | Coincidir con todas las celdas que no estén en blanco en la lista.|
| [`show_all(self)`](/cells/python-net/es/aspose.cells/autofilter/show_all/#) | Mostrar todas las filas.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`CellArea`](/cells/python-net/es/aspose.cells/cellarea)
