---
title: méthode set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 330
url: /fr/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
Définit la formule matricielle dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.


###  Retour

la plage dans laquelle la formule doit déborder.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str |l'expression de la formule|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | options pour analyser la formule.<br/> L'option "Analyser" sera ignorée et la formule sera toujours analysée immédiatement|
| calculate_value | bool | si calculer cette formule de tableau dynamique pour les cellules de la plage déversée.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Définit la formule matricielle dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.


###  Retour

la plage dans laquelle la formule doit déborder.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str |l'expression de la formule|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | options pour analyser la formule.<br/> L'option "Analyser" sera ignorée et la formule sera toujours analysée immédiatement|
| values | list | valeurs (résultats calculés) pour les cellules avec une formule de tableau dynamique donnée|
| calculate_range | bool | Calcule ou non la plage déversée pour cette formule de tableau dynamique.<br/>Si le paramètre "values" n'est pas nul et que ce flag est faux,<br/> alors la hauteur de la plage déversée sera des valeurs. La longueur et la largeur seront des valeurs [0].|
| calculate_value | bool | si calculer cette formule de tableau dynamique pour les cellules de la plage déversée lorsque "valeurs" est nulle<br/> ou l'élément correspondant dans "valeurs" pour une cellule est nul.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Définit la formule matricielle dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.


###  Retour

la plage dans laquelle la formule doit déborder.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str |l'expression de la formule|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | options pour analyser la formule.<br/> L'option "Analyser" sera ignorée et la formule sera toujours analysée immédiatement|
| values | list | valeurs (résultats calculés) pour les cellules avec une formule de tableau dynamique donnée|
| calculate_range | bool | Calcule ou non la plage déversée pour cette formule de tableau dynamique.<br/>Si le paramètre "values" n'est pas nul et que ce flag est faux,<br/> alors la hauteur de la plage déversée sera des valeurs. La longueur et la largeur seront des valeurs [0].|
| calculate_value | bool | si calculer cette formule de tableau dynamique pour les cellules de la plage déversée lorsque "valeurs" est nulle<br/> ou l'élément correspondant dans "valeurs" pour une cellule est nul.|
| copts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Les options de calcul de la formule.<br/> Généralement, pour des raisons de performances, la propriété [`CalculationOptions.recursive`](/cells/python-net/fr/aspose.cells/calculationoptions#recursive) doit être fausse.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
