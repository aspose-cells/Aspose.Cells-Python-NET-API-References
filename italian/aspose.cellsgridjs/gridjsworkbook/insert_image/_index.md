---
title: Metodo insert_image
second_title: Aspose.Cells.GridJs for Python via .NET API Referenze
description:
type: docs
weight: 130
url: /it/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

Inserisce l'immagine nel foglio di lavoro dal flusso di file o dall'URL (deve essere fornito il flusso di file o l'URL)
 O
Inserisce la forma, quando p.type è uno di AutoShapeType


###  ritorna


La stringa di formato JSON dell'immagine inserita


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| uid | str | L'ID univoco per la cache dei file|
| p | str | La stringa di formato JSON per l'operazione che specifica la posizione della cella, il nome del foglio di lavoro, la riga in alto a sinistra, la colonna in alto a sinistra per l'immagine, ecc. {nome:'foglio1',ri:1,ci:1} |
| s | io.RawIOBase | Il flusso di file del file di immagine|
| image_url | str | L'URL del file immagine|



###  Guarda anche
* modulo [`aspose.cellsgridjs`](../../)
* classe [`GridJsWorkbook`](/cells/python-net/it/aspose.cellsgridjs/gridjsworkbook)
