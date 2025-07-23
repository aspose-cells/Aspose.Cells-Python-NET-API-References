---
title: Comment klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 260
url: /sv/aspose.cells/comment/
is_root: false
---
##  Comment klass
Inkapslar objektet som representerar en cellkommentar.



Typen Comment avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [author](/cells/python-net/sv/aspose.cells/comment/author) | Hämtar och anger namnet på den ursprungliga kommentarens författare|
| [comment_shape](/cells/python-net/sv/aspose.cells/comment/comment_shape) | Hämta ett Shape-objekt som representerar den form som är kopplad till den angivna kommentaren.|
| [row](/cells/python-net/sv/aspose.cells/comment/row) | Hämtar radindexet för kommentaren.|
| [column](/cells/python-net/sv/aspose.cells/comment/column) | Hämtar kolumnindexet för kommentaren.|
| [is_threaded_comment](/cells/python-net/sv/aspose.cells/comment/is_threaded_comment) | Anger om den här kommentaren är en trådad kommentar.|
| [threaded_comments](/cells/python-net/sv/aspose.cells/comment/threaded_comments) | Hämtar listan över trådade kommentarer;|
| [note](/cells/python-net/sv/aspose.cells/comment/note) | Representerar innehållet i kommentaren.|
| [html_note](/cells/python-net/sv/aspose.cells/comment/html_note) | Hämtar och anger html-strängen som innehåller data och vissa format i den här kommentaren.|
| [font](/cells/python-net/sv/aspose.cells/comment/font) | Hämtar teckensnittet för kommentaren.|
| [is_visible](/cells/python-net/sv/aspose.cells/comment/is_visible) | Representerar om kommentaren är synlig eller inte.|
| [text_orientation_type](/cells/python-net/sv/aspose.cells/comment/text_orientation_type) | Hämtar och anger textorienteringstypen för kommentaren.|
| [text_horizontal_alignment](/cells/python-net/sv/aspose.cells/comment/text_horizontal_alignment) | Hämtar och anger textens horisontella justeringstyp för kommentaren.|
| [text_vertical_alignment](/cells/python-net/sv/aspose.cells/comment/text_vertical_alignment) | Hämtar och anger textens vertikala justeringstyp för kommentaren.|
| [auto_size](/cells/python-net/sv/aspose.cells/comment/auto_size) | Anger om kommentarens storlek justeras automatiskt enligt dess innehåll.<br/>Obs: I vissa specialfall (t.ex. i Mac-miljö) kanske den här inställningen inte träder i kraft. Om inställningen inte träder i kraft, ersätt den med FitToTextSize().|
| [height_cm](/cells/python-net/sv/aspose.cells/comment/height_cm) | Representerar kommentarens höjd, i centimeter.|
| [width_cm](/cells/python-net/sv/aspose.cells/comment/width_cm) | Representerar kommentarens bredd, i centimeter.|
| [width](/cells/python-net/sv/aspose.cells/comment/width) | Representerar kommentarens bredd, i pixlar.|
| [height](/cells/python-net/sv/aspose.cells/comment/height) | Representerar kommentarens höjd, i pixlar.|
| [width_inch](/cells/python-net/sv/aspose.cells/comment/width_inch) | Representerar kommentarens bredd, i tum.|
| [height_inch](/cells/python-net/sv/aspose.cells/comment/height_inch) | Representerar kommentarens höjd, i tum.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/sv/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Formatera vissa tecken med teckensnittsinställningen.|
| [`characters(self, start_index, length)`](/cells/python-net/sv/aspose.cells/comment/characters/#int-int) | Returnerar ett Characters-objekt som representerar ett teckenintervall i kommentartexten.|
| [`get_characters(self)`](/cells/python-net/sv/aspose.cells/comment/get_characters/#) | Returnerar alla Characters-objekt<br/> som representerar ett teckenintervall i kommentarstexten.|
| [`get_rich_formattings(self)`](/cells/python-net/sv/aspose.cells/comment/get_rich_formattings/#) | Returnerar alla Characters-objekt<br/> som representerar ett teckenintervall i kommentarstexten.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
