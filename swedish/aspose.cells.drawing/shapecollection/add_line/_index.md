---
title: add_line metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 170
url: /sv/aspose.cells.drawing/shapecollection/add_line/
is_root: false
---
##  add_line(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en linjeform i kalkylbladet.


###  Returnerar

Ett LineShape-objekt.


```python

def add_line(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar linjeformens vertikala förskjutning från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av linjeformen från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar höjden på linjeformen, i pixelenhet.|
| width | int |Representerar bredden på linjeformen, i pixelenhet.|

###  Exempel

```python

#  add a line object
lineShape = shapes.add_line(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
