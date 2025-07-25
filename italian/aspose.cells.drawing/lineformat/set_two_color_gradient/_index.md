---
title: Metodo set_two_color_gradient
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells.drawing/lineformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
Imposta il riempimento specificato su un gradiente a due colori.
Si applica solo a Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Un colore sfumato.|
| color2 | aspose.pydrawing.Color | Due colori sfumati.|
| style | [`GradientStyleType`](/cells/python-net/it/aspose.cells.drawing/gradientstyletype) | Stile di ombreggiatura sfumata.|
| variant | int | Variante della sfumatura. Può essere un valore compreso tra 1 e 4, corrispondente a una delle quattro varianti nella scheda Sfumatura della finestra di dialogo Effetti di riempimento. Se lo stile è GradientStyle.FromCenter, l'argomento Variante può essere solo 1 o 2.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Imposta il riempimento specificato su un gradiente a due colori.
Si applica solo a Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Un colore sfumato.|
| transparency1 | float | Grado di trasparenza del colore1, espresso come valore da 0,0 (opaco) a 1,0 (trasparente).|
| color2 | aspose.pydrawing.Color | Due colori sfumati.|
| transparency2 | float | Grado di trasparenza del colore2, espresso come valore da 0,0 (opaco) a 1,0 (trasparente).|
| style | [`GradientStyleType`](/cells/python-net/it/aspose.cells.drawing/gradientstyletype) | Stile di ombreggiatura sfumata.|
| variant | int | Variante della sfumatura. Può essere un valore compreso tra 1 e 4, corrispondente a una delle quattro varianti nella scheda Sfumatura della finestra di dialogo Effetti di riempimento. Se lo stile è GradientStyle.FromCenter, l'argomento Variante può essere solo 1 o 2.|



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`LineFormat`](/cells/python-net/it/aspose.cells.drawing/lineformat)
