---
title: add_text_box metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 340
url: /sv/aspose.cells.drawing/shapecollection/add_text_box/
is_root: false
---
##  add_text_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Lägger till en textruta i kalkylbladet.


###  Returnerar

Ett [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox)-objekt.


```python

def add_text_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar textrutans vertikala förskjutning från dess översta rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av textrutan från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar textrutans höjd, i pixelenhet.|
| width | int | Representerar textrutans bredd, i pixlar.|

###  Exempel

```python

# add a TextBox
textBox = shapes.add_text_box(1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
* klass [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox)
