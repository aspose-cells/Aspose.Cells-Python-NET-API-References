---
title: VbaModuleCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection clase
Representa la lista de [`VbaModule`](/cells/python-net/es/aspose.cells.vba/vbamodule)



El tipo VbaModuleCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.Worksheet) | Agrega un módulo para una hoja de trabajo.|
| [add](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.VbaModuleType-str) | Agrega módulo.|
| [copy_to](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [add_designer_storage](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Representa los datos de Designer.|
| [add_user_form](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Inserte el formulario de usuario en el proyecto VBA.|
| [binary_search](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.VbaModule) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ver también
* módulo [`aspose.cells.vba`](..)
* clase [`VbaModule`](/cells/python-net/es/aspose.cells.vba/vbamodule)
