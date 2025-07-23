---
title: set_desired_size Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.rendering/svgimageoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Legt die gewünschte Breite und Höhe des Bildes fest.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| desired_width | int | gewünschte Breite in Pixeln|
| desired_height | int | gewünschte Höhe in Pixeln|
###  Bemerkungen

HINWEIS: Dieses Mitglied ist mittlerweile veraltet. Stattdessen
Bitte verwenden Sie [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/set_desired_size), indem Sie den Parameter keepAspectRatio auf „false“ setzen.
 Diese Eigenschaft wird 12 Monate später (ab Mai 2023) entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten, die Ihnen möglicherweise entstanden sind.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Legt die gewünschte Breite und Höhe des Bildes fest.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| desired_width | int | gewünschte Breite in Pixeln|
| desired_height | int | gewünschte Höhe in Pixeln|
| keep_aspect_ratio | bool | ob das Seitenverhältnis des Originalbilds beibehalten werden soll|
###  Bemerkungen

Die Breite und Höhe des Ausgabebildes in Pixeln wird nur auf der Grundlage von
die gewünschte Breite und Höhe einstellen.


Die [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) und [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
hat in diesem Fall keine Auswirkungen auf die Breite und Höhe des Ausgabebildes.


###  Siehe auch
* Modul [`aspose.cells.rendering`](../../)
* Klasse [`SvgImageOptions`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions)
