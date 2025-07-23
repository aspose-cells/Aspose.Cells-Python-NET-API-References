---
title: Metodo change_palette
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 50
url: /it/aspose.cells/workbook/change_palette/
is_root: false
---
##  change_palette(self, color, index) {#aspose.pydrawing.Color-int}
Cambia la tavolozza del foglio di calcolo nell'indice specificato.



```python

def change_palette(self, color, index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| color | aspose.pydrawing.Color | Struttura del colore.|
| index | int | Indice della tavolozza, 0 - 55.|
###  Osservazioni

La tavolozza è composta da 56 voci, ciascuna rappresentata da un valore RGB.


Se si imposta un colore non presente nella tavolozza, l'impostazione non avrà effetto.


Quindi, se vuoi impostare un colore personalizzato, per prima cosa modifica la tavolozza.


Quella che segue è la tavolozza dei colori standard.

| Colore| Rosso| Verde| Blu|
| :- | :- | :- | :- |
| Nero| 0| 0| 0 |
| Bianco| 255| 255| 255 |
| Rosso| 255| 0| 0 |
| Lime| 0| 255| 0 |
| Blu| 0| 0| 255 |
| Giallo| 255| 255| 0 |
| Magenta| 255| 0| 255 |
| Ciano| 0| 255| 255 |
| Marrone| 128| 0| 0 |
| Verde| 0| 128| 0 |
| Marina| 0| 0| 128 |
| Oliva| 128| 128| 0 |
| Viola| 128| 0| 128 |
| Verde acqua| 0| 128| 128 |
| Argento| 192| 192| 192 |
| Grigio| 128| 128| 128 |
|Colore17| 153| 153| 255 |
| Colore18| 153| 51| 102 |
| Colore19| 255| 255| 204 |
| Colore20| 204| 255| 255 |
| Colore21| 102| 0| 102 |
| Colore22| 255| 128| 128 |
| Colore23| 0| 102| 204 |
| Colore24| 204| 204| 255 |
| Colore25| 0| 0| 128 |
| Colore26| 255| 0| 255 |
| Colore27| 255| 255| 0 |
| Colore28| 0| 255| 255 |
| Colore29| 128| 0| 128 |
| Colore30| 128| 0| 0 |
| Colore31| 0| 128| 128 |
| Colore32| 0| 0| 255 |
| Colore33| 0| 204| 255 |
| Colore34| 204| 255| 255 |
| Colore35| 204| 255| 204 |
| Colore36| 255| 255| 153 |
| Colore37| 153| 204| 255 |
| Colore38| 255| 153| 204 |
| Colore39| 204| 153| 255 |
| Colore40| 255| 204| 153 |
| Colore41| 51| 102| 255 |
| Colore42| 51| 204| 204 |
| Colore43| 153| 204| 0 |
| Colore44| 255| 204| 0 |
| Colore45| 255| 153| 0 |
| Colore46| 255| 102| 0 |
| Colore47| 102| 102| 153 |
| Colore48| 150| 150| 150 |
| Colore49| 0| 51| 102 |
| Colore50| 51| 153| 102 |
| Colore51| 0| 51| 0 |
| Colore52| 51| 51| 0 |
| Colore53| 153| 51| 0 |
| Colore54| 153| 51| 102 |
| Colore55| 51| 51| 153 |
| Colore56| 51| 51| 51 |


###  Guarda anche

* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
