---
title: ColumnCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 250
url: /es/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection clase
Colección de los [`Column`](/cells/python-net/es/aspose.cells/column) objetos que representan las columnas(configuraciones) individuales en una hoja de cálculo.
El objeto Columna solo representa las configuraciones como ancho de columna, estilos, etc. para toda la columna.
no tiene nada que ver con el hecho de que haya celdas (datos) no vacías o no estén en la columna correspondiente.
Y el "Count" de esta colección solo representa el conteo de objetos de columna que se han instanciado en esta colección,
no tiene nada que ver con el hecho de que haya celdas (datos) no vacías o no en la hoja de cálculo.



El tipo ColumnCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/columncollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/columncollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/columncollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get_by_index(self, index)`](/cells/python-net/es/aspose.cells/columncollection/get_by_index/#int) | Obtiene el objeto de columna por el índice.|
| [`get_column_by_index(self, index)`](/cells/python-net/es/aspose.cells/columncollection/get_column_by_index/#int) | Obtiene el objeto [`Column`](/cells/python-net/es/aspose.cells/column) por la posición en la lista.|
| [`get(self, column_index)`](/cells/python-net/es/aspose.cells/columncollection/get/#int) | Añadir API for Python Vía .Net.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Column`](/cells/python-net/es/aspose.cells/column)
