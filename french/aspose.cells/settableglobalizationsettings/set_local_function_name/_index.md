---
title: méthode set_local_function_name
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 350
url: /fr/aspose.cells/settableglobalizationsettings/set_local_function_name/
is_root: false
---
##  set_local_function_name {#str-str-bool}
Définit le nom de fonction dépendant des paramètres régionaux correspondant au nom de fonction standard donné.



```python
def set_local_function_name(self, standard_name, local_name, bidirectional):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| standard_name | str | Nom de la fonction standard (locale en-US).|
| local_name | str | Nom de la fonction dépendant des paramètres régionaux|
| bidirectional | bool | Permet de mapper automatiquement le nom de la fonction locale au nom de la fonction standard.<br/>Si vrai, le nom local sera automatiquement mappé au nom standard<br/>l'utilisateur n'a donc pas besoin d'appeler à nouveau le [`SettableGlobalizationSettings.set_standard_function_name`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_standard_function_name)<br/> pour la même paire de noms standard et locaux|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`SettableGlobalizationSettings`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings)
