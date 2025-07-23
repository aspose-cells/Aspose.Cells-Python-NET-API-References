---
title: Metodo add_text_effect
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 360
url: /it/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
Inserisce un oggetto WordArt.


###  ritorna

Restituisce un oggetto Shape che rappresenta il nuovo oggetto WordArt.


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/it/aspose.cells.drawing/msopresettexteffect) | Tipo di effetto di testo preimpostato mso.|
| text | str | Il testo WordArt.|
| font_name | str | Il nome del font.|
| size | int | La dimensione del carattere|
| font_bold | bool | Indica se il carattere è in grassetto.|
| font_italic | bool | Indica se il carattere è corsivo.|
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale della forma dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int |Rappresenta lo scostamento orizzontale della forma dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza della forma, in unità di pixel.|
| width | int | Rappresenta la larghezza della forma, in unità di pixel.|

###  Esempio

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
