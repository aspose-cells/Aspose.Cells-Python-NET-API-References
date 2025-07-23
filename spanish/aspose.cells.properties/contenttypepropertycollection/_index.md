---
title: ContentTypePropertyCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells.properties/contenttypepropertycollection/
is_root: false
---
##  ContentTypePropertyCollection clase
Una colección de [`ContentTypeProperty`](/cells/python-net/es/aspose.cells.properties/contenttypeproperty) objetos que representan información adicional.



El tipo ContentTypePropertyCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, name, value)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/add/#str-str) | Agrega información de propiedad de tipo de contenido.|
| [`add(self, name, value, type)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/add/#str-str-str) | Agrega información de propiedad de tipo de contenido.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/get/#str) | Obtiene la propiedad de tipo de contenido por el nombre de la propiedad.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.properties/contenttypepropertycollection/binary_search/#aspose.cells.properties.contenttypeproperty) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Ver también
* módulo [`aspose.cells.properties`](..)
* clase [`ContentTypeProperty`](/cells/python-net/es/aspose.cells.properties/contenttypeproperty)
