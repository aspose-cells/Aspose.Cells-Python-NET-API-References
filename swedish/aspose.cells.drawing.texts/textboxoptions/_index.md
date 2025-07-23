---
title: TextBoxOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions klass
Representerar textalternativen för formen



Typen TextBoxOptions avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Det motsvarar "Formatera figur - Textalternativ - Textruta - Vertikal justering" i Excel.|
| [resize_to_fit_text](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Anger om formen ska ändras så att den passar texten|
| [shape_text_direction](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Hämtar eller anger textens visningsriktning inom en given text.<br/> Det motsvarar "Formatera figur - Textalternativ - Textruta - Textriktning" i Excel.|
| [left_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Hämtar och ställer in vänstermarginalen i enheten poäng.|
| [right_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Hämtar och ställer in högermarginalen i enheten poäng.|
| [top_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Hämtar och ställer in den övre marginalen i enheten poäng.|
| [bottom_margin_pt](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Returnerar den nedre marginalen i enheten poäng|
| [allow_text_to_overflow](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Om texten får överflöda formen.|
| [wrap_text_in_shape](/cells/python-net/sv/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Anger textbrytning inom en form.<br/> Falskt - Ingen radbrytning sker på textens brödtext.<br/>Sant - Radbrytning kommer att ske på textens brödtext.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Se även
* modul [`aspose.cells.drawing.texts`](..)
