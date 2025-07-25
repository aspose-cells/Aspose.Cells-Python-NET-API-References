---
title: ConditionalFormattingIconCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 300
url: /es/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
##  ConditionalFormattingIconCollection clase
Representa una colección de [`ConditionalFormattingIcon`](/cells/python-net/es/aspose.cells/conditionalformattingicon) objetos.



El tipo ConditionalFormattingIconCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, type, index)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.iconsettype-int) | Agrega el objeto [`ConditionalFormattingIcon`](/cells/python-net/es/aspose.cells/conditionalformattingicon).|
| [`add(self, cficon)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.conditionalformattingicon) | Agrega el objeto [`ConditionalFormattingIcon`](/cells/python-net/es/aspose.cells/conditionalformattingicon).|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.conditionalformattingicon) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Get Conditional Formatting
cformattings = sheet.conditional_formattings
# Adds an empty conditional formatting
index = cformattings.add()
# Get newly added Conditional formatting
fcs = cformattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Sets condition
idx = fcs.add_condition(FormatConditionType.ICON_SET)
cond = fcs[idx]
# Sets condition's type
cond.icon_set.type = IconSetType.ARROWS_GRAY3
# Add custom iconset condition.
cfIcon = cond.icon_set.cf_icons[0]
cfIcon.type = IconSetType.ARROWS3
cfIcon.index = 0
cfIcon1 = cond.icon_set.cf_icons[1]
cfIcon1.type = IconSetType.ARROWS_GRAY3
cfIcon1.index = 1
cfIcon2 = cond.icon_set.cf_icons[2]
cfIcon2.type = IconSetType.BOXES5
cfIcon2.index = 2
# Saving the Excel file
workbook.save("output.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`ConditionalFormattingIcon`](/cells/python-net/es/aspose.cells/conditionalformattingicon)
