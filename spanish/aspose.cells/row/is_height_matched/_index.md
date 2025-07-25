---
title: is_height_matched propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 190
url: /es/aspose.cells/row/is_height_matched/
is_root: false
---
##  is_height_matched propiedad

Indica si la altura de la fila coincide con la configuración de fuente predeterminada actual del libro de trabajo.
Esta propiedad también indica que la altura de la fila es "automática" sin un valor de altura personalizado establecido por el usuario.

###  Observaciones

Cuando esta propiedad es verdadera, si el contenido de esta fila cambia,
Generalmente es necesario volver a calcular la altura de la fila (por ejemplo, [`Worksheet.auto_fit_rows`](/cells/python-net/es/aspose.cells/worksheet/auto_fit_rows))
para obtener el mismo resultado que se muestra en MS Excel cuando abre el libro en él.
###  Definición:
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Row`](/cells/python-net/es/aspose.cells/row)
