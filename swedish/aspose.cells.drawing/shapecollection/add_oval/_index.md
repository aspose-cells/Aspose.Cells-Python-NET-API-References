---
title: add_oval metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 220
url: /sv/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en oval i kalkylbladet.


###  Returnerar

Ett ovalt föremål.


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar den vertikala förskjutningen av ovalen från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av ovalen från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar höjden på ovalen, i pixelenhet.|
| width | int | Representerar bredden på ovalen, i pixelenhet.|

###  Exempel

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
