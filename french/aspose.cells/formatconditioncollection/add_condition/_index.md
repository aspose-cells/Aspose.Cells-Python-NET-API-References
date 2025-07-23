---
title: méthode add_condition
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Ajouter une condition de format.


###  Retour

Condition de formatage de l'index de l'objet ;


```python

def add_condition(self, type):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/fr/aspose.cells/formatconditiontype) | Type de condition de format.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Ajoute une condition de formatage.


###  Retour

Condition de formatage de l'index de l'objet ;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/fr/aspose.cells/formatconditiontype) | Le type de condition de format.|
| operator_type | [`OperatorType`](/cells/python-net/fr/aspose.cells/operatortype) | Le type d'opérateur|
| formula1 | str | La valeur ou l’expression associée à la mise en forme conditionnelle.<br/>Si la valeur d'entrée commence par « = », elle sera alors considérée comme une formule.<br/>Sinon, il sera considéré comme une valeur simple (texte, nombre, booléen).<br/> Pour une valeur de texte commençant par « = », l'utilisateur peut la saisir sous forme de formule au format : « =\"=...\" ».|
| formula2 | str | La valeur ou l’expression associée à la mise en forme conditionnelle.<br/> Le format d'entrée est le même que celui de la formule 1|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`FormatConditionCollection`](/cells/python-net/fr/aspose.cells/formatconditioncollection)
