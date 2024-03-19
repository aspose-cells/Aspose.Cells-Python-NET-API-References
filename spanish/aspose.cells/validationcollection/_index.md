---
title: ValidationCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1620
url: /es/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection clase
Representa la recopilación de validación de datos.



El tipo ValidationCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/validationcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells/validationcollection/add/#) | Agrega una validación de datos a la colección.|
| [add](/cells/python-net/es/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Agrega una validación de datos a la colección.|
| [copy_to](/cells/python-net/es/aspose.cells/validationcollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [remove_a_cell](/cells/python-net/es/aspose.cells/validationcollection/remove_a_cell/#int-int) | Elimina todas las configuraciones de validación en la celda.|
| [remove_area](/cells/python-net/es/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Elimina todas las configuraciones de validación en el rango.|
| [get_validation_in_cell](/cells/python-net/es/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Obtiene la validación aplicada a la celda determinada.|
| [binary_search](/cells/python-net/es/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



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
