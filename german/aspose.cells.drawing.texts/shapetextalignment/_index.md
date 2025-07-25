---
title: ShapeTextAlignment Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment Klasse
Stellt die Einstellung der Textausrichtung der Form dar;



Der Typ ShapeTextAlignment macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_text_wrapped](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | Ruft den Textumbruchtyp der Form ab, die Text enthält, oder legt diesen fest.|
| [rotate_text_with_shape](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | Gibt an, ob Text mit Form gedreht wird.|
| [text_vertical_overflow](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | Ruft den vertikalen Textüberlauftyp des Textfelds ab und legt ihn fest.|
| [text_horizontal_overflow](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | Ruft den horizontalen Textüberlauftyp des Textfelds ab und legt ihn fest.|
| [rotation_angle](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | Ruft die Drehung der Form ab und legt sie fest.|
| [text_vertical_type](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | Ruft die Textrichtung ab und legt sie fest.|
| [is_locked_text](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | Gibt an, ob die Form gesperrt ist, wenn das Arbeitsblatt geschützt ist.|
| [auto_size](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/auto_size) | Gibt an, ob die Größe der Form automatisch entsprechend ihrem Inhalt angepasst wird.|
| [text_shape_type](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | Ruft den Transformationstyp des Textes ab und legt ihn fest.|
| [top_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | Gibt den oberen Rand in der Einheit Punkte zurück|
| [bottom_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | Gibt den unteren Rand in der Einheit Punkte zurück|
| [left_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | Gibt den linken Rand in der Einheit Punkte zurück|
| [right_margin_pt](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | Gibt den rechten Rand in der Einheit Punkte zurück|
| [is_auto_margin](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |Gibt an, ob der Rand des Textrahmens automatisch ist.|
| [number_of_columns](/cells/python-net/de/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | Ruft die Anzahl der Textspalten im umgebenden Rechteck ab und legt sie fest.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  Siehe auch
* Modul [`aspose.cells.drawing.texts`](..)
