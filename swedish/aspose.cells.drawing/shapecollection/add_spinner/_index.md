---
title: add_spinner metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 320
url: /sv/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en spinner i kalkylbladet.


###  Returnerar

Ett Spinner-objekt.


```python

def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int |Representerar den vertikala förskjutningen av Spinner från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av Spinner från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar Spinnerns höjd, i pixelenhet.|
| width | int | Representerar bredden på Spinner, i pixelenhet.|

###  Exempel

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
