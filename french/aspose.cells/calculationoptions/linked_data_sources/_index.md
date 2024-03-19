---
title: linked_data_sources propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources propriété

Spécifie les sources de données pour les liens externes utilisés dans les formules.

###  Remarques

Comme [`Workbook.update_linked_data_source`](/cells/python-net/fr/aspose.cells/workbook/update_linked_data_source), ici vous pouvez préciser
sources de données pour les liens externes utilisés dans les formules à calculer, notamment celles
utilisé dans la fonction INDIRECT. Pour les liens externes utilisés dans la fonction INDIRECT,
ils ne font pas partie des liens externes du classeur et ne peuvent pas être mis à jour
par [`Workbook.update_linked_data_source`](/cells/python-net/fr/aspose.cells/workbook/update_linked_data_source).
###  Définition:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions)
