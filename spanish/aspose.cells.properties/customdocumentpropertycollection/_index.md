---
title: CustomDocumentPropertyCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection clase
Una colección de propiedades de documentos personalizadas.



**Herencia:** [`CustomDocumentPropertyCollection`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection)



El tipo CustomDocumentPropertyCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get(self, name)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`add(self, name, value)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Crea una nueva propiedad de documento personalizada del**Tipo de propiedad.Cadena** tipo de datos.|
| [`add(self, name, value)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Crea una nueva propiedad de documento personalizada del**Tipo de propiedad.Número** tipo de datos.|
| [`add(self, name, value)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Crea una nueva propiedad de documento personalizada del**Tipo de propiedad.Fecha y hora** tipo de datos.|
| [`add(self, name, value)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Crea una nueva propiedad de documento personalizada del**Tipo de propiedad.Booleano** tipo de datos.|
| [`add(self, name, value)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Crea una nueva propiedad de documento personalizada del**Tipo de propiedad.Float** tipo de datos.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |Crea una nueva propiedad de documento personalizada que se vincula al contenido.|
| [`update_linked_property_value(self)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | Actualizar el valor de la propiedad del documento personalizado que se vincula al contenido.|
| [`update_linked_range(self)`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Actualizar el valor de la propiedad del documento personalizado al rango vinculado.|



###  Observaciones

Cada objeto [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) representa una propiedad personalizada de un documento contenedor.

###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Ver también
* módulo [`aspose.cells.properties`](..)
* clase [`CustomDocumentPropertyCollection`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection)
* clase [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty)
