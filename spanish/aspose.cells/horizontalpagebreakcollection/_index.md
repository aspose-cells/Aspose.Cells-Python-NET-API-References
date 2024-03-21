---
title: HorizontalPageBreakCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 790
url: /es/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection clase
Encapsula una colección de [`HorizontalPageBreak`](/cells/python-net/es/aspose.cells/horizontalpagebreak) objetos.



El tipo HorizontalPageBreakCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) |Agrega un salto de página horizontal a la colección.|
| [add](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#int) |Agrega un salto de página horizontal a la colección.|
| [add](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#int-int) |Agrega un salto de página horizontal a la colección.|
| [add](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#str) |Agrega un salto de página horizontal a la colección.|
| [copy_to](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [binary_search](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.HorizontalPageBreak) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`HorizontalPageBreak`](/cells/python-net/es/aspose.cells/horizontalpagebreak)
