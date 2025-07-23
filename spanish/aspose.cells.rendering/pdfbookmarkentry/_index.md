---
title: PdfBookmarkEntry clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells.rendering/pdfbookmarkentry/
is_root: false
---
##  PdfBookmarkEntry clase
PdfBookmarkEntry es una entrada en el marcador pdf.
si la propiedad Texto de la instancia actual es nula o "",
La instancia actual se ocultará y los elementos secundarios se insertarán en el nivel actual.



El tipo PdfBookmarkEntry expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/__init__/#) | Construye una nueva instancia de PdfBookmarkEntry|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [text](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/text) | Título de un marcador.|
| [destination](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/destination) |La celda a la que se vincula el marcador.|
| [destination_name](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/destination_name) | Obtiene o establece el nombre del destino.|
| [sub_entry](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/sub_entry) | Subentrada de un marcador.|
| [is_open](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/is_open) | Cuando esta propiedad es verdadera, la entrada del marcador se expandirá; de lo contrario, se contraerá.|
| [is_collapse](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry/is_collapse) | Cuando esta propiedad es verdadera, la entrada del marcador se contraerá; de lo contrario, se expandirá.|



###  Ejemplo

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

###  Ver también
* módulo [`aspose.cells.rendering`](..)
