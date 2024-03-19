---
title: méthode register_add_in_function
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 180
url: /fr/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
Ajoute une fonction complémentaire dans le classeur


###  Retour

URL du fichier complémentaire qui contient les fonctions complémentaires


```python
def register_add_in_function(self, id, function_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| id | int | ID des données qui contiennent des fonctions complémentaires,<br/> peut être obtenu par le premier appel du [`WorksheetCollection.register_add_in_function`](/cells/python-net/fr/aspose.cells/worksheetcollection/register_add_in_function) pour le même fichier complémentaire.|
| function_name | str | le nom de la fonction complémentaire|


##  register_add_in_function {#str-str-bool}
Ajoute une fonction complémentaire dans le classeur


###  Retour

ID des données qui contiennent la fonction complémentaire donnée


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| add_in_file | str | le fichier contient les fonctions complémentaires|
| function_name | str | le nom de la fonction complémentaire|
| lib | bool | si le fichier de complément donné se trouve dans le répertoire ou le sous-répertoire de la bibliothèque Workbook Add-In.<br/>Cet indicateur prend effet et fait la différence lorsque addInFile est un chemin relatif :<br/> true indique que le chemin est relatif à la bibliothèque de compléments et false indique que le chemin est relatif à ce classeur.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`WorksheetCollection`](/cells/python-net/fr/aspose.cells/worksheetcollection)
