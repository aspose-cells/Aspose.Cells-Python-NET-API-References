---
title: méthode delete_blank_rows
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 210
url: /fr/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Supprimez toutes les lignes vides qui ne contiennent aucune donnée ni aucun autre objet.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Supprimez toutes les lignes vides qui ne contiennent aucune donnée ou certains objets spéciaux tels que des commentaires visibles, des tableaux croisés dynamiques.



```python

def delete_blank_rows(self, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/fr/aspose.cells/deleteoptions) | Les options de suppression de plage.|
###  Remarques

Pour les lignes vides qui seront supprimées, il est non seulement nécessaire que [`Row.is_blank`](/cells/python-net/fr/aspose.cells/row#is_blank) soit vrai,
mais il ne devrait pas non plus y avoir de commentaire visible défini pour aucune cellule de ces lignes,
et aucun tableau croisé dynamique dont la plage les croise.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
