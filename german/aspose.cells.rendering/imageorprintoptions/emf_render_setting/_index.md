---
title: emf_render_setting Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting Eigentum

Einstellung zum Rendern der EMF-Metadatei.

###  Bemerkungen

 EMF-Metadateien mit der Bezeichnung „EMF+ Dual“ können sowohl EMF+-Datensätze als auch EMF-Datensätze enthalten.
Zum Rendern des Bildes kann jeder Datensatztyp verwendet werden, nur EMF+ Datensätze oder nur EMF Datensätze.
Wenn [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/de/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) festgelegt ist, werden beim Rendern in ein Bild mehr als EMF Datensätze geparst, andernfalls werden nur EMF Datensätze geparst.
Der Standardwert ist [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/de/aspose.cells/emfrendersetting#EMF_ONLY).
Für die Frameworks, die von .Net System.Drawing.Common abhängen, wird diese Einstellung ignoriert.
###  Definition:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.rendering`](../../)
* Klasse [`EmfRenderSetting`](/cells/python-net/de/aspose.cells/emfrendersetting)
* Klasse [`ImageOrPrintOptions`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions)
