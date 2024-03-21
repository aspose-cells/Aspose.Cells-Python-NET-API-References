---
title: Metodo to_image
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 50
url: /it/aspose.cells.rendering/sheetrender/to_image/
is_root: false
---
##  to_image {#int-str}
Renderizza una determinata pagina in un file.



```python
def to_image(self, page_index, file_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| page_index | int | indicare quale pagina deve essere convertita|
| file_name | str | nome file dell'immagine di output|

###  Esempio

Il codice seguente restituisce la prima pagina del primo foglio come immagine PNG.

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
Visualizza una determinata pagina in uno stream.



```python
def to_image(self, page_index, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| page_index | int | indicare quale pagina deve essere convertita|
| stream | io.RawIOBase | il flusso dell'immagine di output|



###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/it/aspose.cells.rendering/sheetrender)
