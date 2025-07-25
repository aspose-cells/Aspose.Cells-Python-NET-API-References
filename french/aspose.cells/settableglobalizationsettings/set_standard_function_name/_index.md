---
title: méthode set_standard_function_name
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 380
url: /fr/aspose.cells/settableglobalizationsettings/set_standard_function_name/
is_root: false
---
##  set_standard_function_name(self, local_name, standard_name, bidirectional) {#str-str-bool}
Définit le nom de la fonction dépendant des paramètres régionaux en fonction du nom de fonction standard donné.



```python

def set_standard_function_name(self, local_name, standard_name, bidirectional):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| local_name | str | Nom de fonction dépendant des paramètres régionaux|
| standard_name | str | Nom de fonction standard (locale en-US).|
| bidirectional | bool | Si le nom de la fonction standard doit être mappé automatiquement au nom de la fonction locale.<br/>Si vrai, le nom standard sera automatiquement mappé au nom local<br/>l'utilisateur n'a donc pas besoin d'appeler à nouveau le [`SettableGlobalizationSettings.set_local_function_name`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_local_function_name)<br/> pour la même paire de noms standard et locaux|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`SettableGlobalizationSettings`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings)
