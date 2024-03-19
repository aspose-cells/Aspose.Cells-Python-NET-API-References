---
title: check_excel_restriction propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells/workbooksettings/check_excel_restriction/
is_root: false
---
##  check_excel_restriction propriété

Vérifier ou non la restriction du fichier Excel lorsque l'utilisateur modifie les objets liés aux cellules.
Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.
Lorsque vous saisissez une valeur supérieure à 32 Ko, par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.
Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard
vous pouvez afficher la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.
Cependant, si vous avez défini un type de valeur non valide pour le format de fichier Excel,
vous ne devez pas enregistrer le classeur au format de fichier Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire pour le fichier Excel généré.
###  Définition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`WorkbookSettings`](/cells/python-net/fr/aspose.cells/workbooksettings)
