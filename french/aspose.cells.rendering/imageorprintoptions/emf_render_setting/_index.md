---
title: emf_render_setting propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting propriété

Paramètre pour le rendu des métafichiers Emf dans le fichier source.

###  Remarques

 Les métafichiers EMF identifiés comme « EMF+ Dual » peuvent contenir à la fois des enregistrements EMF+ et des enregistrements EMF.
L'un ou l'autre type d'enregistrement peut être utilisé pour restituer l'image, uniquement les enregistrements EMF+ ou uniquement les enregistrements EMF.
Lorsque [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/fr/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) est défini, les enregistrements EMF+ seront analysés lors du rendu de l'image, sinon seuls les enregistrements EMF seront analysés.
La valeur par défaut est [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/fr/aspose.cells/emfrendersetting#EMF_ONLY).
Pour les frameworks qui dépendent de .Net System.Drawing.Common, ce paramètre est ignoré.
###  Définition:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`EmfRenderSetting`](/cells/python-net/fr/aspose.cells/emfrendersetting)
* classe [`ImageOrPrintOptions`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions)
