---
title: PivotTableCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 250
url: /es/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection clase
Representa la colección de todos los objetos de tabla dinámica en la hoja de cálculo especificada.



El tipo PivotTableCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | Agrega una nueva tabla dinámica.|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | Agrega una nueva tabla dinámica.|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | Agrega una nueva tabla dinámica.|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | Agrega una nueva tabla dinámica.|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) | Agrega una nueva tabla dinámica.|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) | Agrega una nueva tabla dinámica.|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) | Agrega una nueva tabla dinámica basada en otra tabla dinámica.|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Agrega una nueva tabla dinámica basada en otra tabla dinámica.|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) | Agrega un nuevo objeto de tabla dinámica a la colección con múltiples rangos de consolidación como fuente de datos.|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) | Agrega un nuevo objeto de tabla dinámica a la colección con múltiples rangos de consolidación como fuente de datos.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/get/#str) | Obtiene el informe de tabla dinámica por nombre de tabla dinámica.|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) | Elimina la tabla dinámica especificada y elimina los datos de la tabla dinámica|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) | Elimina la tabla dinámica especificada|
| [`remove_by_index(self, index)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) | Elimina la tabla dinámica en el índice especificado y elimina los datos de la tabla dinámica|
| [`remove_at(self, index, keep_data)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | Elimina la tabla dinámica en el índice especificado|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ver también
* módulo [`aspose.cells.pivot`](..)
