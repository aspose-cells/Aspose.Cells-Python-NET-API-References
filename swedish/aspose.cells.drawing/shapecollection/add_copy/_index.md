---
title: add_copy metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Lägger till och kopierar en form till kalkylbladet.


###  Returnerar

Det nya objektet [`Shape`](/cells/python-net/sv/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/sv/aspose.cells.drawing/shape) | Källform.|
| top_row | int |Indexet på den översta raden.|
| top | int | Representerar den vertikala förskjutningen från dess översta rad, i pixelenhet.|
| left_column | int | Indexet i vänster kolumn.|
| left | int | Representerar den horisontella förskjutningen från dess vänstra kolumn, i pixelenhet.|

###  Exempel

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Shape`](/cells/python-net/sv/aspose.cells.drawing/shape)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
