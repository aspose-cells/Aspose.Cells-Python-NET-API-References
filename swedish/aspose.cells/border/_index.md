---
title: Border klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/border/
is_root: false
---
##  Border klass
Inkapslar objektet som representerar cellkanten.



Typen Border avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [theme_color](/cells/python-net/sv/aspose.cells/border/theme_color) | Hämtar och anger temafärgen för kantlinjen.|
| [color](/cells/python-net/sv/aspose.cells/border/color) | Hämtar eller anger färgen på kantlinjen.|
| [argb_color](/cells/python-net/sv/aspose.cells/border/argb_color) | Hämtar och ställer in färgen med ett 32-bitars ARGB-värde.|
| [line_style](/cells/python-net/sv/aspose.cells/border/line_style) | Hämtar eller anger cellkantlinjetypen.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
