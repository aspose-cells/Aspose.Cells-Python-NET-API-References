---
title: SparklineGroupCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 300
url: /es/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection clase
Encapsula una colección de [`SparklineGroup`](/cells/python-net/es/aspose.cells.charts/sparklinegroup) objetos.



El tipo SparklineGroupCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, type)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | Agrega un [`SparklineGroup`](/cells/python-net/es/aspose.cells.charts/sparklinegroup) con un [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline) a la colección.|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | Agrega un [`SparklineGroup`](/cells/python-net/es/aspose.cells.charts/sparklinegroup) con [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline) a la colección.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | Borra las líneas brillantes que se encuentran dentro de un área de celdas.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | Borra los grupos de minigráficos que se superponen a un área de celdas.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

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
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Ver también
* módulo [`aspose.cells.charts`](..)
* clase [`Sparkline`](/cells/python-net/es/aspose.cells.charts/sparkline)
* clase [`SparklineGroup`](/cells/python-net/es/aspose.cells.charts/sparklinegroup)
