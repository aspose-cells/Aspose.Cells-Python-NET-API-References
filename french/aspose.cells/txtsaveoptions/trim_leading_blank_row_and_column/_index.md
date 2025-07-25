---
title: trim_leading_blank_row_and_column propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 230
url: /fr/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column propriété

Indique si les lignes et les colonnes vides de début doivent être coupées comme le fait MS Excel.
La valeur par défaut est vrai.

###  Remarques

De même que la règle dans MS Excel, une ligne/colonne ne sera pas considérée comme vide si elle a un style personnalisé,
même s'il ne contient aucune donnée cellulaire.
Lors de l'enregistrement avec le mode LightCells, cette option n'a aucun effet.
L'utilisateur doit contrôler la plage de sortie en implémentant [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/fr/aspose.cells/txtsaveoptions)
ou en précisant le [`TxtSaveOptions.export_area`](/cells/python-net/fr/aspose.cells/txtsaveoptions#export_area)
###  Définition:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`TxtSaveOptions`](/cells/python-net/fr/aspose.cells/txtsaveoptions)
