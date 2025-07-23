---
title: add_list_box metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 190
url: /sv/aspose.cells.drawing/shapecollection/add_list_box/
is_root: false
---
##  add_list_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en listbox i kalkylbladet.


###  Returnerar

Ett ListBox-objekt.


```python

def add_list_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar den vertikala förskjutningen av ListBox från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av ListBox från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar höjden på listboxen, i pixelenhet.|
| width | int | Representerar bredden på listboxen, i pixlar.|

###  Exempel

```python

# add a list box
listBox = shapes.add_list_box(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
