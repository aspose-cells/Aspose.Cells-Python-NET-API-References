---
title: tiff_color_depth propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 400
url: /fr/aspose.cells.rendering/svgimageoptions/tiff_color_depth/
is_root: false
---
##  tiff_color_depth propriété

Obtient ou définit la profondeur de bits à appliquer uniquement lors de l'enregistrement des pages au format `Tiff`.

###  Remarques

N'a d'effet que lors de l'enregistrement dans TIFF.
Si TiffCompression est défini sur CCITT3, CCITT4, cela n'aura aucun effet, la profondeur de bits de l'image tiff générée sera toujours de 1.
###  Définition:
```python
@property
def tiff_color_depth(self):
    ...
@tiff_color_depth.setter
def tiff_color_depth(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`ColorDepth`](/cells/python-net/fr/aspose.cells.rendering/colordepth)
* classe [`SvgImageOptions`](/cells/python-net/fr/aspose.cells.rendering/svgimageoptions)
