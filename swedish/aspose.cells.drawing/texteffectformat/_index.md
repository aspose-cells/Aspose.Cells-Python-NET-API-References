---
title: TextEffectFormat klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 680
url: /sv/aspose.cells.drawing/texteffectformat/
is_root: false
---
##  TextEffectFormat klass
Innehåller egenskaper och metoder som gäller för WordArt-objekt.



Typen TextEffectFormat avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [text](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/text) | Texten i WordArt-filen.|
| [font_name](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/font_name) | Namnet på teckensnittet som används i WordArt-objektet.|
| [font_bold](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/font_bold) | Anger om teckensnittet är fetstilt.|
| [font_italic](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/font_italic) | Anger om teckensnittet är kursivt.|
| [rotated_chars](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/rotated_chars) | Om värdet är sant roteras tecken i det angivna WordArt-objektet 90 grader i förhållande till WordArt-objektets avgränsande form.|
| [font_size](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/font_size) | Storleken (i punkter) på teckensnittet som används i WordArt-objektet.|
| [preset_shape](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/preset_shape) | Hämtar och anger den förinställda formtypen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_text_effect(self, effect)`](/cells/python-net/sv/aspose.cells.drawing/texteffectformat/set_text_effect/#aspose.cells.drawing.msopresettexteffect) | Ställer in den förinställda texteffekten.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing`](..)
