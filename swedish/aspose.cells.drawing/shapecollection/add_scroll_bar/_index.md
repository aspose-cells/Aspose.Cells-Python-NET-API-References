---
title: add_scroll_bar metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 270
url: /sv/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en rullningslist i kalkylbladet.


###  Returnerar

Ett ScrollBar-objekt.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int |Representerar den vertikala förskjutningen av rullningsfältet från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av rullningsfältet från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar höjden på ScrollBar, i pixlar.|
| width | int | Representerar bredden på rullningslisten, i pixlar.|

###  Exempel

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
