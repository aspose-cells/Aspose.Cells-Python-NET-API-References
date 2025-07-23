---
title: Border Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/border/
is_root: false
---
##  Border Klasse
Kapselt das Objekt ein, das den Zellrand darstellt.



Der Typ Border macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [theme_color](/cells/python-net/de/aspose.cells/border/theme_color) | Ruft die Designfarbe des Rahmens ab und legt sie fest.|
| [color](/cells/python-net/de/aspose.cells/border/color) | Ruft die Farbe des Rahmens ab oder legt sie fest.|
| [argb_color](/cells/python-net/de/aspose.cells/border/argb_color) | Ruft die Farbe mit einem 32-Bit-ARGB-Wert ab und legt sie fest.|
| [line_style](/cells/python-net/de/aspose.cells/border/line_style) | Ruft den Zellenrahmentyp ab oder legt ihn fest.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
