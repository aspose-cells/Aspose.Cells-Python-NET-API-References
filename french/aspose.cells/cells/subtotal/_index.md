---
title: méthode subtotal
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 910
url: /fr/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Crée des sous-totaux pour la plage.



```python
def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La gamme|
| group_by | int | Le champ à regrouper, sous forme de décalage entier de base zéro|
| function | [`ConsolidationFunction`](/cells/python-net/fr/aspose.cells/consolidationfunction) | La fonction de sous-total.|
| total_list | list | Tableau de décalages de champs de base zéro, indiquant les champs auxquels les sous-totaux sont ajoutés.|


##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Crée des sous-totaux pour la plage.



```python
def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La gamme|
| group_by | int | Le champ à regrouper, sous forme de décalage entier de base zéro|
| function | [`ConsolidationFunction`](/cells/python-net/fr/aspose.cells/consolidationfunction) | La fonction de sous-total.|
| total_list | list | Tableau de décalages de champs de base zéro, indiquant les champs auxquels les sous-totaux sont ajoutés.|
| replace | bool | Indique si remplacer les sous-totaux actuels|
| page_breaks | bool | Indique si ajouter un saut de page entre les groupes|
| summary_below_data | bool | Indique si vous ajoutez un résumé sous les données.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
