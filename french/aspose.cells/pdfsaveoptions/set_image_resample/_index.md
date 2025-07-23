---
title: méthode set_image_resample
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
 Définit le PPI (pixels par pouce) souhaité des images de rééchantillonnage et la qualité jpeg.
 Toutes les images seront converties en JPEG avec le paramètre de qualité spécifié,
et les images supérieures au PPI (pixels par pouce) spécifié seront rééchantillonnées.



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| desired_ppi | int | Pixels souhaités par pouce. 220 haute qualité. 150 qualité d'écran. 96 qualité de courrier électronique.|
| jpeg_quality | int | 0 - 100% JPEG qualité.|

###  Exemple

Le code suivant définit le PPI souhaité sur 96 et la qualité jpeg sur 80 pour les images dans le PDF de sortie.

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



###  Voir également
* module [`aspose.cells`](../../)
* classe [`PdfSaveOptions`](/cells/python-net/fr/aspose.cells/pdfsaveoptions)
