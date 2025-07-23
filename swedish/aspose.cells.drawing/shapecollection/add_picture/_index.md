---
title: add_picture metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 230
url: /sv/aspose.cells.drawing/shapecollection/add_picture/
is_root: false
---
##  add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) Bildobjekt.


```python

def add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
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
    picture = shapes.add_picture(1, 0, 1, 0, fs)

```


##  add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Lägger till en bild i samlingen.


###  Returnerar

[`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) Bildobjekt.


```python

def add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
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
    picture = shapes.add_picture(1, 1, fs, 50, 60)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
