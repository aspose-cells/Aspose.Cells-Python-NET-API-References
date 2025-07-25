---
title: método get_picture
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells/pagesetup/get_picture/
is_root: false
---
##  get_picture(self, is_header, section) {#bool-int}
Obtiene el objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture) del encabezado/pie de página.


###  Devoluciones

Devuelve el objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).
Devuelve nulo si no hay imagen.


```python

def get_picture(self, is_header, section):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| is_header | bool | Indica si está en el encabezado o pie de página.|
| section | int |0: Sección izquierda, 1: Sección central, 2: Sección derecha.|


##  get_picture(self, is_first, is_even, is_header, section) {#bool-bool-bool-int}
Obtiene el objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture) del encabezado/pie de página.


###  Devoluciones

Devuelve el objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def get_picture(self, is_first, is_even, is_header, section):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| is_first | bool | Indica si se obtendrá la imagen del encabezado/pie de página de la primera página.|
| is_even | bool | Indica si se obtiene la imagen del encabezado/pie de página.|
| is_header | bool | Indica si se obtiene la imagen del encabezado/pie de página.|
| section | int |0: Sección izquierda, 1: Sección central, 2: Sección derecha.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`PageSetup`](/cells/python-net/es/aspose.cells/pagesetup)
* clase [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture)
