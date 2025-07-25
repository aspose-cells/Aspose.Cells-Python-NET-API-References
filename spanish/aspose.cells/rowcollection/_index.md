---
title: RowCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1240
url: /es/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection clase
Recopila los [`Row`](/cells/python-net/es/aspose.cells/row) objetos que representan las filas individuales en una hoja de cálculo.



El tipo RowCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [count](/cells/python-net/es/aspose.cells/rowcollection/count) | Obtiene el número de filas en esta colección.|



Obtiene un objeto [`Row`](/cells/python-net/es/aspose.cells/row) según el índice de fila indicado. Se instanciará el objeto de fila con el índice de fila indicado si no existía previamente.
###  Indexador
| Nombre| Descripción|
| :- | :- |
| [index] |  |


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/es/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Obtiene un enumerador que itera filas a través de esta colección|
| [`get_row_by_index(self, index)`](/cells/python-net/es/aspose.cells/rowcollection/get_row_by_index/#int) | Obtiene el objeto de fila por la posición en la lista.|
| [`clear(self)`](/cells/python-net/es/aspose.cells/rowcollection/clear/#) | Borrar todas las filas y celdas.|
| [`remove_at(self, index)`](/cells/python-net/es/aspose.cells/rowcollection/remove_at/#int) | Eliminar el elemento de fila en el índice (posición) especificado en esta colección.|



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
