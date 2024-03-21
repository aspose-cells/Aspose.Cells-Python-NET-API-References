---
title: emf_render_setting propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 130
url: /fr/aspose.cells/pptxsaveoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting propriété

Paramètre de rendu du métafichier Emf.

###  Remarques

 Les métafichiers EMF identifiés comme « EMF+ Dual » peuvent contenir à la fois des enregistrements EMF+ et des enregistrements EMF.
L'un ou l'autre type d'enregistrement peut être utilisé pour restituer l'image, uniquement EMF+ enregistrements, ou uniquement EMF enregistrements.
Lorsque [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/fr/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) est défini, alors les enregistrements EMF+ seront analysés lors du rendu sur la page, sinon seuls les enregistrements EMF seront analysés.
La valeur par défaut est [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/fr/aspose.cells/emfrendersetting#EMF_ONLY).
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
* module [`aspose.cells`](../../)
* classe [`EmfRenderSetting`](/cells/python-net/fr/aspose.cells/emfrendersetting)
* classe [`PptxSaveOptions`](/cells/python-net/fr/aspose.cells/pptxsaveoptions)
