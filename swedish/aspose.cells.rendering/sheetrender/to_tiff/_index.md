---
title: to_tiff metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff(self, stream) {#io.RawIOBase}
Rendera hela kalkylbladet som en Tiff-bild för att strömma.



```python

def to_tiff(self, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | strömmen av utdatabilden|


##  to_tiff(self, filename) {#str}
Rendera hela kalkylbladet som en Tiff-bild till en fil.



```python

def to_tiff(self, filename):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| filename | str | filnamnet på utdatabilden|

###  Exempel

Följande kod matar ut alla sidor i det första arket till en TIFF-bild.

```python
from aspose.cells import SaveFormat, Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

# load the source file with images.
wb = Workbook("Book1.xlsx")
imgOpt = ImageOrPrintOptions()
# set output image type.
imgOpt.save_format = SaveFormat.TIFF
# render the first sheet.
sr = SheetRender(wb.worksheets[0], imgOpt)
# output all the pages of the sheet to Tiff image.
sr.to_tiff("output.tiff")

```



###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`SheetRender`](/cells/python-net/sv/aspose.cells.rendering/sheetrender)
