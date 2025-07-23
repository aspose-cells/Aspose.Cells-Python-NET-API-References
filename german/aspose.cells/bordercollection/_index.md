---
title: BorderCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells/bordercollection/
is_root: false
---
##  BorderCollection Klasse
Kapselt eine Sammlung von [`Border`](/cells/python-net/de/aspose.cells/border) Objekten.



Der Typ BorderCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [diagonal_color](/cells/python-net/de/aspose.cells/bordercollection/diagonal_color) | Ruft die Farbe diagonaler Linien ab oder legt sie fest.|
| [diagonal_style](/cells/python-net/de/aspose.cells/bordercollection/diagonal_style) | Ruft den Stil diagonaler Linien ab oder legt ihn fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/de/aspose.cells/bordercollection/get/#aspose.cells.bordertype) | Hinzufügen API for Python Via .Net.since this[BorderType borderType] is unsupported|
| [`set_color(self, color)`](/cells/python-net/de/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) | Legt die Farbe aller Rahmen in der Sammlung fest.|
| [`set_style(self, style)`](/cells/python-net/de/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) | Legt den Stil aller Rahmen der Sammlung fest.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Border`](/cells/python-net/de/aspose.cells/border)
