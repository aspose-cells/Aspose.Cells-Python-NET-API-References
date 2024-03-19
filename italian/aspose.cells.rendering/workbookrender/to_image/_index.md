---
title: Metodo to_image
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 50
url: /it/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image {#io.RawIOBase}
Visualizza l'intera cartella di lavoro come immagine Tiff per lo streaming.



```python
def to_image(self, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | il flusso dell'immagine di output|


##  to_image {#str}
Visualizza l'intera cartella di lavoro come immagine Tiff in un file.



```python
def to_image(self, filename):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| filename | str | il nome file dell'immagine di output|


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
* classe [`WorkbookRender`](/cells/python-net/it/aspose.cells.rendering/workbookrender)
