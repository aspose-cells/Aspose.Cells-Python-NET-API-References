---
title: méthode create_safe_sheet_name
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, nom_proposition){#str}
Vérifie le nom de la feuille donnée et en crée une valide si nécessaire.
Si le nom de feuille donné est conforme aux règles du nom de feuille Excel, renvoyez-le.
Sinon, la chaîne sera tronquée si la longueur dépasse la limite
et les caractères non valides seront remplacés par ' ', puis renverront la valeur de chaîne reconstruite.


###  Retour




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| name_proposal | str | nom de la feuille à utiliser|


##  create_safe_sheet_name(, nom_proposition, remplacer_caractère){#str-char}
Vérifie le nom de la feuille donnée et en crée une valide si nécessaire.
Si le nom de feuille donné est conforme aux règles du nom de feuille Excel, renvoyez-le.
Sinon, la chaîne sera tronquée si la longueur dépasse la limite
et les caractères non valides seront remplacés par le caractère donné, puis renverront la valeur de chaîne reconstruite.


###  Retour




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| name_proposal | str | nom de la feuille à utiliser|
| replace_char | char | caractère qui sera utilisé pour remplacer les caractères invalides dans le nom de feuille donné|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`CellsHelper`](/cells/python-net/fr/aspose.cells/cellshelper)
