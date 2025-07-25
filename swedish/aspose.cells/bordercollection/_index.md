---
title: BorderCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/bordercollection/
is_root: false
---
##  BorderCollection klass
Inkapslar en samling av [`Border`](/cells/python-net/sv/aspose.cells/border) objekt.



Typen BorderCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [diagonal_color](/cells/python-net/sv/aspose.cells/bordercollection/diagonal_color) | Hämtar eller ställer in färgen på diagonala linjer.|
| [diagonal_style](/cells/python-net/sv/aspose.cells/bordercollection/diagonal_style) | Hämtar eller ställer in stilen för diagonala linjer.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/sv/aspose.cells/bordercollection/get/#aspose.cells.bordertype) | Lägg till API for Python Via .Net. eftersom denna [BorderType borderType] inte stöds.|
| [`set_color(self, color)`](/cells/python-net/sv/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) | Anger färgen på alla ramar i samlingen.|
| [`set_style(self, style)`](/cells/python-net/sv/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) | Anger stilen för alla kantlinjer i samlingen.|



###  Exempel

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Visit Aspose!")
style = cell.get_style()
# Setting the line style of the top border
style.borders.get(BorderType.TOP_BORDER).line_style = CellBorderType.THICK
# Setting the color of the top border
style.borders.get(BorderType.TOP_BORDER).color = Color.black
# Setting the line style of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).line_style = CellBorderType.THICK
# Setting the color of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).color = Color.black
# Setting the line style of the left border
style.borders.get(BorderType.LEFT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the left border
style.borders.get(BorderType.LEFT_BORDER).color = Color.black
# Setting the line style of the right border
style.borders.get(BorderType.RIGHT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the right border
style.borders.get(BorderType.RIGHT_BORDER).color = Color.black
cell.set_style(style)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Border`](/cells/python-net/sv/aspose.cells/border)
