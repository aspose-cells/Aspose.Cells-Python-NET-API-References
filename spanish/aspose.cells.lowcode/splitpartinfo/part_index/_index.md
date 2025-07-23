---
title: part_index propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells.lowcode/splitpartinfo/part_index/
is_root: false
---
##  part_index propiedad

Índice de la parte actual en la secuencia (basado en 0).
-1 significa que no hay partes múltiples, por lo que el resultado es único.

###  Observaciones

Si es necesario procesar varias hojas y cada hoja se procesa (divide)
Por separado, el índice de la pieza siempre comienza desde 0 para cada hoja.
Por ejemplo, al convertir un libro de trabajo a imágenes,
Representa el índice de la página de salida de la hoja procesada actualmente.
Y -1 indica que solo hay una página para la hoja actual.
###  Definición:
```python
@property
def part_index(self):
    ...
```

###  Ver también
* módulo [`aspose.cells.lowcode`](../../)
* clase [`SplitPartInfo`](/cells/python-net/es/aspose.cells.lowcode/splitpartinfo)
