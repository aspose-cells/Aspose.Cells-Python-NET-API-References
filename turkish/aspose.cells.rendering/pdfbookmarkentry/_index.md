---
title: PdfBookmarkEntry sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells.rendering/pdfbookmarkentry/
is_root: false
---
##  PdfBookmarkEntry sınıfı
PdfBookmarkEntry pdf yer iminde bir girdidir.
geçerli örneğin Metin özelliği null veya "" ise,
geçerli örnek gizlenecek ve çocuklar geçerli düzeye eklenecek.



PdfBookmarkEntry türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/__init__/#) | PdfBookmarkEntry'nin yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [text](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/text) | Bir yer iminin başlığı.|
| [destination](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/destination) |Yer iminin bağlantı yaptığı hücre.|
| [destination_name](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/destination_name) | Hedefin adını alır veya ayarlar.|
| [sub_entry](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/sub_entry) | Bir yer iminin alt girişi.|
| [is_open](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/is_open) | Bu özellik doğru olduğunda yer imleri kenti genişleyecek, aksi takdirde daralacaktır.|
| [is_collapse](/cells/python-net/tr/aspose.cells.rendering/pdfbookmarkentry/is_collapse) | Bu özellik doğru olduğunda yer imleri kenti çöker, aksi takdirde genişler.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](..)
