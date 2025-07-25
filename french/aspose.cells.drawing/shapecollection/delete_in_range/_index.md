---
title: méthode delete_in_range
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 430
url: /fr/aspose.cells.drawing/shapecollection/delete_in_range/
is_root: false
---
##  delete_in_range(self, ca) {#aspose.cells.CellArea}
Supprimez les formes de la plage. Les formes de commentaires ne seront pas supprimées.



```python

def delete_in_range(self, ca):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) |La plage. Si les formes sont contenues dans la plage, elles seront supprimées.|

###  Exemple

```python
from aspose.cells import CellArea

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
area3 = CellArea()
area3.start_column = 0
area3.start_row = 5
area3.end_column = 5
area3.end_row = 8
# del
shapes.delete_in_range(area3)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
