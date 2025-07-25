---
title: set_desired_size metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.rendering/imageorprintoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Ställer in önskad bredd och höjd på bilden.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| desired_width | int | önskad bredd i pixlar|
| desired_height | int | önskad höjd i pixlar|
###  Anmärkningar

OBS! Denna medlem är nu föråldrad. Istället,
Använd [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/set_desired_size) genom att sätta parametern keepAspectRatio till false.
 Den här egenskapen kommer att tas bort 12 månader senare från och med maj 2023.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Ställer in önskad bredd och höjd på bilden.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| desired_width | int | önskad bredd i pixlar|
| desired_height | int | önskad höjd i pixlar|
| keep_aspect_ratio | bool | om bildförhållandet för ursprungsbilden ska behållas|
###  Anmärkningar

Bredden och höjden på utdatabilden i pixlar kommer endast att baseras på
den inställda önskade bredden och höjden.


[`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) och [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
kommer inte att påverka bredden och höjden på den utgående bilden i det här fallet.


###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`ImageOrPrintOptions`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions)
