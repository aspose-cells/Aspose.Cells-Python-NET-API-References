---
title: check_font_compatibility propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/pptxsaveoptions/check_font_compatibility/
is_root: false
---
##  check_font_compatibility propiedad

Indica si se debe verificar la compatibilidad de fuentes para cada carácter del texto.

###  Observaciones

El valor por defecto es verdadero.
Deshabilitar esta propiedad puede brindar un mejor rendimiento.
Pero cuando la fuente de texto/carácter predeterminada o especificada no se puede utilizar para representarlo,
Es posible que aparezcan caracteres ilegibles (como un bloque) en el pdf generado.
Para tal situación, el usuario debe mantener esta propiedad como verdadera para que
se puede buscar una fuente alternativa y utilizarla para representar el texto;
###  Definición:
```python
@property
def check_font_compatibility(self):
    ...
@check_font_compatibility.setter
def check_font_compatibility(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`PptxSaveOptions`](/cells/python-net/es/aspose.cells/pptxsaveoptions)
