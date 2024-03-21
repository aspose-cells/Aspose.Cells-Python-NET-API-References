---
title: méthode refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
Actualise les formules de tableau dynamique (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)
Les autres formules du classeur ne seront pas calculées de manière récursive même si elles ont été utilisées par des formules matricielles dynamiques.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| calculate | bool | S'il calcule et met à jour les valeurs de cellule pour ces formules de tableau dynamique|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
Actualise les formules de tableau dynamique (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| calculate | bool | S'il calcule et met à jour les valeurs de cellule pour ces formules de tableau dynamique|
| copts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Les options de calcul des formules|
###  Remarques

Pour des raisons de performances, nous n'actualisons pas automatiquement toutes les formules de tableau dynamique.
lorsque la formule elle-même ou les données auxquelles elle fait référence ont changé.
L'utilisateur doit donc appeler cette méthode manuellement après les opérations susceptibles d'influencer les formules matricielles dynamiques,
tels que l'importation/définition de valeurs de cellules, l'insertion/suppression de lignes/colonnes/plages, ... etc.

Pour la plupart des formules comportant des fonctions, le calcul de la plage de déversement nécessite également le calcul de la formule,
donc, en général, la valeur vraie pour l'indicateur "calculer" est préférée.
Si la formule est simple, comme une référence de plage ou un tableau (par exemple "=C1:E5", "={1,2;3,4}", ...),
fonction simple sur une plage ou un tableau (par exemple "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
et toutes les formules seront calculées plus tard (comme par [`Workbook.calculate_formula`](/cells/python-net/fr/aspose.cells/workbook/calculate_formula)),
puis utiliser une valeur fausse pour l'indicateur "calculer" peut éviter le calcul en double au profit des performances.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
