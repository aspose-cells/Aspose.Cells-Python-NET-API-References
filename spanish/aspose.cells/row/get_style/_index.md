---
title: método get_style
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells/row/get_style/
is_root: false
---
##  get_style(self) {#}
Obtiene el estilo de esta fila.



```python

def get_style(self):
    ...
```


###  Observaciones

Modificar directamente el objeto de estilo devuelto no tiene efecto en esta fila ni en ninguna celda de esta fila.
Debes llamar al método [`Row.apply_style`](/cells/python-net/es/aspose.cells/row/apply_style) o [`Row.set_style`](/cells/python-net/es/aspose.cells/row/set_style)
para aplicar el cambio a esta fila.

El estilo de la fila es el estilo que heredarán las celdas de esta fila (aquellas celdas que no tienen configuraciones de estilo personalizadas,
(como celdas existentes a las que no se les ha asignado un estilo de forma explícita, o aquellas que no han sido instanciadas)


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Row`](/cells/python-net/es/aspose.cells/row)
