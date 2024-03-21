---
title: méthode intersect
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells/range/intersect/
is_root: false
---
##  intersect {#aspose.cells.Range}
Renvoie un objet [`Range`](/cells/python-net/fr/aspose.cells/range) qui représente l'intersection rectangulaire de deux plages.


###  Retour

Renvoie un objet [`Range`](/cells/python-net/fr/aspose.cells/range)


```python
def intersect(self, range):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/fr/aspose.cells/range) | La plage qui se croise.|
###  Remarques

Si les deux plages ne se croisent pas, renvoie null.
###  Exemple


```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A3:A10")
# Get intersected range of the two ranges.
intersectRange = range1.intersect(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
