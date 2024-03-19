---
title: méthode get_default_sheet_name
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name {#}
Obtient le nom de feuille par défaut pour ajouter automatiquement une feuille de calcul.
La valeur par défaut est « Feuille ».


###  Retour

le nom de la feuille par défaut pour ajouter automatiquement une feuille de calcul


```python
def get_default_sheet_name(self):
    ...
```


###  Remarques

Le automatiquement ajouté (comme par [`WorksheetCollection.add`](/cells/python-net/fr/aspose.cells/worksheetcollection/add))
le nom de la feuille sera le nom spécifié plus le numéro de séquence.
 Par exemple, pour l'Allemagne, l'utilisateur souhaite peut-être que le nom de la feuille soit "Tabellenblatt2" au lieu de "Sheet2".
L'utilisateur peut ensuite implémenter cette méthode pour renvoyer "Tabellenblatt".


###  Voir également
* module [`aspose.cells`](../../)
* classe [`SettableGlobalizationSettings`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings)
