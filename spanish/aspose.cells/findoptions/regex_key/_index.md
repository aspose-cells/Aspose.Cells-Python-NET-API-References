---
title: regex_key propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key propiedad

Indica si la clave buscada es una expresión regular.
Si es verdadero, la clave buscada se tomará como expresión regular y se analizará.
De lo contrario, la clave se analizará de acuerdo con las reglas de MS Excel.

###  Observaciones

Aunque la clave de búsqueda se haya especificado como expresión regular,
Puede refactorizarse de acuerdo con lo especificado [`FindOptions.look_at_type`](/cells/python-net/es/aspose.cells/findoptions#look_at_type).
Por ejemplo, cuando el tipo es [`LookAtType.CONTAINS`](/cells/python-net/es/aspose.cells/lookattype#CONTAINS) (este es el valor predeterminado para esta opción),
Se agregarán comodines al principio y al final de la clave de búsqueda automáticamente para garantizar que la coincidencia sea correcta.
Marcado como "contiene". En este caso, las expresiones regulares se volverán más complejas.
y el rendimiento también disminuirá.
Entonces, por razones de rendimiento, si el usuario ha especificado la regla exacta para la expresión regular, no hay necesidad de...
Utilice [`FindOptions.look_at_type`](/cells/python-net/es/aspose.cells/findoptions#look_at_type) como restricción adicional y el usuario puede configurarlo como [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/es/aspose.cells/lookattype#ENTIRE_CONTENT)
para obtener un mejor rendimiento.
###  Definición:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FindOptions`](/cells/python-net/es/aspose.cells/findoptions)
