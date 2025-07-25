---
title: emf_render_setting proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting proprietà

Impostazione per il rendering dei metafile Emf nel file sorgente.

###  Osservazioni

 I metafile EMF identificati come "EMF+ Dual" possono contenere sia record EMF+ sia record EMF.
Per il rendering dell'immagine è possibile utilizzare entrambi i tipi di record: solo i record EMF+ oppure solo i record EMF.
Se è impostato [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/it/aspose.cells/emfrendersetting#EMF_PLUS_PREFER), durante il rendering dell'immagine verranno analizzati i record EMF+, altrimenti verranno analizzati solo i record EMF.
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
