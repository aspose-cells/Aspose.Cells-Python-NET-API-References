---
title: méthode get_enumerator
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 100
url: /fr/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
Obtient l'énumérateur pour les cellules de cette plage.


###  Retour

L'enquêteur de cellules


```python
def get_enumerator(self):
    ...
```


###  Remarques

Lors du parcours d'éléments par l'énumérateur renvoyé, la collection de cellules
ne doit pas être modifié (comme les opérations qui entraîneront l'instanciation d'un nouveau Cell/Row ou la suppression d'un Cell/Row existant).
Sinon, l'enquêteur risque de ne pas être en mesure de parcourir toutes les cellules correctement (certains éléments peuvent être parcourus à plusieurs reprises ou ignorés).
###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
