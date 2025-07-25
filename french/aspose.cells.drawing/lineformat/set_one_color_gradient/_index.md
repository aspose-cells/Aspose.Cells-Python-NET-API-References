---
title: méthode set_one_color_gradient
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.drawing/lineformat/set_one_color_gradient/
is_root: false
---
##  set_one_color_gradient(self, color, degree, style, variant) {#aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Définit le remplissage spécifié sur un dégradé d'une couleur.
S'applique uniquement à Excel 2007.



```python

def set_one_color_gradient(self, color, degree, style, variant):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| color | aspose.pydrawing.Color | Une couleur dégradée.|
| degree | float | Le degré de dégradé. Il peut être compris entre 0,0 (foncé) et 1,0 (clair).|
| style | [`GradientStyleType`](/cells/python-net/fr/aspose.cells.drawing/gradientstyletype) | Style d'ombrage dégradé.|
| variant | int | Variante du dégradé. Il peut s'agir d'une valeur comprise entre 1 et 4, correspondant à l'une des quatre variantes de l'onglet Dégradé de la boîte de dialogue Effets de remplissage. Si le style est GradientStyle.FromCenter, l'argument Variant ne peut être que 1 ou 2.|



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`LineFormat`](/cells/python-net/fr/aspose.cells.drawing/lineformat)
