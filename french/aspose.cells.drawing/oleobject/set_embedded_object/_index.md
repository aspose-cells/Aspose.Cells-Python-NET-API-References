---
title: méthode set_embedded_object
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 200
url: /fr/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label) {#bool-bytes-str-bool-str}
Définit les données d'objet intégrées.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| link_to_file | bool | Indique si l'objet est lié au fichier. Si la valeur est « true », le paramètre objectData est ignoré.|
| object_data | bytes | Les données de l'objet intégré.|
| source_file_name | str | Le nom du fichier.|
| display_as_icon | bool | Indique si l'objet doit être affiché sous forme d'icône.<br/> Si cette option est vraie, les données de l'image d'origine seront couvertes par l'icône.|
| label | str | Étiquette de l'icône. Fonctionne uniquement lorsque displayAsIcon est défini sur true.|


##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon) {#bool-bytes-str-bool-str-bool}
Définit les données d'objet intégrées.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| link_to_file | bool | Indique si l'objet est lié au fichier. Si la valeur est « true », le paramètre objectData est ignoré.|
| object_data | bytes | Les données de l'objet intégré.|
| source_file_name | str | Le nom du fichier.|
| display_as_icon | bool | Indique si l'objet doit être affiché sous forme d'icône.<br/> Si cette option est vraie, les données de l'image d'origine seront couvertes par l'icône.|
| label | str | Étiquette de l'icône. Fonctionne uniquement lorsque displayAsIcon est défini sur true.|
| update_icon | bool |Indique si l'icône est mise à jour automatiquement.|
###  Remarques

Comme Aspose peut mettre à jour toutes les icônes de fichiers intégrées, il est donc préférable que vous puissiez ajouter l'icône correcte avec `update_icon` comme faux.


###  Voir également

* module [`aspose.cells.drawing`](../../)
* classe [`OleObject`](/cells/python-net/fr/aspose.cells.drawing/oleobject)
