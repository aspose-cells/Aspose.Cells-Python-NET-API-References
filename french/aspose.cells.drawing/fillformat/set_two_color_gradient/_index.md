---
title: méthode set_two_color_gradient
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells.drawing/fillformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
Définit le remplissage spécifié sur un dégradé à deux couleurs.
S'applique uniquement à Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Une couleur dégradée.|
| color2 | aspose.pydrawing.Color | Deux dégradés de couleurs.|
| style | [`GradientStyleType`](/cells/python-net/fr/aspose.cells.drawing/gradientstyletype) | Style d'ombrage dégradé.|
| variant | int | Variante du dégradé. Il peut s'agir d'une valeur comprise entre 1 et 4, correspondant à l'une des quatre variantes de l'onglet Dégradé de la boîte de dialogue Effets de remplissage. Si le style est GradientStyle.FromCenter, l'argument Variant ne peut être que 1 ou 2.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Définit le remplissage spécifié sur un dégradé à deux couleurs.
S'applique uniquement à Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Une couleur dégradée.|
| transparency1 | float | Le degré de transparence de la couleur 1 sous forme de valeur comprise entre 0,0 (opaque) et 1,0 (clair).|
| color2 | aspose.pydrawing.Color | Deux dégradés de couleurs.|
| transparency2 | float | Le degré de transparence de la couleur 2 sous forme de valeur comprise entre 0,0 (opaque) et 1,0 (clair).|
| style | [`GradientStyleType`](/cells/python-net/fr/aspose.cells.drawing/gradientstyletype) | Style d'ombrage dégradé.|
| variant | int | Variante du dégradé. Il peut s'agir d'une valeur comprise entre 1 et 4, correspondant à l'une des quatre variantes de l'onglet Dégradé de la boîte de dialogue Effets de remplissage. Si le style est GradientStyle.FromCenter, l'argument Variant ne peut être que 1 ou 2.|



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`FillFormat`](/cells/python-net/fr/aspose.cells.drawing/fillformat)
