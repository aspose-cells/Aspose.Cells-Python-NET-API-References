---
title: BorderCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/bordercollection/
is_root: false
---
##  BorderCollection classe
Incapsula una raccolta di [`Border`](/cells/python-net/it/aspose.cells/border) oggetti.



Il tipo BorderCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [diagonal_color](/cells/python-net/it/aspose.cells/bordercollection/diagonal_color) | Ottiene o imposta il colore delle linee diagonali.|
| [diagonal_style](/cells/python-net/it/aspose.cells/bordercollection/diagonal_style) | Ottiene o imposta lo stile delle linee diagonali.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/it/aspose.cells/bordercollection/get/#aspose.cells.bordertype) | Aggiungi API for Python tramite .Net poiché questo [BorderType borderType] non è supportato|
| [`set_color(self, color)`](/cells/python-net/it/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) | Imposta il colore di tutti i bordi nella raccolta.|
| [`set_style(self, style)`](/cells/python-net/it/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) | Imposta lo stile di tutti i bordi della raccolta.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Border`](/cells/python-net/it/aspose.cells/border)
