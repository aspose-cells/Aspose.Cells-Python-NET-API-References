---
title: método set_two_color_gradient
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells.drawing/fillformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
Establece el relleno especificado en un degradado de dos colores.
Sólo se aplica para Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Un color degradado.|
| color2 | aspose.pydrawing.Color | Dos colores degradados.|
| style | [`GradientStyleType`](/cells/python-net/es/aspose.cells.drawing/gradientstyletype) | Estilo de sombreado degradado.|
| variant | int | La variante de degradado. Puede tener un valor entre 1 y 4, correspondiente a una de las cuatro variantes de la pestaña Degradado del cuadro de diálogo Efectos de relleno. Si el estilo es GradientStyle.FromCenter, el argumento Variant solo puede ser 1 o 2.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Establece el relleno especificado en un degradado de dos colores.
Sólo se aplica para Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Un color degradado.|
| transparency1 | float | El grado de transparencia del color1 como un valor de 0,0 (opaco) a 1,0 (transparente).|
| color2 | aspose.pydrawing.Color | Dos colores degradados.|
| transparency2 | float | El grado de transparencia del color2 como un valor de 0,0 (opaco) a 1,0 (transparente).|
| style | [`GradientStyleType`](/cells/python-net/es/aspose.cells.drawing/gradientstyletype) | Estilo de sombreado degradado.|
| variant | int | La variante de degradado. Puede tener un valor entre 1 y 4, correspondiente a una de las cuatro variantes de la pestaña Degradado del cuadro de diálogo Efectos de relleno. Si el estilo es GradientStyle.FromCenter, el argumento Variant solo puede ser 1 o 2.|



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`FillFormat`](/cells/python-net/es/aspose.cells.drawing/fillformat)
