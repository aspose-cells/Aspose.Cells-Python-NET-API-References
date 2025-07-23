---
title: PdfBookmarkEntry klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells.rendering/pdfbookmarkentry/
is_root: false
---
##  PdfBookmarkEntry klass
PdfBookmarkEntry är en post i pdf-bokmärket.
om egenskapen Text för den aktuella instansen är null eller "",
Den aktuella instansen kommer att döljas och underordnade filer kommer att infogas på den aktuella nivån.



Typen PdfBookmarkEntry avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/__init__/#) | Skapar en ny instans av PdfBookmarkEntry|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [text](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/text) | Titel på ett bokmärke.|
| [destination](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/destination) |Cellen som bokmärket länkar till.|
| [destination_name](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/destination_name) | Hämtar eller anger namnet på destinationen.|
| [sub_entry](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/sub_entry) | Delpost till ett bokmärke.|
| [is_open](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/is_open) | När den här egenskapen är sann kommer bokmärkesposten att expandera, annars kommer den att kollapsa.|
| [is_collapse](/cells/python-net/sv/aspose.cells.rendering/pdfbookmarkentry/is_collapse) | När den här egenskapen är sann kommer bokmärkesposten att kollapsa, annars kommer den att expandera.|



###  Exempel

```python
from aspose.cells import PdfSaveOptions, Workbook
from aspose.cells.rendering import PdfBookmarkEntry

workbook = Workbook()
workbook.worksheets.add()
workbook.worksheets.add()
cellInPage1 = workbook.worksheets[0].cells.get("A1")
cellInPage2 = workbook.worksheets[1].cells.get("A1")
cellInPage3 = workbook.worksheets[2].cells.get("A1")
cellInPage1.put_value("page1")
cellInPage2.put_value("page2")
cellInPage3.put_value("page3")
pbeRoot = PdfBookmarkEntry()
pbeRoot.text = "root"
pbeRoot.destination = cellInPage1
pbeRoot.sub_entry = []
pbeRoot.is_open = False
subPbe1 = PdfBookmarkEntry()
subPbe1.text = "section1"
subPbe1.destination = cellInPage2
subPbe2 = PdfBookmarkEntry()
subPbe2.text = "section2"
subPbe2.destination = cellInPage3
pbeRoot.sub_entry.append(subPbe1)
pbeRoot.sub_entry.append(subPbe2)
saveOptions = PdfSaveOptions()
saveOptions.bookmark = pbeRoot
workbook.save("output_bookmark.pdf", saveOptions)

```

###  Se även
* modul [`aspose.cells.rendering`](..)
