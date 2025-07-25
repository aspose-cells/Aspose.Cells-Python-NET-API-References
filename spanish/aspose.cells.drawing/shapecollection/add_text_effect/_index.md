---
title: método add_text_effect
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 360
url: /es/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
Inserta un objeto WordArt.


###  Devoluciones

Devuelve un objeto Shape que representa el nuevo objeto WordArt.


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/es/aspose.cells.drawing/msopresettexteffect) | El tipo de efecto de texto preestablecido mso.|
| text | str | El texto de WordArt.|
| font_name | str | El nombre de la fuente.|
| size | int | El tamaño de la fuente|
| font_bold | bool | Indica si la fuente está en negrita.|
| font_italic | bool | Indica si la fuente es cursiva.|
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de la forma desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int |Representa el desplazamiento horizontal de la forma desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura de la forma, en unidades de píxeles.|
| width | int | Representa el ancho de la forma, en unidades de píxeles.|

###  Ejemplo

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
