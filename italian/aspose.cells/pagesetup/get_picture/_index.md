---
title: Metodo get_picture
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 120
url: /it/aspose.cells/pagesetup/get_picture/
is_root: false
---
##  get_picture(self, is_header, section) {#bool-int}
Ottiene l'oggetto [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) dell'intestazione/piè di pagina.


###  ritorna

Restituisce l'oggetto [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture).
Restituisce null se non è presente alcuna immagine.


```python

def get_picture(self, is_header, section):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| is_header | bool | Indica se si trova nell'intestazione o nel piè di pagina.|
| section | int |0: Sezione sinistra, 1: Sezione centrale, 2: Sezione destra.|


##  get_picture(self, is_first, is_even, is_header, section) {#bool-bool-bool-int}
Ottiene l'oggetto [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) dell'intestazione/piè di pagina.


###  ritorna

Restituisce l'oggetto [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture).


```python

def get_picture(self, is_first, is_even, is_header, section):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| is_first | bool | Indica se ottenere l'immagine dell'intestazione/piè di pagina della prima pagina.|
| is_even | bool | Indica se si desidera visualizzare anche l'intestazione/piè di pagina della pagina.|
| is_header | bool | Indica se si desidera ottenere l'immagine dell'intestazione/piè di pagina.|
| section | int |0: Sezione sinistra, 1: Sezione centrale, 2: Sezione destra.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`PageSetup`](/cells/python-net/it/aspose.cells/pagesetup)
* classe [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture)
