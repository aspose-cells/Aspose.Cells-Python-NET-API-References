---
title: emf_render_setting fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting fastighet

Inställning för rendering av Emf-metafil.

###  Anmärkningar

 EMF metafiler identifierade som "EMF+ Dual" kan innehålla både EMF+ poster och EMF poster.
Vilken typ av post som helst kan användas för att återge bilden, endast EMF+ poster, eller bara EMF poster.
När [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/sv/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) är inställt, kommer EMF+ poster att tolkas under rendering till bild, annars kommer endast EMF poster att tolkas.
Standardvärdet är [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/sv/aspose.cells/emfrendersetting#EMF_ONLY).
För ramverk som är beroende av .Net System.Drawing.Common ignoreras denna inställning.
###  Definition:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`EmfRenderSetting`](/cells/python-net/sv/aspose.cells/emfrendersetting)
* klass [`ImageOrPrintOptions`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions)
