---
title: emf_render_setting fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 130
url: /sv/aspose.cells.rendering/svgimageoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting fastighet

Inställning för att rendera EMF-metafiler i källfilen.

###  Anmärkningar

 EMF-metafiler identifierade som "EMF+ Dual" kan innehålla både EMF+-poster och EMF-poster.
Båda typerna av poster kan användas för att rendera bilden, endast EMF+ poster, eller endast EMF poster.
När [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/sv/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) är inställt kommer fler än EMF poster att tolkas vid rendering till bild, annars kommer endast EMF poster att tolkas.
Standardvärdet är [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/sv/aspose.cells/emfrendersetting#EMF_ONLY).
För ramverk som är beroende av .Net System.Drawing.Common ignoreras den här inställningen.
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
* klass [`SvgImageOptions`](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions)
