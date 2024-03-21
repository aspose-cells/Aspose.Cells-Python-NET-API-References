---
title: emf_render_setting proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 110
url: /it/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting proprietà

Impostazione per il rendering del metafile Emf.

###  Osservazioni

 I metafile EMF identificati come "EMF+ Dual" possono contenere sia i record EMF+ che i record EMF.
Per eseguire il rendering dell'immagine è possibile utilizzare entrambi i tipi di record: solo EMF+ record o solo EMF record.
Quando è impostato [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/it/aspose.cells/emfrendersetting#EMF_PLUS_PREFER), verranno analizzati EMF+ record durante il rendering nell'immagine, altrimenti verranno analizzati solo EMF record.
Il valore predefinito è [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/it/aspose.cells/emfrendersetting#EMF_ONLY).
Per i framework che dipendono da .Net System.Drawing.Common, questa impostazione viene ignorata.
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
* modulo [`aspose.cells.rendering`](../../)
* classe [`EmfRenderSetting`](/cells/python-net/it/aspose.cells/emfrendersetting)
* classe [`ImageOrPrintOptions`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions)
