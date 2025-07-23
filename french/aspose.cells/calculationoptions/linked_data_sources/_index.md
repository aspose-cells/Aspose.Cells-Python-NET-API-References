---
title: linked_data_sources propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources propriété

Spécifie les sources de données pour les liens externes utilisés dans les formules.

###  Remarques

Comme [`Workbook.update_linked_data_source`](/cells/python-net/fr/aspose.cells/workbook/update_linked_data_source), ici vous pouvez préciser
sources de données pour les liens externes utilisés dans les formules à calculer, en particulier celles
utilisé dans la fonction INDIRECT. Pour les liens externes utilisés dans la fonction INDIRECT,
ils ne sont pas considérés comme faisant partie des liens externes du classeur et ne peuvent pas être mis à jour
par [`Workbook.update_linked_data_source`](/cells/python-net/fr/aspose.cells/workbook/update_linked_data_source).
La correspondance de ces classeurs avec des liens externes est déterminée par [`Workbook.file_name`](/cells/python-net/fr/aspose.cells/workbook#file_name)
et [`ExternalLink.data_source`](/cells/python-net/fr/aspose.cells/externallink#data_source). Veuillez donc vous assurer que [`Workbook.file_name`](/cells/python-net/fr/aspose.cells/workbook#file_name) a
été spécifié avec la valeur appropriée (généralement, elle devrait être la même que celle correspondante
[`ExternalLink.data_source`](/cells/python-net/fr/aspose.cells/externallink#data_source)) pour chaque classeur afin qu'ils puissent être liés comme prévu.
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
