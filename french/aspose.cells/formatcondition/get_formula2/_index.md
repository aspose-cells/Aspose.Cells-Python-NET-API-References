---
title: méthode get_formula2
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/formatcondition/get_formula2/
is_root: false
---
##  get_formula2(self, is_r1c1, is_local) {#bool-bool}
Obtient la valeur ou l'expression associée à cette condition de format.


###  Retour

La valeur ou l’expression associée à cette condition de format.


```python

def get_formula2(self, is_r1c1, is_local):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| is_r1c1 | bool | Si la formule doit être formatée comme R1C1.|
| is_local | bool | Si la formule doit être formatée par les paramètres régionaux.|


##  get_formula2(self, row, column) {#int-int}
Obtient la formule de mise en forme conditionnelle de la cellule.


###  Retour

La formule.


```python

def get_formula2(self, row, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row | int | L'index de ligne.|
| column | int | L'index des colonnes.|


##  get_formula2(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
Obtient la valeur ou l'expression de la mise en forme conditionnelle de la cellule.


###  Retour

La valeur ou l’expression associée à la mise en forme conditionnelle de la cellule.


```python

def get_formula2(self, is_r1c1, is_local, row, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| is_r1c1 | bool | Si la formule doit être formatée comme R1C1.|
| is_local | bool | Si la formule doit être formatée par les paramètres régionaux.|
| row | int | L'index de ligne.|
| column | int | L'index des colonnes.|
###  Remarques

La cellule donnée doit être contenue par cette mise en forme conditionnelle, sinon null sera renvoyé.


###  Voir également

* module [`aspose.cells`](../../)
* classe [`FormatCondition`](/cells/python-net/fr/aspose.cells/formatcondition)
