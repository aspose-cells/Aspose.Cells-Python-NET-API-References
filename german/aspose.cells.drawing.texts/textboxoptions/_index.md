---
title: TextBoxOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions Klasse
Stellt die Textoptionen der Form dar



Der Typ TextBoxOptions macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Es entspricht „Form formatieren – Textoptionen – Textfeld – Vertikale Ausrichtung“ in Excel.|
| [resize_to_fit_text](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Gibt an, ob die Größe der Form an den Text angepasst werden soll|
| [shape_text_direction](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Ruft die Textanzeigerichtung innerhalb eines bestimmten Textkörpers ab oder legt sie fest.<br/> Es entspricht "Form formatieren - Textoptionen - Textfeld - Textrichtung" in Excel|
| [left_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Ruft den linken Rand in der Einheit „Punkte“ ab und legt ihn fest.|
| [right_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Ruft den rechten Rand in der Einheit „Punkte“ ab und legt ihn fest.|
| [top_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Ruft den oberen Rand in der Einheit „Punkte“ ab und legt ihn fest.|
| [bottom_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Gibt den unteren Rand in der Einheit Punkte zurück|
| [allow_text_to_overflow](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Ob Text über die Form hinauslaufen darf.|
| [wrap_text_in_shape](/cells/python-net/de/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Gibt den Textumbruch innerhalb einer Form an.<br/> Falsch: Im Textkörper erfolgt kein Umbruch.<br/>True – Der Textkörper wird umbrochen.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing.texts`](..)
