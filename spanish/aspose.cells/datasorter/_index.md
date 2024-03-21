---
title: DataSorter clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 440
url: /es/aspose.cells/datasorter/
is_root: false
---
##  DataSorter clase
Descripción resumida de DataSorter.



El tipo DataSorter expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [keys](/cells/python-net/es/aspose.cells/datasorter/keys) | Obtiene la lista de claves del clasificador de datos.|
| [has_headers](/cells/python-net/es/aspose.cells/datasorter/has_headers) | Representa si el rango tiene encabezados.|
| [key1](/cells/python-net/es/aspose.cells/datasorter/key1) | Representa el índice de la primera columna ordenada (posición absoluta, la columna A es 0, B es 1, ...).|
| [order1](/cells/python-net/es/aspose.cells/datasorter/order1) | Representa el orden de clasificación de la primera clave.|
| [key2](/cells/python-net/es/aspose.cells/datasorter/key2) | Representa el índice de la segunda columna ordenada (posición absoluta, la columna A es 0, B es 1, ...).|
| [order2](/cells/python-net/es/aspose.cells/datasorter/order2) | Representa el orden de clasificación de la segunda clave.|
| [key3](/cells/python-net/es/aspose.cells/datasorter/key3) | Representa el índice de la tercera columna ordenada (posición absoluta, la columna A es 0, B es 1, ...).|
| [order3](/cells/python-net/es/aspose.cells/datasorter/order3) | Representa el orden de clasificación de la tercera clave.|
| [sort_left_to_right](/cells/python-net/es/aspose.cells/datasorter/sort_left_to_right) | Verdadero significa que la orientación de clasificación es de izquierda a derecha.<br/>Falso significa que la orientación de clasificación es de arriba a abajo.<br/> El valor predeterminado es falso.|
| [case_sensitive](/cells/python-net/es/aspose.cells/datasorter/case_sensitive) | Obtiene y establece si se distingue entre mayúsculas y minúsculas al comparar cadenas.|
| [sort_as_number](/cells/python-net/es/aspose.cells/datasorter/sort_as_number) |Indica si se está clasificando algo que parece un número.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add_key](/cells/python-net/es/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder) | Agrega índice de columnas ordenadas y orden de clasificación.|
| [add_key](/cells/python-net/es/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder-str) | Agrega un índice de columnas ordenadas y un orden de clasificación con una lista de clasificación personalizada.|
| [add_key](/cells/python-net/es/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any) | Agrega un índice de columnas ordenadas y un orden de clasificación con una lista de clasificación personalizada.|
| [add_key](/cells/python-net/es/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder-list) | Agrega un índice de columnas ordenadas y un orden de clasificación con una lista de clasificación personalizada.|
| [sort](/cells/python-net/es/aspose.cells/datasorter/sort/#aspose.cells.Cells-int-int-int-int) | Ordena los datos del área.|
| [sort](/cells/python-net/es/aspose.cells/datasorter/sort/#aspose.cells.Cells-aspose.cells.CellArea) | Ordenar los datos del área.|
| [sort](/cells/python-net/es/aspose.cells/datasorter/sort/#) | Ordena los datos en el rango.|
| [clear](/cells/python-net/es/aspose.cells/datasorter/clear/#) | Borre todas las configuraciones.|



###  Ejemplo

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
