---
title: add_check_box metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells.drawing/shapecollection/add_check_box/
is_root: false
---
##  add_check_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en kryssruta i kalkylbladet.


###  Returnerar

Det nya CheckBox-objektindexet.


```python

def add_check_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar kryssrutans vertikala förskjutning från dess översta rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av textrutan från dess vänstra kolumn, i pixelenhet.|
| height | int | Textrutans höjd, i pixelenhet.|
| width | int | Bredd på textruta, i pixlar.|

###  Exempel

```python

# add a CheckBox
checkBox = shapes.add_check_box(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
