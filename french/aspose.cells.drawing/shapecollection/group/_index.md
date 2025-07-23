---
title: méthode group
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 460
url: /fr/aspose.cells.drawing/shapecollection/group/
is_root: false
---
##  group(self, group_items) {#list}
Regroupez les formes.


###  Retour

Renvoie la forme group.


```python

def group(self, group_items):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| group_items | list | les éléments du groupe.|
###  Remarques

La forme dans le groupeItems ne doit pas être groupée.
La forme doit être dans cette collection Formes.
###  Exemple

```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
