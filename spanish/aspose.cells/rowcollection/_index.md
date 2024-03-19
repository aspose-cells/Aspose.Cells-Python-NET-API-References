---
title: RowCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1350
url: /es/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection clase
Recopila los objetos [`Row`](/cells/python-net/es/aspose.cells/row) que representan las filas individuales de una hoja de trabajo.



El tipo RowCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [count](/cells/python-net/es/aspose.cells/rowcollection/count) | Obtiene el número de filas de esta colección.|



Obtiene un objeto [`Row`](/cells/python-net/es/aspose.cells/row) según el índice de fila determinado. Se creará una instancia del objeto Fila del índice de fila dado si no existe antes.
###  indexador
| Nombre| Descripción|
| :- | :- |
| [index] |  |


###  Métodos
| Método| Descripción|
| :- | :- |
| [get_enumerator](/cells/python-net/es/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Obtiene un enumerador que itera filas a través de esta colección.|
| [get_row_by_index](/cells/python-net/es/aspose.cells/rowcollection/get_row_by_index/#int) | Obtiene el objeto de fila por su posición en la lista.|
| [clear](/cells/python-net/es/aspose.cells/rowcollection/clear/#) | Borre todas las filas y celdas.|
| [remove_at](/cells/python-net/es/aspose.cells/rowcollection/remove_at/#int) | Elimine el elemento de fila en el índice (posición) especificado en esta colección.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Row`](/cells/python-net/es/aspose.cells/row)
