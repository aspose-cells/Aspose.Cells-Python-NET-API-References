---
title: Border classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells/border/
is_root: false
---
##  Border classe
Incapsula l'oggetto che rappresenta il bordo della cella.



Il tipo Border espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [theme_color](/cells/python-net/it/aspose.cells/border/theme_color) | Ottiene e imposta il colore del tema del bordo.|
| [color](/cells/python-net/it/aspose.cells/border/color) | Ottiene o imposta il colore del bordo.|
| [argb_color](/cells/python-net/it/aspose.cells/border/argb_color) | Ottiene e imposta il colore con un valore ARGB a 32 bit.|
| [line_style](/cells/python-net/it/aspose.cells/border/line_style) | Ottiene o imposta il tipo di bordo della cella.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells`](..)
