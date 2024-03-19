---
title: méthode to_tiff
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff {#io.RawIOBase}
Rendre la feuille de calcul entière sous forme d'image Tiff à diffuser.



```python
def to_tiff(self, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase | le flux de l'image de sortie|


##  to_tiff {#str}
Rendre la feuille de calcul entière sous forme d'image Tiff dans un fichier.



```python
def to_tiff(self, filename):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| filename | str | le nom de fichier de l'image de sortie|

###  Exemple

Le code suivant affiche toutes les pages de la première feuille sur une image Tiff.

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



###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/fr/aspose.cells.rendering/sheetrender)
