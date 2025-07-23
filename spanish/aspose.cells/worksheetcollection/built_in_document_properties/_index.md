---
title: built_in_document_properties propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 280
url: /es/aspose.cells/worksheetcollection/built_in_document_properties/
is_root: false
---
##  built_in_document_properties propiedad

Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades de documento integradas de la hoja de cálculo.

###  Observaciones

No se puede agregar una nueva propiedad a la lista de propiedades integradas del documento. Solo se puede obtener una propiedad integrada y modificar su valor.
La siguiente es la lista de nombres de propiedades incorporadas:

Título


Sujeto


Autor


Palabras clave


Comentarios


Plantilla


Último autor


Número de revisión


Nombre de la aplicación


Fecha de última impresión


Fecha de creación


Última hora de guardado


Tiempo total de edición


Número de páginas


Número de palabras


Número de caracteres


Seguridad


Categoría


Formato


Gerente


Compañía


Número de bytes


Número de líneas


Número de párrafos


Número de diapositivas


Número de notas


Número de diapositivas ocultas


Número de clips multimedia

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.worksheets.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Definición:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`BuiltInDocumentPropertyCollection`](/cells/python-net/es/aspose.cells.properties/builtindocumentpropertycollection)
* clase [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
