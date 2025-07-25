---
title: método get_linked_cell
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells.drawing/groupbox/get_linked_cell/
is_root: false
---
##  get_linked_cell(self, is_r1c1, is_local) {#bool-bool}
Obtiene el rango vinculado al valor del control.


###  Devoluciones

El rango vinculado al valor del control.


```python

def get_linked_cell(self, is_r1c1, is_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| is_r1c1 | bool | Si la fórmula debe formatearse como R1C1.|
| is_local | bool | Si la fórmula necesita formatearse según la configuración regional.|

###  Ejemplo

```python

# You may get results like '$A$1'
link = shape.get_linked_cell(False, False)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`GroupBox`](/cells/python-net/es/aspose.cells.drawing/groupbox)
