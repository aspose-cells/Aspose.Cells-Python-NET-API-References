---
title: set_image_resample Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
 Legt die gewünschte PPI (Pixel pro Zoll)-Qualität für neu abgetastete Bilder und JPEG fest.
 Alle Bilder werden mit der angegebenen Qualitätseinstellung in JPEG konvertiert.
und Bilder, die größer als die angegebene PPI (Pixel pro Zoll) sind, werden neu abgetastet.



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| desired_ppi | int | Gewünschte Pixel pro Zoll. 220 hohe Qualität. 150 Bildschirmqualität. 96 E-Mail-Qualität.|
| jpeg_quality | int | 0 - 100 % JPEG Qualität.|

###  Beispiel

Der folgende Code legt den gewünschten PPI-Wert auf 96 und die JPEG-Qualität auf 80 für Bilder im Ausgabe-PDF fest.

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`PdfSaveOptions`](/cells/python-net/de/aspose.cells/pdfsaveoptions)
