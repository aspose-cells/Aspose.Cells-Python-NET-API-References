---
title: Metodo set_image_resample
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
 Imposta i PPI (pixel per pollice) desiderati delle immagini ricampionate e la qualità jpeg.
 Tutte le immagini verranno convertite in JPEG con l'impostazione di qualità specificata,
e le immagini che hanno un numero di PPI (pixel per pollice) maggiore di quello specificato verranno ricampionate.



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| desired_ppi | int | Pixel per pollice desiderati. 220 alta qualità. 150 qualità schermo. 96 qualità e-mail.|
| jpeg_quality | int | 0 - 100% JPEG qualità.|

###  Esempio

Il seguente codice imposta il PPI desiderato su 96 e la qualità JPEG su 80 per le immagini nel PDF di output.

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`PdfSaveOptions`](/cells/python-net/it/aspose.cells/pdfsaveoptions)
