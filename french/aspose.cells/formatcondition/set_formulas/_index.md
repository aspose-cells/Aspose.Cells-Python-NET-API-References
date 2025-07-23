---
title: méthode set_formulas
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells/formatcondition/set_formulas/
is_root: false
---
##  set_formulas(self, formula1, formula2, is_r1c1, is_local) {#str-str-bool-bool}
Définit la valeur ou l'expression associée à cette condition de format.



```python

def set_formulas(self, formula1, formula2, is_r1c1, is_local):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula1 | str | La valeur ou l’expression associée à cette condition de format.<br/>Si la valeur d'entrée commence par « = », elle sera considérée comme une formule. Sinon, elle sera considérée comme une valeur simple (texte, nombre, booléen).<br/> Pour une valeur de texte commençant par « = », l'utilisateur peut la saisir sous forme de formule au format : « =\"=...\" ».|
| formula2 | str | Valeur ou expression associée à cette condition de format. Le format d'entrée est identique à celui de la formule 1.|
| is_r1c1 | bool | Que la formule soit la formule R1C1.|
| is_local | bool | Si la formule est formatée en fonction des paramètres régionaux.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`FormatCondition`](/cells/python-net/fr/aspose.cells/formatcondition)
