---
title: método set_one_color_gradient
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.drawing/fillformat/set_one_color_gradient/
is_root: false
---
##  set_one_color_gradient(self, color, degree, style, variant) {#aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Establece el relleno especificado en un degradado de un solo color.
Sólo se aplica para Excel 2007.



```python

def set_one_color_gradient(self, color, degree, style, variant):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| color | aspose.pydrawing.Color | Un color degradado.|
| degree | float | Grado de degradado. Puede ser un valor entre 0,0 (oscuro) y 1,0 (claro).|
| style | [`GradientStyleType`](/cells/python-net/es/aspose.cells.drawing/gradientstyletype) | Estilo de sombreado degradado.|
| variant | int | La variante de degradado. Puede tener un valor entre 1 y 4, correspondiente a una de las cuatro variantes de la pestaña Degradado del cuadro de diálogo Efectos de relleno. Si el estilo es GradientStyle.FromCenter, el argumento Variant solo puede ser 1 o 2.|



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`FillFormat`](/cells/python-net/es/aspose.cells.drawing/fillformat)
