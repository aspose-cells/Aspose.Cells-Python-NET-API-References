---
title: méthode to_image
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cells.rendering/sheetrender/to_image/
is_root: false
---
##  to_image {#int-str}
Rendre certaines pages dans un fichier.



```python
def to_image(self, page_index, file_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| page_index | int | indiquer quelle page doit être convertie|
| file_name | str | nom de fichier de l'image de sortie|

###  Exemple

Le code suivant génère la première page de la première feuille sous forme d'image png.

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
Afficher certaines pages dans un flux.



```python
def to_image(self, page_index, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| page_index | int | indiquer quelle page doit être convertie|
| stream | io.RawIOBase | le flux de l'image de sortie|



###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/fr/aspose.cells.rendering/sheetrender)
