---
title: tiff_color_depth proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 400
url: /it/aspose.cells.rendering/svgimageoptions/tiff_color_depth/
is_root: false
---
##  tiff_color_depth proprietà

Ottiene o imposta la profondità di bit da applicare solo quando si salvano le pagine nel formato `Tiff`.

###  Osservazioni

Ha effetto solo se si salva su TIFF.
Se TiffCompression è impostato su CCITT3, CCITT4, questo non avrà effetto, la profondità di bit dell'immagine tiff generata sarà sempre 1.
###  Definizione:
```python
@property
def tiff_color_depth(self):
    ...
@tiff_color_depth.setter
def tiff_color_depth(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`ColorDepth`](/cells/python-net/it/aspose.cells.rendering/colordepth)
* classe [`SvgImageOptions`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions)
