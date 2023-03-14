---
title: change_palette método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells/workbook/change_palette/
is_root: false
---
##  change_palette(color, index) {#aspose.pydrawing.Color-int}
Cambia la paleta de la hoja de cálculo en el índice especificado.



```python
def change_palette(self, color, index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| color | aspose.pydrawing.Color | Estructura de colores.|
| index | int | Índice de paleta, 0 - 55.|
###  Observaciones

La paleta tiene 56 entradas, cada una representada por un valor RGB.


Si establece un color que no está en la paleta, no tendrá efecto.


Entonces, si desea establecer un color personalizado, cambie la paleta al principio.


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
| cian| 0| 255| 255 |
| Granate| 128| 0| 0 |
| Verde| 0| 128| 0 |
| Armada| 0| 0| 128 |
| Aceituna| 128| 128| 0 |
| Púrpura| 128| 0| 128 |
| verde azulado| 0| 128| 128 |
| Plata| 192| 192| 192 |
| Gris| 128| 128| 128 |
| color17| 153| 153| 255 |
| color18| 153| 51| 102 |
| color19| 255| 255| 204 |
| color20| 204| 255| 255 |
| color21| 102| 0| 102 |
| color22| 255| 128| 128 |
| color23| 0| 102| 204 |
| color24| 204| 204| 255 |
| color25| 0| 0| 128 |
| color26| 255| 0| 255 |
| color27| 255| 255| 0 |
| color28| 0| 255| 255 |
| color29| 128| 0| 128 |
| color30| 128| 0| 0 |
| Color31| 0| 128| 128 |
| Color32| 0| 0| 255 |
| Color33| 0| 204| 255 |
| Color34| 204| 255| 255 |
| Color35| 204| 255| 204 |
| Color36| 255| 255| 153 |
| Color37| 153| 204| 255 |
| color38| 255| 153| 204 |
| Color39| 204| 153| 255 |
| Color40| 255| 204| 153 |
| color41| 51| 102| 255 |
| Color42| 51| 204| 204 |
| Color43| 153| 204| 0 |
| color44| 255| 204| 0 |
| Color45| 255| 153| 0 |
| color46| 255| 102| 0 |
| Color47| 102| 102| 153 |
| color48| 150| 150| 150 |
| Color49| 0| 51| 102 |
| color50| 51| 153| 102 |
| Color51| 0| 51| 0 |
| Color52| 51| 51| 0 |
| Color53| 153| 51| 0 |
|color54| 153| 51| 102 |
| color55| 51| 51| 153 |
| Color56| 51| 51| 51 |


###  Ver también

* módulo [aspose.cells](../../)
* clase [Workbook](/cells/python-net/es/aspose.cells/workbook)
