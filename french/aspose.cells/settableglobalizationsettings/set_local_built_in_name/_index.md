---
title: méthode set_local_built_in_name
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 340
url: /fr/aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---
##  set_local_built_in_name(self, standard_name, local_name, bidirectional) {#str-str-bool}
Définit le texte dépendant des paramètres régionaux pour le nom intégré avec le texte de nom standard donné.



```python

def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| standard_name | str | Texte de nom standard (locale en-US) du nom intégré.|
| local_name | str | Texte du nom dépendant des paramètres régionaux|
| bidirectional | bool |Si le texte du nom local doit être mappé automatiquement au texte du nom standard.<br/>Si vrai, le texte du nom local sera automatiquement mappé au texte du nom standard<br/>l'utilisateur n'a donc pas besoin d'appeler à nouveau le [`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_standard_built_in_name)<br/> pour la même paire de noms standard et locaux|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`SettableGlobalizationSettings`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings)
