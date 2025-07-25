---
title: add_arc metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells.drawing/shapecollection/add_arc/
is_root: false
---
##  add_arc(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en bågform i kalkylbladet.


###  Returnerar

Ett ArcShape-objekt.


```python

def add_arc(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int |Representerar den vertikala förskjutningen av ArcShape från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av ArcShape från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar höjden på ArcShape, i pixelenhet.|
| width | int | Representerar bredden på ArcShape, i pixelenhet.|

###  Exempel

```python

# add a arc
arcShape = shapes.add_arc(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
