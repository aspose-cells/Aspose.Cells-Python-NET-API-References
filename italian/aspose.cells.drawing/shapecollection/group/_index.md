---
title: Metodo group
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 460
url: /it/aspose.cells.drawing/shapecollection/group/
is_root: false
---
##  group(self, group_items) {#list}
Raggruppa le forme.


###  ritorna

Restituisce la forma group.


```python

def group(self, group_items):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| group_items | list | gli elementi del gruppo.|
###  Osservazioni

La forma nel gruppoItems non deve essere raggruppata.
La forma deve trovarsi in questa raccolta Forme.
###  Esempio

```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
