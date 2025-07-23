---
title: look_at_type propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type propiedad

Mira el tipo.

###  Observaciones

Cuando [`FindOptions.regex_key`](/cells/python-net/es/aspose.cells/findoptions#regex_key) es verdadero y el usuario ha especificado la regla exacta para la expresión regular,
Para tener en cuenta el rendimiento, esta propiedad debe establecerse como [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/es/aspose.cells/lookattype#ENTIRE_CONTENT).
De lo contrario, refactorizaremos la clave de búsqueda para garantizar que pueda coincidir según el tipo específico.
Por ejemplo, cuando el tipo es [`LookAtType.CONTAINS`](/cells/python-net/es/aspose.cells/lookattype#CONTAINS) (este es el valor predeterminado para esta propiedad),
Agregaremos comodines al principio y al final de la clave de búsqueda automáticamente.
En este caso, las expresiones regulares se volverán más complejas y el rendimiento también disminuirá.
###  Definición:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FindOptions`](/cells/python-net/es/aspose.cells/findoptions)
* clase [`LookAtType`](/cells/python-net/es/aspose.cells/lookattype)
