---
title: look_at_type propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type propriété

Regardez le type.

###  Remarques

Lorsque [`FindOptions.regex_key`](/cells/python-net/fr/aspose.cells/findoptions#regex_key) est vrai et que l'utilisateur a spécifié la règle exacte pour l'expression régulière,
pour des raisons de performances, cette propriété doit être définie sur [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/fr/aspose.cells/lookattype#ENTIRE_CONTENT).
Sinon, nous refactoriserons la clé de recherche pour garantir qu'elle puisse être mise en correspondance en fonction du type spécifique.
Par exemple, lorsque le type est [`LookAtType.CONTAINS`](/cells/python-net/fr/aspose.cells/lookattype#CONTAINS) (c'est la valeur par défaut pour cette propriété),
nous ajouterons automatiquement des caractères génériques au début et à la fin de la clé de recherche.
Dans ce cas, les expressions régulières deviendront plus complexes et les performances diminueront également.
###  Définition:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`FindOptions`](/cells/python-net/fr/aspose.cells/findoptions)
* classe [`LookAtType`](/cells/python-net/fr/aspose.cells/lookattype)
