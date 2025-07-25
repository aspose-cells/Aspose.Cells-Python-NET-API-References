---
title: ShapeTextAlignment klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment klass
Representerar inställningen för formens textjustering;



Typen ShapeTextAlignment avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_text_wrapped](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | Hämtar eller anger textomslagstypen för formen som innehåller text.|
| [rotate_text_with_shape](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | Anger om text med form ska roteras.|
| [text_vertical_overflow](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | Hämtar och anger textrutans vertikala överflödestyp.|
| [text_horizontal_overflow](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | Hämtar och anger textrutans horisontella överflödestyp.|
| [rotation_angle](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | Hämtar och ställer in rotationen av formen.|
| [text_vertical_type](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | Hämtar och anger textriktningen.|
| [is_locked_text](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | Anger om formen är låst när kalkylbladet är skyddat.|
| [auto_size](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/auto_size) | Anger om formens storlek justeras automatiskt enligt dess innehåll.|
| [text_shape_type](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | Hämtar och anger transformeringstypen för text.|
| [top_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | Returnerar den övre marginalen i enheten poäng|
| [bottom_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | Returnerar den nedre marginalen i enheten poäng|
| [left_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | Returnerar vänstermarginalen i enheten poäng|
| [right_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | Returnerar högermarginalen i enheten poäng|
| [is_auto_margin](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |Anger om marginalen för textramen är automatisk.|
| [number_of_columns](/cells/python-net/sv/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | Hämtar och anger antalet textkolumner i den avgränsande rektangeln.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  Se även
* modul [`aspose.cells.drawing.texts`](..)
