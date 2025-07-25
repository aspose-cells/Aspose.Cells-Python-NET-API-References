---
title: método get_input_range
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells.drawing/textbox/get_input_range/
is_root: false
---
##  get_input_range(self, is_r1c1, is_local) {#bool-bool}
Obtiene el rango utilizado para llenar el control.


###  Devoluciones

El rango utilizado para llenar el control.


```python

def get_input_range(self, is_r1c1, is_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| is_r1c1 | bool | Si la fórmula debe formatearse como R1C1.|
| is_local | bool | Si la fórmula necesita formatearse según la configuración regional.|

###  Ejemplo

```python

range = shape.get_input_range(False, True)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox)
