---
title: método change_palette
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells/workbook/change_palette/
is_root: false
---
##  change_palette(self, color, index) {#aspose.pydrawing.Color-int}
Cambia la paleta de la hoja de cálculo en el índice especificado.



```python

def change_palette(self, color, index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| color | aspose.pydrawing.Color | Estructura del color.|
| index | int | Índice de paleta, 0 - 55.|
###  Observaciones

La paleta tiene 56 entradas, cada una representada por un valor RGB.


Si establece un color que no está en la paleta, no tendrá efecto.


Entonces, si desea establecer un color personalizado, primero cambie la paleta.


La siguiente es la paleta de colores estándar.

| Color| Rojo| Verde| Azul|
| :- | :- | :- | :- |
| Negro| 0| 0| 0 |
| Blanco| 255| 255| 255 |
| Rojo| 255| 0| 0 |
| Cal| 0| 255| 0 |
| Azul| 0| 0| 255 |
| Amarillo| 255| 255| 0 |
| Magenta| 255| 0| 255 |
| Cian| 0| 255| 255 |
| Granate| 128| 0| 0 |
| Verde| 0| 128| 0 |
| Marina de guerra| 0| 0| 128 |
| Aceituna| 128| 128| 0 |
| Púrpura| 128| 0| 128 |
| Verde azulado| 0| 128| 128 |
| Plata| 192| 192| 192 |
| Gris| 128| 128| 128 |
|Color17| 153| 153| 255 |
| Color18| 153| 51| 102 |
| Color19| 255| 255| 204 |
| Color20| 204| 255| 255 |
| Color21| 102| 0| 102 |
| Color22| 255| 128| 128 |
| Color23| 0| 102| 204 |
| Color24| 204| 204| 255 |
| Color25| 0| 0| 128 |
| Color26| 255| 0| 255 |
| Color27| 255| 255| 0 |
| Color28| 0| 255| 255 |
| Color29| 128| 0| 128 |
| Color30| 128| 0| 0 |
| Color31| 0| 128| 128 |
| Color32| 0| 0| 255 |
| Color33| 0| 204| 255 |
| Color34| 204| 255| 255 |
| Color35| 204| 255| 204 |
| Color36| 255| 255| 153 |
| Color37| 153| 204| 255 |
| Color38| 255| 153| 204 |
| Color39| 204| 153| 255 |
| Color40| 255| 204| 153 |
| Color41| 51| 102| 255 |
| Color42| 51| 204| 204 |
| Color43| 153| 204| 0 |
| Color44| 255| 204| 0 |
| Color45| 255| 153| 0 |
| Color46| 255| 102| 0 |
| Color47| 102| 102| 153 |
| Color48| 150| 150| 150 |
| Color49| 0| 51| 102 |
| Color50| 51| 153| 102 |
| Color51| 0| 51| 0 |
| Color52| 51| 51| 0 |
| Color53| 153| 51| 0 |
| Color54| 153| 51| 102 |
| Color55| 51| 51| 153 |
| Color56| 51| 51| 51 |


###  Ver también

* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
