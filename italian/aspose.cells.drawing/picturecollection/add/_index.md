---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) indice oggetto.


```python

def add(self, upper_left_row, upper_left_column, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| stream | io.RawIOBase | Oggetto stream contenente i dati dell'immagine.|

###  Esempio

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(self, upper_left_row, upper_left_column, file_name) {#int-int-str}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) indice oggetto.


```python

def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| file_name | str | Nome del file immagine.|

###  Esempio

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) indice oggetto.


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
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
    pictures.add(1, 1, 5, 5, fs)

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) indice oggetto.


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| lower_right_row | int | Indice della riga inferiore destra|
| lower_right_column | int | Indice della colonna in basso a destra|
| file_name | str | Nome del file immagine.|

###  Esempio

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) indice oggetto.


```python

def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
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
    pictures.add(1, 1, fs, 50, 50)

```


##  add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
Aggiunge un'immagine alla raccolta.


###  ritorna

[`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) indice oggetto.


```python

def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| file_name | str | Nome del file immagine.|
| width_scale | int | Scala della larghezza dell'immagine, in percentuale.|
| height_scale | int | Scala dell'altezza dell'immagine, in percentuale.|

###  Esempio

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture)
* classe [`PictureCollection`](/cells/python-net/it/aspose.cells.drawing/picturecollection)
