---
title: FontSetting clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 700
url: /es/aspose.cells/fontsetting/
is_root: false
---
##  FontSetting clase
Representa una variedad de caracteres dentro del texto de la celda.



El tipo FontSetting expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/fontsetting/__init__/#int-int-aspose.cells.WorksheetCollection) |  |


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [type](/cells/python-net/es/aspose.cells/fontsetting/type) | Obtiene el tipo de nodo de texto.|
| [start_index](/cells/python-net/es/aspose.cells/fontsetting/start_index) |Obtiene el índice inicial de los caracteres.|
| [length](/cells/python-net/es/aspose.cells/fontsetting/length) | Obtiene la longitud de los caracteres.|
| [font](/cells/python-net/es/aspose.cells/fontsetting/font) | Devuelve la fuente de este objeto.|
| [text_options](/cells/python-net/es/aspose.cells/fontsetting/text_options) | Devuelve las opciones de texto.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_word_art_style](/cells/python-net/es/aspose.cells/fontsetting/set_word_art_style/#aspose.cells.drawing.PresetWordArtStyle) | Establece el estilo preestablecido de WordArt.|



###  Ejemplo

```python
from aspose.cells import Workbook
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
# getting charactor
charactor = cell.characters(6, 7)
# Setting the font of selected characters to bold
charactor.font.is_bold = True
# Setting the font color of selected characters to blue
charactor.font.color = Color.blue
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
