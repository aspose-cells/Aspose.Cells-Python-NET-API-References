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
| [capacity](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Agrega módulo para una hoja de trabajo.|
| [`add(self, type, name)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Añade módulo.|
| [`get(self, index)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/get/#int) | Obtiene [`VbaModule`](/cells/python-net/es/aspose.cells.vba/vbamodule) en la lista por el índice.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/get/#str) | Obtiene [`VbaModule`](/cells/python-net/es/aspose.cells.vba/vbamodule) en la lista por el nombre.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Representa los datos del Diseñador.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Insertar formulario de usuario en el proyecto VBA.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Elimina el módulo de una hoja de cálculo.|
| [`remove_by_name(self, name)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Eliminar el módulo por el nombre|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



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
