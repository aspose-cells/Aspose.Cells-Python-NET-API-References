---
title: ConditionalFormattingCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 310
url: /es/aspose.cells/conditionalformattingcollection/
is_root: false
---
##  ConditionalFormattingCollection clase
Encapsula una colección de [`FormatCondition`](/cells/python-net/es/aspose.cells/formatcondition) objetos.



El tipo ConditionalFormattingCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/conditionalformattingcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [copy_to](/cells/python-net/es/aspose.cells/conditionalformattingcollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells/conditionalformattingcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells/conditionalformattingcollection/index_of/#aspose.cells.FormatConditionCollection-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells/conditionalformattingcollection/index_of/#aspose.cells.FormatConditionCollection-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.FormatConditionCollection) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.FormatConditionCollection-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.FormatConditionCollection-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [remove_area](/cells/python-net/es/aspose.cells/conditionalformattingcollection/remove_area/#int-int-int-int) | Elimine todo el formato condicional en el rango.|
| [add](/cells/python-net/es/aspose.cells/conditionalformattingcollection/add/#) | Agrega FormatConditions a la colección.|
| [binary_search](/cells/python-net/es/aspose.cells/conditionalformattingcollection/binary_search/#aspose.cells.FormatConditionCollection) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



###  Ejemplo

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

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
# Add condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Add condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`FormatCondition`](/cells/python-net/es/aspose.cells/formatcondition)
