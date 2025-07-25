---
title: méthode get_style
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells/row/get_style/
is_root: false
---
##  get_style(self) {#}
Obtient le style de cette ligne.



```python

def get_style(self):
    ...
```


###  Remarques

La modification directe de l'objet de style renvoyé n'a aucun effet sur cette ligne ou sur les cellules de cette ligne.
Vous devez appeler la méthode [`Row.apply_style`](/cells/python-net/fr/aspose.cells/row/apply_style) ou [`Row.set_style`](/cells/python-net/fr/aspose.cells/row/set_style)
pour appliquer la modification à cette ligne.

Le style de la ligne est le style qui sera hérité par les cellules de cette ligne (les cellules qui n'ont pas de paramètres de style personnalisés,
comme les cellules existantes dont le style n'a pas été défini explicitement ou celles qui n'ont pas été instanciées)


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Row`](/cells/python-net/fr/aspose.cells/row)
