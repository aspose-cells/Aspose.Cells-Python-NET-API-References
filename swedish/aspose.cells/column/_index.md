---
title: Column klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 240
url: /sv/aspose.cells/column/
is_root: false
---
##  Column klass
Representerar en enda kolumn i ett kalkylblad.



Typen Column avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [index](/cells/python-net/sv/aspose.cells/column/index) | Hämtar indexet för den här kolumnen.|
| [width](/cells/python-net/sv/aspose.cells/column/width) | Hämtar och ställer in kolumnbredden i teckenenheter.|
| [group_level](/cells/python-net/sv/aspose.cells/column/group_level) | Hämtar kolumnens gruppnivå.|
| [is_hidden](/cells/python-net/sv/aspose.cells/column/is_hidden) | Anger om kolumnen är dold.|
| [has_custom_style](/cells/python-net/sv/aspose.cells/column/has_custom_style) | Anger om den här kolumnen har anpassade stilinställningar (som skiljer sig från standardinställningen som ärvs från arbetsboken).|
| [style](/cells/python-net/sv/aspose.cells/column/style) | Hämtar stilen för den här kolumnen.|
| [is_collapsed](/cells/python-net/sv/aspose.cells/column/is_collapsed) | om kolumnen är hopfälld|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`apply_style(self, style, flag)`](/cells/python-net/sv/aspose.cells/column/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för en hel kolumn.|
| [`get_style(self)`](/cells/python-net/sv/aspose.cells/column/get_style/#) | Hämtar stilen för den här kolumnen.|
| [`set_style(self, style)`](/cells/python-net/sv/aspose.cells/column/set_style/#aspose.cells.style) | Anger stilen för den här kolumnen.|



###  Exempel

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first Column
column = worksheet.cells.columns[0]
# Apply Style to first Column
column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Se även
* modul [`aspose.cells`](..)
