---
title: ColumnCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 280
url: /es/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection clase
Colección de los objetos [`Column`](/cells/python-net/es/aspose.cells/column) que representan las columnas (configuraciones) individuales en una hoja de trabajo.
El objeto Columna solo representa configuraciones como el ancho de la columna, los estilos, etc. para toda la columna,
No tiene nada que ver con el hecho de que haya celdas (datos) no vacías o no en la columna correspondiente.
Y el "Recuento" de esta colección solo representa el recuento de objetos de columna de los que se han creado instancias en esta colección.
No tiene nada que ver con el hecho de que haya celdas (datos) no vacías o no en la hoja de trabajo.



El tipo ColumnCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/columncollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [copy_to](/cells/python-net/es/aspose.cells/columncollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells/columncollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells/columncollection/index_of/#aspose.cells.Column-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells/columncollection/index_of/#aspose.cells.Column-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells/columncollection/last_index_of/#aspose.cells.Column) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [get_by_index](/cells/python-net/es/aspose.cells/columncollection/get_by_index/#int) | Obtiene el objeto de columna por el índice.|
| [get_column_by_index](/cells/python-net/es/aspose.cells/columncollection/get_column_by_index/#int) | Obtiene el objeto [`Column`](/cells/python-net/es/aspose.cells/column) por su posición en la lista.|
| [binary_search](/cells/python-net/es/aspose.cells/columncollection/binary_search/#aspose.cells.Column) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



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
