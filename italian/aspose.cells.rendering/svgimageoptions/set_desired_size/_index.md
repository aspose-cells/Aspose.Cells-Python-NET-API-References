---
title: Metodo set_desired_size
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.rendering/svgimageoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Imposta la larghezza e l'altezza desiderate dell'immagine.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| desired_width | int | larghezza desiderata in pixel|
| desired_height | int | altezza desiderata in pixel|
###  Osservazioni

NOTA: questo membro è ora obsoleto. Invece,
si prega di utilizzare [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions/set_desired_size) impostando il parametro keepAspectRatio su false.
 Questa proprietà verrà rimossa 12 mesi dopo, a partire da maggio 2023.
Aspose si scusa per ogni eventuale disagio arrecato.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Imposta la larghezza e l'altezza desiderate dell'immagine.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| desired_width | int | larghezza desiderata in pixel|
| desired_height | int | altezza desiderata in pixel|
| keep_aspect_ratio | bool | se mantenere le proporzioni dell'immagine di origine|
###  Osservazioni

La larghezza e l'altezza dell'immagine di output in pixel saranno basate solo su
la larghezza e l'altezza desiderate.


[`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) e [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
in questo caso non influirà sulla larghezza e sull'altezza dell'immagine in uscita.


###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SvgImageOptions`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions)
