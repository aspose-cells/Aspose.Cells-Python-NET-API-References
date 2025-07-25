---
title: check_excel_restriction propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/htmlloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction propriété

Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.
Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.
Lorsque vous saisissez une valeur supérieure à 32 Ko, comme par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.
Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard
vous pouvez générer la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.
Cependant, si vous avez défini un type de valeur qui n'est pas valide pour le format de fichier Excel,
Vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire dans le fichier Excel généré.
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
* classe [`HtmlLoadOptions`](/cells/python-net/fr/aspose.cells/htmlloadoptions)
