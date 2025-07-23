---
title: Metodo add_word_art
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 380
url: /it/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.PresetWordArtStyle-str-int-int-int-int-int-int}
Aggiunge WordArt preimpostato da Excel 2007.


###  ritorna




```python

def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| style | [`PresetWordArtStyle`](/cells/python-net/it/aspose.cells.drawing/presetwordartstyle) | Lo stile WordArt preimpostato.|
| text | str | Il testo.|
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale della forma dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int |Rappresenta lo scostamento orizzontale della forma dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza della forma, in unità di pixel.|
| width | int | Rappresenta la larghezza della forma, in unità di pixel.|

###  Esempio

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
