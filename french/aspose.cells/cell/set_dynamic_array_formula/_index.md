---
title: méthode set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 340
url: /fr/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Définit une formule de tableau dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.


###  Retour

la plage dans laquelle la formule doit s'étendre.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | l'expression de la formule|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | options pour analyser la formule.<br/> L'option « Analyser » sera ignorée et la formule sera toujours analysée immédiatement|
| calculate_value | bool | si vous calculez cette formule de tableau dynamique pour les cellules de la plage renversée.|
###  Remarques

la plage renvoyée peut ne pas être la même que celle dans laquelle cette formule de tableau dynamique se déverse.
S'il y a des cellules non vides dans la plage, la formule sera définie pour la cellule actuelle uniquement et marquée comme « #SPILL ! ».
Mais pour ce genre de situation, nous renvoyons toujours toute la gamme dans laquelle cette formule devrait se déverser.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Définit une formule de tableau dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.


###  Retour

la plage dans laquelle la formule doit s'étendre.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | l'expression de la formule|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | options pour analyser la formule.<br/> L'option « Analyser » sera ignorée et la formule sera toujours analysée immédiatement|
| values | list |valeurs (résultats calculés) pour les cellules avec la formule de tableau dynamique donnée|
| calculate_range | bool | Calculez la plage renversée pour cette formule de tableau dynamique.<br/>Si le paramètre « valeurs » n'est pas nul et que cet indicateur est faux,<br/> alors la hauteur de la plage renversée sera values.Length et la largeur sera values[0].Length.|
| calculate_value | bool | si cette formule de tableau dynamique est calculée pour les cellules de la plage déversée lorsque « valeurs » est nulle<br/> ou l'élément correspondant dans « valeurs » pour une cellule est nul.|
###  Remarques

la plage renvoyée peut ne pas être la même que celle dans laquelle cette formule de tableau dynamique se déverse.
S'il y a des cellules non vides dans la plage, la formule sera définie pour la cellule actuelle uniquement et marquée comme « #SPILL ! ».
Mais pour ce genre de situation, nous renvoyons toujours toute la gamme dans laquelle cette formule devrait se déverser.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Définit une formule de tableau dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.


###  Retour

la plage dans laquelle la formule doit s'étendre.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | l'expression de la formule|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | options pour analyser la formule.<br/> L'option « Analyser » sera ignorée et la formule sera toujours analysée immédiatement|
| values | list |valeurs (résultats calculés) pour les cellules avec la formule de tableau dynamique donnée|
| calculate_range | bool | Calculez la plage renversée pour cette formule de tableau dynamique.<br/>Si le paramètre « valeurs » n'est pas nul et que cet indicateur est faux,<br/> alors la hauteur de la plage renversée sera values.Length et la largeur sera values[0].Length.|
| calculate_value | bool | si cette formule de tableau dynamique est calculée pour les cellules de la plage déversée lorsque « valeurs » est nulle<br/> ou l'élément correspondant dans « valeurs » pour une cellule est nul.|
| copts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Les options de calcul de la formule.<br/> Généralement, pour des raisons de performances, la propriété [`CalculationOptions.recursive`](/cells/python-net/fr/aspose.cells/calculationoptions#recursive) doit être fausse.|
###  Remarques

la plage renvoyée peut ne pas être la même que celle dans laquelle cette formule de tableau dynamique se déverse.
S'il y a des cellules non vides dans la plage, la formule sera définie pour la cellule actuelle uniquement et marquée comme « #SPILL ! ».
Mais pour ce genre de situation, nous renvoyons toujours toute la gamme dans laquelle cette formule devrait se déverser.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
