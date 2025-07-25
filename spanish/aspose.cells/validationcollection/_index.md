---
title: ValidationCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1530
url: /es/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection clase
Representa la recopilación de validación de datos.



El tipo ValidationCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/validationcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self)`](/cells/python-net/es/aspose.cells/validationcollection/add/#) | Agrega una validación de datos a la colección.|
| [`add(self, ca)`](/cells/python-net/es/aspose.cells/validationcollection/add/#aspose.cells.cellarea) | Agrega una validación de datos a la colección.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/validationcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/es/aspose.cells/validationcollection/remove_a_cell/#int-int) | Elimina toda la configuración de validación en la celda.|
| [`remove_area(self, ca)`](/cells/python-net/es/aspose.cells/validationcollection/remove_area/#aspose.cells.cellarea) | Elimina todas las configuraciones de validación en el rango.|
| [`get_validation_in_cell(self, row, column)`](/cells/python-net/es/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Obtiene la validación aplicada a la celda dada.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/validationcollection/binary_search/#aspose.cells.validation) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  Ver también
* módulo [`aspose.cells`](..)
