---
title: méthode clear
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Supprime tous les liens externes.



```python

def clear(self):
    ...
```


###  Remarques

Lors de la suppression des liens externes, toutes les formules qui y font référence seront également supprimées car
les références deviennent invalides.

##  clear(self, update_references_as_local) {#bool}
Supprime tous les liens externes.



```python

def clear(self, update_references_as_local):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| update_references_as_local | bool |Mettre à jour toutes les références des liens externes dans les formules vers les références du classeur actuel lui-même.|
###  Remarques

Si des références doivent être mises à jour, ces références de liens externes dans les formules
sera modifié vers le classeur actuel lorsque cela sera possible.
Par exemple, la formule d'origine d'une cellule est "='externalsource.xlam'!customfunction()",
après avoir supprimé les liens externes, la formule deviendra "=customfunction()";
Lorsque la formule d'origine est "='[externalsource.xlam]Sheet1'!$A$1",
selon qu'il y a une feuille avec le nom « Feuille1 » dans le classeur actuel :
si vrai, la formule deviendra "=Sheet1!$A$1";
si faux, la formule deviendra "=#REF!$A$1".

Si les références ne doivent pas être mises à jour, toutes les formules contenant des références à des liens externes
seront également supprimés car ces références deviennent invalides.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`ExternalLinkCollection`](/cells/python-net/fr/aspose.cells/externallinkcollection)
