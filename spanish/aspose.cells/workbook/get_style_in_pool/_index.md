---
title: método get_style_in_pool
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 200
url: /es/aspose.cells/workbook/get_style_in_pool/
is_root: false
---
##  get_style_in_pool(self, index) {#int}
Obtiene el estilo en el grupo de estilos.
Todos los estilos del libro de trabajo se reunirán en un grupo.
Sólo hay un índice de referencia simple en las celdas.


###  Devoluciones

El estilo en el pool corresponde al índice dado, puede ser nulo.


```python

def get_style_in_pool(self, index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| index | int | El índice.|
###  Observaciones

Si se cambia el estilo devuelto, se cambiará el estilo de todas las celdas (que hacen referencia a este estilo).


###  Ver también

* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
