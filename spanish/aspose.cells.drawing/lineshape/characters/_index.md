---
title: método characters
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells.drawing/lineshape/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Devuelve un objeto Caracteres que representa un rango de characters dentro del texto.


###  Devoluciones

Objeto de personajes.


```python

def characters(self, start_index, length):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| start_index | int | El índice del inicio del carácter.|
| length | int | El número de caracteres.|
###  Observaciones

Este método sólo funciona en formas con título.
###  Ejemplo


```python

fontSetting = shape.characters(0, 4)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`LineShape`](/cells/python-net/es/aspose.cells.drawing/lineshape)
