---
title: Comment Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 260
url: /de/aspose.cells/comment/
is_root: false
---
##  Comment Klasse
Kapselt das Objekt, das einen Zellenkommentar darstellt.



Der Typ Comment macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [author](/cells/python-net/de/aspose.cells/comment/author) | Ruft den Namen des ursprünglichen Kommentarautors ab und legt ihn fest.|
| [comment_shape](/cells/python-net/de/aspose.cells/comment/comment_shape) | Rufen Sie ein Shape-Objekt ab, das die Form darstellt, die dem angegebenen Kommentar zugeordnet ist.|
| [row](/cells/python-net/de/aspose.cells/comment/row) | Ruft den Zeilenindex des Kommentars ab.|
| [column](/cells/python-net/de/aspose.cells/comment/column) | Ruft den Spaltenindex des Kommentars ab.|
| [is_threaded_comment](/cells/python-net/de/aspose.cells/comment/is_threaded_comment) | Gibt an, ob es sich bei diesem Kommentar um einen Threadkommentar handelt.|
| [threaded_comments](/cells/python-net/de/aspose.cells/comment/threaded_comments) | Ruft die Liste der Thread-Kommentare ab;|
| [note](/cells/python-net/de/aspose.cells/comment/note) | Stellt den Inhalt des Kommentars dar.|
| [html_note](/cells/python-net/de/aspose.cells/comment/html_note) | Ruft die HTML-Zeichenfolge ab und legt sie fest, die Daten und einige Formate in diesem Kommentar enthält.|
| [font](/cells/python-net/de/aspose.cells/comment/font) | Ruft die Schriftart des Kommentars ab.|
| [is_visible](/cells/python-net/de/aspose.cells/comment/is_visible) | Gibt an, ob der Kommentar sichtbar ist oder nicht.|
| [text_orientation_type](/cells/python-net/de/aspose.cells/comment/text_orientation_type) | Ruft den Textausrichtungstyp des Kommentars ab und legt ihn fest.|
| [text_horizontal_alignment](/cells/python-net/de/aspose.cells/comment/text_horizontal_alignment) | Ruft den horizontalen Textausrichtungstyp des Kommentars ab und legt ihn fest.|
| [text_vertical_alignment](/cells/python-net/de/aspose.cells/comment/text_vertical_alignment) | Ruft den Typ der vertikalen Textausrichtung des Kommentars ab und legt ihn fest.|
| [auto_size](/cells/python-net/de/aspose.cells/comment/auto_size) | Gibt an, ob die Größe des Kommentars automatisch an seinen Inhalt angepasst wird.<br/>Hinweis: In einigen Sonderfällen (z. B. in Mac-Umgebungen) ist diese Einstellung möglicherweise nicht wirksam. Falls diese Einstellung nicht wirksam ist, ersetzen Sie sie bitte durch FitToTextSize().|
| [height_cm](/cells/python-net/de/aspose.cells/comment/height_cm) | Stellt die Höhe des Kommentars in Zentimetern dar.|
| [width_cm](/cells/python-net/de/aspose.cells/comment/width_cm) | Stellt die Breite des Kommentars in Zentimetern dar.|
| [width](/cells/python-net/de/aspose.cells/comment/width) | Stellt die Breite des Kommentars in Pixeln dar.|
| [height](/cells/python-net/de/aspose.cells/comment/height) | Stellt die Höhe des Kommentars in Pixeln dar.|
| [width_inch](/cells/python-net/de/aspose.cells/comment/width_inch) | Stellt die Breite des Kommentars in Zoll dar.|
| [height_inch](/cells/python-net/de/aspose.cells/comment/height_inch) | Stellt die Höhe des Kommentars in Zoll dar.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/de/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Formatieren Sie einige Zeichen mit der Schriftarteinstellung.|
| [`characters(self, start_index, length)`](/cells/python-net/de/aspose.cells/comment/characters/#int-int) | Gibt ein Zeichenobjekt zurück, das einen Zeichenbereich innerhalb des Kommentartextes darstellt.|
| [`get_characters(self)`](/cells/python-net/de/aspose.cells/comment/get_characters/#) | Gibt alle Characters-Objekte zurück<br/> das einen Zeichenbereich innerhalb des Kommentartextes darstellt.|
| [`get_rich_formattings(self)`](/cells/python-net/de/aspose.cells/comment/get_rich_formattings/#) | Gibt alle Characters-Objekte zurück<br/> das einen Zeichenbereich innerhalb des Kommentartextes darstellt.|



###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
