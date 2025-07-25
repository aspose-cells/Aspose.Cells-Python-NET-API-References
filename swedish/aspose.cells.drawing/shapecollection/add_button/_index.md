---
title: add_button metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en knapp i kalkylbladet.


###  Returnerar

Ett knappobjekt.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar knappens vertikala förskjutning från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int |Representerar knappens horisontella förskjutning från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar knappens höjd, i pixlar.|
| width | int | Representerar knappens bredd, i pixlar.|

###  Exempel

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
