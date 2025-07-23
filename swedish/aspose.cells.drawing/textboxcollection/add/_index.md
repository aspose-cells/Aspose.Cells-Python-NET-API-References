---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.drawing/textboxcollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, height, width) {#int-int-int-int}
Lägger till en textruta i samlingen.


###  Returnerar

[`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox) objektindex.


```python

def add(self, upper_left_row, upper_left_column, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| height | int | Textrutans höjd, i pixelenhet.|
| width | int | Bredd på textruta, i pixlar.|

###  Exempel

```python

# add a TextBox
index2 = textBoxCollection.add(1, 1, 50, 100)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox)
* klass [`TextBoxCollection`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection)
