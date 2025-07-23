---
title: método get_display_style
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Obtiene el estilo de visualización de esta celda.


###  Devoluciones

estilo de visualización de esta celda


```python

def get_display_style(self):
    ...
```


###  Observaciones

Lo mismo ocurre con el uso de [`BorderType.SIDE_BORDERS`](/cells/python-net/es/aspose.cells/bordertype#SIDE_BORDERS)
para [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style).
Es decir, este método comprobará y ajustará los bordes superior/inferior/izquierdo/derecho de esta celda.
según el estilo([`Cell.get_style`](/cells/python-net/es/aspose.cells/cell/get_style)) de sus celdas adyacentes,
pero no verifique las celdas fusionadas ni el estilo de visualización de las celdas adyacentes.

##  get_display_style(self, include_merged_borders) {#bool}
Obtiene el estilo de visualización de esta celda.


###  Devoluciones

estilo de visualización de esta celda


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| include_merged_borders | bool | Indica si se verifican los bordes de las celdas fusionadas.|
###  Observaciones

Si la bandera especificada es falsa, entonces es lo mismo que [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style).
De lo contrario, es lo mismo con el uso.
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
para [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Obtiene el estilo de visualización de esta celda.


###  Devoluciones

estilo de visualización de esta celda


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/es/aspose.cells/bordertype) | Indica qué fronteras deben comprobarse y ajustarse<br/> según los bordes de las celdas adyacentes.|
###  Observaciones

Si esta celda también se ve afectada por otras configuraciones como formato condicional, objetos de lista, etc.,
Entonces el estilo de visualización puede ser diferente al [`Cell.get_style`](/cells/python-net/es/aspose.cells/cell/get_style).

Para las banderas de ajuste de bordes según celdas adyacentes,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
Indica si se verifican y combinan los bordes inferior/superior/derecho/izquierdo de
las celdas izquierda/derecha/superior/inferior adyacentes a ésta.

Por razones de rendimiento y compatibilidad,
Algunas enumeraciones se utilizan para denotar algunas operaciones especiales:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
Indica si se verifica y combina el borde inferior/derecho de las celdas fusionadas con este.

[`BorderType.DIAGONAL`](/cells/python-net/es/aspose.cells/bordertype#DIAGONAL)(es decir, tanto [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/es/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) como
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/es/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) se han establecido) indica verificar y combinar bordes
del estilo de visualización de las celdas adyacentes.

Tenga en cuenta que al verificar los bordes y estilos de las celdas adyacentes, especialmente los estilos de visualización,
Es un proceso que consume mucho tiempo. Si no es necesario obtener los bordes para el estilo devuelto,
Usando [`BorderType.NONE`](/cells/python-net/es/aspose.cells/bordertype#NONE) para deshabilitar el proceso de celdas adyacentes
Dará un mejor rendimiento.
Al obtener los bordes de celdas adyacentes a partir de estilos definidos solo en esas celdas (sin configurar
[`BorderType.DIAGONAL`](/cells/python-net/es/aspose.cells/bordertype#DIAGONAL)), el rendimiento también puede ser mejor porque se verifica
El estilo de visualización de una celda también consume mucho tiempo.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
