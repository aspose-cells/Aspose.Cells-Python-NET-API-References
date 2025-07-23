---
title: Metodo add_picture
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 230
url: /it/aspose.cells.drawing/shapecollection/add_picture/
is_root: false
---
##  add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) Oggetto immagine.


```python

def add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| lower_right_row | int | Indice della riga inferiore destra|
| lower_right_column | int | Indice della colonna in basso a destra|
| stream | io.RawIOBase | Oggetto stream contenente i dati dell'immagine.|

###  Esempio

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 0, 1, 0, fs)

```


##  add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) Oggetto immagine.


```python

def add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| stream | io.RawIOBase | Oggetto stream contenente i dati dell'immagine.|
| width_scale | int | Scala della larghezza dell'immagine, in percentuale.|
| height_scale | int | Scala dell'altezza dell'immagine, in percentuale.|

###  Esempio

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 1, fs, 50, 60)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
