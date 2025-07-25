---
title: SlicerCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells.slicers/slicercollection/
is_root: false
---
##  SlicerCollection clase
Especifica la colección de todos los objetos Slicer en la hoja de cálculo especificada.



El tipo SlicerCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.slicers/slicercollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-str) | Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-int) | Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos|
| [`add(self, table, index, dest_cell_name)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-int-str) | Agregar un nuevo Slicer usando ListObjet como fuente de datos|
| [`add(self, table, list_column, dest_cell_name)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-str) | Agregar un nuevo Slicer usando ListObjet como fuente de datos|
| [`add(self, table, list_column, row, column)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-int-int) | Agregar un nuevo Slicer usando ListObjet como fuente de datos|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/get/#str) | Obtiene la segmentación por nombre de segmentación.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.slicers/slicercollection/binary_search/#aspose.cells.slicers.slicer) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

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
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
tableIndex = sheet.list_objects.add("A1", "C9", True)
table = sheet.list_objects[tableIndex]
# do your business
book.save("out.xlsx")

```

###  Ver también
* módulo [`aspose.cells.slicers`](..)
