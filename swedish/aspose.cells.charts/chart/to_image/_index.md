---
title: to_image metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 140
url: /sv/aspose.cells.charts/chart/to_image/
is_root: false
---
##  to_image(self, image_file) {#str}
Skapar diagrambilden och sparar den till en fil.
Filnamnstillägget avgör bildens format.



```python

def to_image(self, image_file):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| image_file | str | Bildfilens namn med fullständig sökväg.|
###  Anmärkningar

Bildens format anges med hjälp av filnamnets tillägg.
Om du till exempel anger "minfil.png" sparas bilden
 i formatet PNG. Följande filändelser känns igen:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.

##  to_image(self, image_file, image_type) {#str-aspose.cells.drawing.ImageType}
Skapar diagrambilden och sparar den till en fil med den angivna bildtypen.



```python

def to_image(self, image_file, image_type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| image_file | str | Bildfilens namn med fullständig sökväg.|
| image_type | aspose.cells.drawing.ImageType | Bildtypen som bilden ska sparas i.|
###  Anmärkningar

Bildtypen anges med hjälp av `imageType`.
 Följande typer stöds:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.

##  to_image(self, image_file, jpeg_quality) {#str-int}
Skapar diagrambilden och sparar den till en fil i JPEG-format.



```python

def to_image(self, image_file, jpeg_quality):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| image_file | str | Bildfilens namn med fullständig sökväg.|
| jpeg_quality | int | Jpeg-kvalitet.|
###  Anmärkningar

Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.
 OBS! Den här metoden är nu föråldrad. Istället,
Använd metoden ToImage(string,ImageOrPrintOptions) med angiven kvalitet.
 Denna metod kommer att tas bort 12 månader senare från och med mars 2025.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  to_image(self, stream, jpeg_quality) {#io.RawIOBase-int}
Skapar diagrambilden och sparar den till en ström i JPEG-format.



```python

def to_image(self, stream, jpeg_quality):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | Utgångsströmmen.|
| jpeg_quality | int | Jpeg-kvalitet.|
###  Anmärkningar

Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.

##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}

Skapar diagrambilden och sparar den till en ström i det angivna formatet.



```python

def to_image(self, stream, image_type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | Utgångsströmmen.|
| image_type | aspose.cells.drawing.ImageType | Bildtypen som bilden ska sparas i.|
###  Anmärkningar

Bildtypen anges med hjälp av `imageType`.
 Följande typer stöds:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.

##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
Skapar diagrambilden och sparar den till en fil.
Filnamnstillägget avgör bildens format.



```python

def to_image(self, image_file, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| image_file | str | Bildfilens namn med fullständig sökväg.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Ytterligare alternativ för att skapa bilder|
###  Anmärkningar

Bildens format anges med hjälp av filnamnets tillägg.
Om du till exempel anger "minfil.png" sparas bilden
 i formatet PNG. Följande filändelser känns igen:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.
 Vänligen hänvisa till[Lista över diagram som stöds](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) för mer information.
###  Exempel

Sparar till Tiff med 300 dpi och CCITT4-komprimering.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, TiffCompression

options = ImageOrPrintOptions()
options.horizontal_resolution = 300
options.vertical_resolution = 300
options.tiff_compression = TiffCompression.COMPRESSION_CCITT4
book = Workbook(r"test.xls")
book.worksheets[0].charts[0].to_image(r"chart.Tiff", options)

```


Sparar som JPEG med 300 dpi och 80 bildkvalitet.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions

options = ImageOrPrintOptions()
options.horizontal_resolution = 300
options.vertical_resolution = 300
options.quality = 80
book = Workbook(r"test.xls")
book.worksheets[0].charts[0].to_image(r"chart.Jpeg", options)

```


##  to_image(self, stream, options) {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Skapar diagrambilden och sparar den till en ström i det angivna formatet.



```python

def to_image(self, stream, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | Utgångsströmmen.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Ytterligare alternativ för att skapa bilder|
###  Anmärkningar

Bildtypen anges med hjälp av `options.ImageType`.
 Följande format stöds:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Om bredden eller höjden är noll eller om diagrammet inte stöds enligt listan över diagram som stöds, kommer den här metoden inte att göra någonting.
 Vänligen hänvisa till[Lista över diagram som stöds](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) för mer information.


###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`Chart`](/cells/python-net/sv/aspose.cells.charts/chart)
