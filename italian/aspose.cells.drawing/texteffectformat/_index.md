---
title: TextEffectFormat classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 680
url: /it/aspose.cells.drawing/texteffectformat/
is_root: false
---
##  TextEffectFormat classe
Contiene proprietà e metodi che si applicano agli oggetti WordArt.



Il tipo TextEffectFormat espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [text](/cells/python-net/it/aspose.cells.drawing/texteffectformat/text) | Il testo in WordArt.|
| [font_name](/cells/python-net/it/aspose.cells.drawing/texteffectformat/font_name) | Il nome del font utilizzato in WordArt.|
| [font_bold](/cells/python-net/it/aspose.cells.drawing/texteffectformat/font_bold) | Indica se il carattere è in grassetto.|
| [font_italic](/cells/python-net/it/aspose.cells.drawing/texteffectformat/font_italic) | Indica se il carattere è corsivo.|
| [rotated_chars](/cells/python-net/it/aspose.cells.drawing/texteffectformat/rotated_chars) | Se è vero, i caratteri nella WordArt specificata vengono ruotati di 90 gradi rispetto alla forma di delimitazione della WordArt.|
| [font_size](/cells/python-net/it/aspose.cells.drawing/texteffectformat/font_size) | La dimensione (in punti) del font utilizzato in WordArt.|
| [preset_shape](/cells/python-net/it/aspose.cells.drawing/texteffectformat/preset_shape) | Ottiene e imposta il tipo di forma preimpostato.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_text_effect(self, effect)`](/cells/python-net/it/aspose.cells.drawing/texteffectformat/set_text_effect/#aspose.cells.drawing.msopresettexteffect) | Imposta l'effetto di testo preimpostato.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.drawing import MsoPresetTextEffect

# Instantiating a Workbook object
workbook = Workbook()
shapes = workbook.worksheets[0].shapes
shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT1, "Aspose", "Arial", 30, False, False, 0, 0, 0, 0, 100, 200)
textEffectFormat = shapes[0].text_effect
textEffectFormat.set_text_effect(MsoPresetTextEffect.TEXT_EFFECT10)
workbook.save("Book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
