---
title: méthode refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 290
url: /fr/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
Actualise les formules de tableau dynamiques (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)
Les autres formules du classeur ne seront pas calculées de manière récursive même si elles ont été utilisées par des formules de tableau dynamique.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| calculate | bool | Calcule et met à jour les valeurs des cellules pour ces formules de tableau dynamiques|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
Actualise les formules de tableau dynamiques (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| calculate | bool | Calcule et met à jour les valeurs des cellules pour ces formules de tableau dynamiques|
| copts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Les options de calcul des formules|
###  Remarques

Pour des raisons de performances, nous n'actualisons pas automatiquement toutes les formules de tableau dynamiques
lorsque la formule elle-même ou les données auxquelles elle fait référence ont changé.
L'utilisateur doit donc appeler cette méthode manuellement après les opérations susceptibles d'influencer les formules de tableau dynamiques,
comme l'importation/la définition de valeurs de cellules, l'insertion/la suppression de lignes/colonnes/plages, ...etc.

Pour la plupart des formules avec des fonctions, le calcul de la plage de déversement nécessite également le calcul de la formule,
donc en général, la vraie valeur pour l'indicateur « calculer » est préférée.
Si la formule est simple, comme une référence de plage ou un tableau (par exemple "=C1:E5", "={1,2;3,4}", ...),
fonction simple sur une plage ou un tableau (par exemple "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
et toutes les formules seront calculées plus tard (par exemple par [`Workbook.calculate_formula`](/cells/python-net/fr/aspose.cells/workbook/calculate_formula)),
alors utiliser une fausse valeur pour l'indicateur « calculer » peut éviter le calcul en double au profit des performances.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
