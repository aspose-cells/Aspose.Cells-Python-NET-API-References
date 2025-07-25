---
title: PdfBookmarkEntry صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells.rendering/pdfbookmarkentry/
is_root: false
---
##  PdfBookmarkEntry صف
PdfBookmarkEntry هو إدخال في إشارة مرجعية لملف pdf.
إذا كانت خاصية النص للمثيل الحالي فارغة أو ""،
سيتم إخفاء المثيل الحالي وسيتم إدراج الأبناء على المستوى الحالي.



يكشف النوع PdfBookmarkEntry عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/__init__/#) | إنشاء مثيل جديد لـ PdfBookmarkEntry|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [text](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/text) | عنوان الإشارة المرجعية.|
| [destination](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/destination) |الخلية التي يرتبط بها الإشارة المرجعية.|
| [destination_name](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/destination_name) | يحصل على اسم الوجهة أو يحدده.|
| [sub_entry](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/sub_entry) | إدخال فرعي للإشارة المرجعية.|
| [is_open](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/is_open) | عندما تكون هذه الخاصية صحيحة، سيتم توسيع إدخال العلامة المرجعية، وإلا فسوف ينهار.|
| [is_collapse](/cells/python-net/ar/aspose.cells.rendering/pdfbookmarkentry/is_collapse) | عندما تكون هذه الخاصية صحيحة، سوف ينهار إدخال العلامة المرجعية، وإلا فسوف يتوسع.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](..)
