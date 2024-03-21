---
title: emf_render_setting proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 120
url: /it/aspose.cells/xpssaveoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting proprietà

Impostazione per il rendering del metafile Emf.

###  Osservazioni

 I metafile EMF identificati come "EMF+ Dual" possono contenere sia i record EMF+ che i record EMF.
Per eseguire il rendering dell'immagine è possibile utilizzare entrambi i tipi di record: solo EMF+ record o solo EMF record.
Quando è impostato [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/it/aspose.cells/emfrendersetting#EMF_PLUS_PREFER), i record EMF+ verranno analizzati durante il rendering nella pagina, altrimenti verranno analizzati solo i record EMF.
Il valore predefinito è [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/it/aspose.cells/emfrendersetting#EMF_ONLY).
###  Definizione:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`EmfRenderSetting`](/cells/python-net/it/aspose.cells/emfrendersetting)
* classe [`XpsSaveOptions`](/cells/python-net/it/aspose.cells/xpssaveoptions)
