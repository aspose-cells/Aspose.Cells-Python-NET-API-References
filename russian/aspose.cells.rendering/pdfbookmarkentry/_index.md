---
title: PdfBookmarkEntry класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells.rendering/pdfbookmarkentry/
is_root: false
---
##  PdfBookmarkEntry класс
PdfBookmarkEntry — это запись в закладке PDF.
если свойство Text текущего экземпляра равно null или "",
текущий экземпляр будет скрыт, а дочерние элементы будут вставлены на текущий уровень.



Тип PdfBookmarkEntry предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/__init__/#) | Создает новый экземпляр PdfBookmarkEntry|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [text](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/text) | Название закладки.|
| [destination](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/destination) |Ячейка, на которую ссылается закладка.|
| [destination_name](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/destination_name) | Получает или задает имя пункта назначения.|
| [sub_entry](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/sub_entry) | Подзапись закладки.|
| [is_open](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/is_open) | Если это свойство истинно, закладка будет расширяться, в противном случае она свернется.|
| [is_collapse](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry/is_collapse) | Если это свойство истинно, закладка будет свернута, в противном случае она будет расширена.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells.rendering`](..)
