---
title: Border classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells/border/
is_root: false
---
##  Border classe
Encapsule l'objet qui représente la bordure de la cellule.



Le type Border expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [theme_color](/cells/python-net/fr/aspose.cells/border/theme_color) | Obtient et définit la couleur du thème de la bordure.|
| [color](/cells/python-net/fr/aspose.cells/border/color) | Obtient ou définit la couleur de la bordure.|
| [argb_color](/cells/python-net/fr/aspose.cells/border/argb_color) | Obtient et définit la couleur avec une valeur ARGB 32 bits.|
| [line_style](/cells/python-net/fr/aspose.cells/border/line_style) | Obtient ou définit le type de bordure de cellule.|



###  Exemple

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
# Set top border style and color
border = style.borders.get(BorderType.TOP_BORDER)
border.line_style = CellBorderType.MEDIUM
border.color = Color.red
cell.set_style(style)

```

###  Voir également
* module [`aspose.cells`](..)
