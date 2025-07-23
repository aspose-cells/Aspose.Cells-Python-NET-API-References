---
title: méthode copy
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 100
url: /fr/aspose.cells/range/copy/
is_root: false
---
##  copy(self, range) {#aspose.cells.Range}
Copie les données (y compris les formules), la mise en forme, les objets de dessin, etc. à partir d'une plage source.



```python

def copy(self, range):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/fr/aspose.cells/range) | Source objet [`Range`](/cells/python-net/fr/aspose.cells/range).|

###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy(self, range, options) {#aspose.cells.Range-aspose.cells.PasteOptions}
Copie de la plage avec les options de collage spécial.



```python

def copy(self, range, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/fr/aspose.cells/range) | La gamme source.|
| options | [`PasteOptions`](/cells/python-net/fr/aspose.cells/pasteoptions) | Les options spéciales de pâte.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
