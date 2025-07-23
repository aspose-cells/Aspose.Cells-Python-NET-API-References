---
title: TimelineCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.timelines/timelinecollection/
is_root: false
---
##  TimelineCollection clase
Especifica la colección de todos los objetos de la línea de tiempo en la hoja de cálculo especificada.
Debido a MS Excel, Excel 2003 no admite la línea de tiempo.



El tipo TimelineCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.timelines/timelinecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-str) | Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-int) | Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/get/#str) | Obtiene la línea de tiempo por nombre de la línea de tiempo.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.timelines/timelinecollection/binary_search/#aspose.cells.timelines.timeline) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import CellsFactory, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from datetime import datetime

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
# Create date style
dateStyle = CellsFactory().create_style()
dateStyle.custom = "m/d/yyyy"
cells.get(0, 1).value = "date"
cells.get(1, 1).value = datetime(2021, 2, 5)
cells.get(2, 1).value = datetime(2022, 3, 8)
cells.get(3, 1).value = datetime(2023, 4, 10)
cells.get(4, 1).value = datetime(2024, 5, 16)
# Set date style
cells.get(1, 1).set_style(dateStyle)
cells.get(2, 1).set_style(dateStyle)
cells.get(3, 1).set_style(dateStyle)
cells.get(4, 1).set_style(dateStyle)
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
pivots = sheet.pivot_tables
# Add a PivotTable
pivotIndex = pivots.add("=Sheet1!A1:C5", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "date")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Refresh PivotTable data
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ver también
* módulo [`aspose.cells.timelines`](..)
