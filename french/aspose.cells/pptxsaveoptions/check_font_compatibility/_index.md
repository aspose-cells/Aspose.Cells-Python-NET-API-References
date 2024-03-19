---
title: check_font_compatibility propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells/pptxsaveoptions/check_font_compatibility/
is_root: false
---
##  check_font_compatibility propriété

Indique s’il faut vérifier la compatibilité des polices pour chaque caractère du texte.

###  Remarques

La valeur par défaut est vraie.
Désactiver cette propriété peut donner de meilleures performances.
Mais lorsque la police de texte/caractère par défaut ou spécifiée ne peut pas être utilisée pour le restituer,
des caractères illisibles (tels qu'un bloc) peuvent apparaître dans le pdf généré.
Dans une telle situation, l'utilisateur doit conserver cette propriété comme vraie afin que
une police alternative peut être recherchée et utilisée pour restituer le texte à la place ;
###  Définition:
```python
@property
def check_font_compatibility(self):
    ...
@check_font_compatibility.setter
def check_font_compatibility(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`PptxSaveOptions`](/cells/python-net/fr/aspose.cells/pptxsaveoptions)
