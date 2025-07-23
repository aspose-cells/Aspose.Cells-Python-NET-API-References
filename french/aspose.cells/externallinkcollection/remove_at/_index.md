---
title: méthode remove_at
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Supprime le lien externe spécifié du classeur.



```python

def remove_at(self, index):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| index | int | l'index du lien externe à supprimer.|
###  Remarques

Lors de la suppression du lien externe, toutes les formules qui y font référence seront également supprimées car
les références deviennent invalides.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Supprime le lien externe spécifié du classeur.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| index | int | l'index du lien externe à supprimer.|
| update_references_as_local | bool | Mettre à jour toutes les références du lien externe donné vers la référence du classeur actuel lui-même.<br/> Consultez le [`ExternalLinkCollection.clear`](/cells/python-net/fr/aspose.cells/externallinkcollection/clear) pour obtenir plus de détails sur ce paramètre.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`ExternalLinkCollection`](/cells/python-net/fr/aspose.cells/externallinkcollection)
