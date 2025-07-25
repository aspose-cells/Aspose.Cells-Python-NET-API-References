---
title: Metodo to_image
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 140
url: /it/aspose.cells.charts/chart/to_image/
is_root: false
---
##  to_image(self, image_file) {#str}
Crea l'immagine del grafico e la salva in un file.
L'estensione del nome del file determina il formato dell'immagine.



```python

def to_image(self, image_file):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| image_file | str | Nome del file immagine con percorso completo.|
###  Osservazioni

Il formato dell'immagine viene specificato utilizzando l'estensione del nome del file.
Ad esempio, se specifichi "myfile.png", l'immagine verrà salvata
 nel formato PNG. Sono riconosciute le seguenti estensioni di file:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.

##  to_image(self, image_file, image_type) {#str-aspose.cells.drawing.ImageType}
Crea l'immagine del grafico e la salva in un file nel tipo di immagine specificato.



```python

def to_image(self, image_file, image_type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| image_file | str | Nome del file immagine con percorso completo.|
| image_type | aspose.cells.drawing.ImageType | Tipo di immagine in cui salvare l'immagine.|
###  Osservazioni

Il tipo di immagine viene specificato utilizzando `imageType`.
 Sono supportati i seguenti tipi:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.

##  to_image(self, image_file, jpeg_quality) {#str-int}
Crea l'immagine del grafico e la salva in un file in formato Jpeg.



```python

def to_image(self, image_file, jpeg_quality):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| image_file | str | Nome del file immagine con percorso completo.|
| jpeg_quality | int | Qualità JPEG.|
###  Osservazioni

Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.
 NOTA: questo metodo è ormai obsoleto. Invece,
si prega di utilizzare il metodo ToImage(string,ImageOrPrintOptions) con la qualità specificata.
 Questo metodo verrà rimosso 12 mesi dopo, a partire da marzo 2025.
Aspose si scusa per ogni eventuale disagio arrecato.

##  to_image(self, stream, jpeg_quality) {#io.RawIOBase-int}
Crea l'immagine del grafico e la salva in un flusso in formato Jpeg.



```python

def to_image(self, stream, jpeg_quality):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il flusso di output.|
| jpeg_quality | int | Qualità JPEG.|
###  Osservazioni

Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.

##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}

Crea l'immagine del grafico e la salva in un flusso nel formato specificato.



```python

def to_image(self, stream, image_type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il flusso di output.|
| image_type | aspose.cells.drawing.ImageType | Tipo di immagine in cui salvare l'immagine.|
###  Osservazioni

Il tipo di immagine viene specificato utilizzando `imageType`.
 Sono supportati i seguenti tipi:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.

##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
Crea l'immagine del grafico e la salva in un file.
L'estensione del nome del file determina il formato dell'immagine.



```python

def to_image(self, image_file, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| image_file | str | Nome del file immagine con percorso completo.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Ulteriori opzioni di creazione di immagini|
###  Osservazioni

Il formato dell'immagine viene specificato utilizzando l'estensione del nome del file.
Ad esempio, se specifichi "myfile.png", l'immagine verrà salvata
 nel formato PNG. Sono riconosciute le seguenti estensioni di file:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.
 Fare riferimento a[Elenco dei grafici supportati](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) per maggiori dettagli.
###  Esempio

Salva in Tiff con 300 dpi e compressione CCITT4.

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


Salva in formato JPEG con 300 dpi e qualità dell'immagine 80.

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
Crea l'immagine del grafico e la salva in un flusso nel formato specificato.



```python

def to_image(self, stream, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il flusso di output.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Ulteriori opzioni di creazione di immagini|
###  Osservazioni

Il tipo di immagine viene specificato utilizzando `options.ImageType`.
 Sono supportati i seguenti formati:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Se la larghezza o l'altezza sono pari a zero oppure il grafico non è supportato in base all'elenco dei grafici supportati, questo metodo non farà nulla.
 Fare riferimento a[Elenco dei grafici supportati](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) per maggiori dettagli.


###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`Chart`](/cells/python-net/it/aspose.cells.charts/chart)
