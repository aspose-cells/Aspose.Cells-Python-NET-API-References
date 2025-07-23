---
title: trim_tailing_blank_cells propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 240
url: /fr/aspose.cells/txtsaveoptions/trim_tailing_blank_cells/
is_root: false
---
##  trim_tailing_blank_cells propriété

Indique si les cellules vides en fin de ligne doivent être supprimées. La valeur par défaut est « false ».

###  Remarques

Lors de l'enregistrement avec le mode LightCells et que le [`TxtSaveOptions.export_area`](/cells/python-net/fr/aspose.cells/txtsaveoptions#export_area) n'a pas été spécifié,
cette option n'a aucun effet et une ligne sera étendue uniquement à la dernière cellule fournie par
la mise en œuvre [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/fr/aspose.cells/txtsaveoptions)
###  Définition:
```python
@property
def trim_tailing_blank_cells(self):
    ...
@trim_tailing_blank_cells.setter
def trim_tailing_blank_cells(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`TxtSaveOptions`](/cells/python-net/fr/aspose.cells/txtsaveoptions)
