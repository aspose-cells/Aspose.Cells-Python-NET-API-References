---
title: méthode characters
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cells.drawing/listbox/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Renvoie un objet Characters qui représente une plage de characters dans le texte.


###  Retour

Objet Personnages.


```python

def characters(self, start_index, length):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start_index | int | L'index du début du caractère.|
| length | int | Le nombre de caractères.|
###  Remarques

Cette méthode ne fonctionne que sur les formes avec titre.
###  Exemple


```python

fontSetting = shape.characters(0, 4)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ListBox`](/cells/python-net/fr/aspose.cells.drawing/listbox)
