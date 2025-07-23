---
title: méthode add
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Ajoute une condition de formatage et une plage de cellules affectée aux FormatConditions
Les FormatConditions peuvent contenir jusqu'à trois formats conditionnels.
Les références aux autres feuilles ne sont pas autorisées dans les formules de mise en forme conditionnelle.


###  Retour

[0] : Index de l'objet de condition de formatage ; [1] Index de la plage de cellules affectée.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) |Plage de cellules formatées conditionnellement.|
| type | [`FormatConditionType`](/cells/python-net/fr/aspose.cells/formatconditiontype) | Type de mise en forme conditionnelle. Il peut s'agir de l'un des membres de FormatConditionType.|
| operator_type | [`OperatorType`](/cells/python-net/fr/aspose.cells/operatortype) | Opérateur de comparaison. Il peut s'agir de l'un des membres de OperatorType.|
| formula1 | str | La valeur ou l’expression associée à la mise en forme conditionnelle.|
| formula2 | str | La valeur ou l'expression associée à la mise en forme conditionnelle|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`FormatConditionCollection`](/cells/python-net/fr/aspose.cells/formatconditioncollection)
