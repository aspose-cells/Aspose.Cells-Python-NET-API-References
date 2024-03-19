---
title: to_image Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 50
url: /de/aspose.cells.rendering/sheetrender/to_image/
is_root: false
---
##  to_image {#int-str}
Rendern Sie eine bestimmte Seite in eine Datei.



```python
def to_image(self, page_index, file_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| page_index | int | Geben Sie an, welche Seite konvertiert werden soll|
| file_name | str | Dateiname des Ausgabebildes|

###  Beispiel

Der folgende Code gibt die erste Seite des ersten Blatts als PNG-Bild aus.

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

# load the source file with images.
wb = Workbook("Book1.xlsx")
imgOpt = ImageOrPrintOptions()
# set output image type.
imgOpt.image_type = ImageType.PNG
# render the first sheet.
sr = SheetRender(wb.worksheets[0], imgOpt)
# output the first page of the sheet to image.
sr.to_image(0, "output.png")

```


##  to_image {#int-io.RawIOBase}
Rendern Sie eine bestimmte Seite in einen Stream.



```python
def to_image(self, page_index, stream):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| page_index | int | Geben Sie an, welche Seite konvertiert werden soll|
| stream | io.RawIOBase | der Stream des Ausgabebildes|



###  Siehe auch
* Modul [`aspose.cells.rendering`](../../)
* Klasse [`SheetRender`](/cells/python-net/de/aspose.cells.rendering/sheetrender)
