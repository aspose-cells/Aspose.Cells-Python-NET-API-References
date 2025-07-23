---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objektindex.


```python

def add(self, upper_left_row, upper_left_column, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| stream | io.RawIOBase | Strömobjekt som innehåller bilddata.|

###  Exempel

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(self, upper_left_row, upper_left_column, file_name) {#int-int-str}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objektindex.


```python

def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| file_name | str | Bildfilnamn.|

###  Exempel

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objektindex.


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| lower_right_row | int | Index nedre högra raden|
| lower_right_column | int | Index i nedre högra kolumnen|
| stream | io.RawIOBase | Strömobjekt som innehåller bilddata.|

###  Exempel

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, 5, 5, fs)

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objektindex.


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| lower_right_row | int | Index nedre högra raden|
| lower_right_column | int | Index i nedre högra kolumnen|
| file_name | str | Bildfilnamn.|

###  Exempel

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objektindex.


```python

def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| stream | io.RawIOBase | Strömobjekt som innehåller bilddata.|
| width_scale | int | Skala för bildbredd, en procentandel.|
| height_scale | int | Skala för bildhöjd, en procentandel.|

###  Exempel

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs, 50, 50)

```


##  add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objektindex.


```python

def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| file_name | str | Bildfilnamn.|
| width_scale | int | Skala för bildbredd, en procentandel.|
| height_scale | int | Skala för bildhöjd, en procentandel.|

###  Exempel

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)
* klass [`PictureCollection`](/cells/python-net/sv/aspose.cells.drawing/picturecollection)
