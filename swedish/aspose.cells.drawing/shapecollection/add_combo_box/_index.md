---
title: add_combo_box metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells.drawing/shapecollection/add_combo_box/
is_root: false
---
##  add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en kombinationsruta i kalkylbladet.


###  Returnerar

Ett ComboBox-objekt.


```python

def add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar den vertikala förskjutningen av kombinationsboxen från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av ComboBox från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar höjden på kombinationsrutan, i pixelenhet.|
| width | int | Representerar bredden på kombinationsrutan, i pixelenhet.|

###  Exempel

```python

# add a combo box
comboBox = shapes.add_combo_box(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
