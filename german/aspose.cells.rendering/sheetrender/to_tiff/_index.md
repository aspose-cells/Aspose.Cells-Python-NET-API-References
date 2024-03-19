---
title: to_tiff Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff {#io.RawIOBase}
Rendern Sie das gesamte Arbeitsblatt als TIFF-Bild zum Streamen.



```python
def to_tiff(self, stream):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase | der Stream des Ausgabebildes|


##  to_tiff {#str}
Rendern Sie das gesamte Arbeitsblatt als TIFF-Bild in eine Datei.



```python
def to_tiff(self, filename):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| filename | str | der Dateiname des Ausgabebildes|

###  Beispiel

Der folgende Code gibt alle Seiten des ersten Blatts als TIFF-Bild aus.

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



###  Siehe auch
* Modul [`aspose.cells.rendering`](../../)
* Klasse [`SheetRender`](/cells/python-net/de/aspose.cells.rendering/sheetrender)
