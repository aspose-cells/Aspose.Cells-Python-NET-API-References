---
title: set_two_color_gradient Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells.drawing/fillformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
Legt die angegebene Füllung auf einen zweifarbigen Farbverlauf fest.
Gilt nur für Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Eine Farbverlaufsfarbe.|
| color2 | aspose.pydrawing.Color | Zwei Farbverläufe.|
| style | [`GradientStyleType`](/cells/python-net/de/aspose.cells.drawing/gradientstyletype) | Farbverlaufsschattierungsstil.|
| variant | int | Die Verlaufsvariante. Kann einen Wert zwischen 1 und 4 annehmen und entspricht einer der vier Varianten auf der Registerkarte „Verlauf“ im Dialogfeld „Fülleffekte“. Wenn der Stil „GradientStyle.FromCenter“ lautet, kann das Argument „Variante“ nur 1 oder 2 sein.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Legt die angegebene Füllung auf einen zweifarbigen Farbverlauf fest.
Gilt nur für Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Eine Farbverlaufsfarbe.|
| transparency1 | float | Der Transparenzgrad der Farbe1 als Wert von 0,0 (undurchsichtig) bis 1,0 (klar).|
| color2 | aspose.pydrawing.Color | Zwei Farbverläufe.|
| transparency2 | float | Der Transparenzgrad der Farbe2 als Wert von 0,0 (undurchsichtig) bis 1,0 (klar).|
| style | [`GradientStyleType`](/cells/python-net/de/aspose.cells.drawing/gradientstyletype) | Farbverlaufsschattierungsstil.|
| variant | int | Die Verlaufsvariante. Kann einen Wert zwischen 1 und 4 annehmen und entspricht einer der vier Varianten auf der Registerkarte „Verlauf“ im Dialogfeld „Fülleffekte“. Wenn der Stil „GradientStyle.FromCenter“ lautet, kann das Argument „Variante“ nur 1 oder 2 sein.|



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`FillFormat`](/cells/python-net/de/aspose.cells.drawing/fillformat)
