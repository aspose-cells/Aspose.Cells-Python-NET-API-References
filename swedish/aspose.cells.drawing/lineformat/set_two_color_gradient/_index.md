---
title: set_two_color_gradient metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells.drawing/lineformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
Ställer in den angivna fyllningen till en tvåfärgad övertoning.
Gäller endast för Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | En gradientfärg.|
| color2 | aspose.pydrawing.Color | Två gradientfärger.|
| style | [`GradientStyleType`](/cells/python-net/sv/aspose.cells.drawing/gradientstyletype) | Stil med gradientskuggning.|
| variant | int | Gradientvarianten. Kan vara ett värde från 1 till 4, motsvarande en av de fyra varianterna på fliken Gradient i dialogrutan Fyllningseffekter. Om stilen är GradientStyle.FromCenter kan variantargumentet bara vara 1 eller 2.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Ställer in den angivna fyllningen till en tvåfärgad övertoning.
Gäller endast för Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | En gradientfärg.|
| transparency1 | float | Färgens genomskinlighetsgrad1 som ett värde från 0,0 (ogenomskinlig) till 1,0 (klar).|
| color2 | aspose.pydrawing.Color | Två gradientfärger.|
| transparency2 | float | Färgens transparensgrad2 som ett värde från 0,0 (ogenomskinlig) till 1,0 (klar).|
| style | [`GradientStyleType`](/cells/python-net/sv/aspose.cells.drawing/gradientstyletype) | Stil med gradientskuggning.|
| variant | int | Gradientvarianten. Kan vara ett värde från 1 till 4, motsvarande en av de fyra varianterna på fliken Gradient i dialogrutan Fyllningseffekter. Om stilen är GradientStyle.FromCenter kan variantargumentet bara vara 1 eller 2.|



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`LineFormat`](/cells/python-net/sv/aspose.cells.drawing/lineformat)
