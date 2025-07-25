---
title: regex_key propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key propriété

Indique si la clé recherchée est une expression régulière.
Si vrai, la clé recherchée sera considérée comme une expression régulière et analysée.
Sinon, la clé sera analysée selon les règles de MS Excel.

###  Remarques

Même si la clé de recherche a été spécifiée comme regex,
il peut être refactorisé selon le [`FindOptions.look_at_type`](/cells/python-net/fr/aspose.cells/findoptions#look_at_type) spécifié.
Par exemple, lorsque le type est [`LookAtType.CONTAINS`](/cells/python-net/fr/aspose.cells/lookattype#CONTAINS) (c'est la valeur par défaut pour ces options),
des caractères génériques seront ajoutés automatiquement au début et à la fin de la clé de recherche pour garantir que la correspondance sera
coché comme « contient ». Dans ce cas, les expressions régulières deviendront plus complexes.
et les performances diminueront également.
Ainsi, pour des raisons de performances, si l'utilisateur a spécifié la règle exacte pour l'expression régulière, il n'est pas nécessaire de
utilisez [`FindOptions.look_at_type`](/cells/python-net/fr/aspose.cells/findoptions#look_at_type) comme contrainte supplémentaire et l'utilisateur peut le définir comme [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/fr/aspose.cells/lookattype#ENTIRE_CONTENT)
pour obtenir de meilleures performances.
###  Définition:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`FindOptions`](/cells/python-net/fr/aspose.cells/findoptions)
