---
title: Metodo to_tiff
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff(self, stream) {#io.RawIOBase}
Esegui il rendering dell'intero foglio di lavoro come immagine Tiff per lo streaming.



```python

def to_tiff(self, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | il flusso dell'immagine di output|


##  to_tiff(self, filename) {#str}
Trasforma l'intero foglio di lavoro in un file immagine Tiff.



```python

def to_tiff(self, filename):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| filename | str | il nome del file dell'immagine di output|

###  Esempio

Il codice seguente restituisce tutte le pagine del primo foglio in un'immagine Tiff.

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



###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/it/aspose.cells.rendering/sheetrender)
