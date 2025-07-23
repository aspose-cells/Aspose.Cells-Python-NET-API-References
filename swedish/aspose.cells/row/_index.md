---
title: Row klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1230
url: /sv/aspose.cells/row/
is_root: false
---
##  Row klass
Representerar en enda rad i ett kalkylblad.



Typen Row avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_blank](/cells/python-net/sv/aspose.cells/row/is_blank) | Anger om raden innehåller data|
| [is_collapsed](/cells/python-net/sv/aspose.cells/row/is_collapsed) | om raden är hopfälld|
| [height](/cells/python-net/sv/aspose.cells/row/height) | Hämtar och ställer in radhöjden i enheten punkter.|
| [is_hidden](/cells/python-net/sv/aspose.cells/row/is_hidden) | Anger om raden är dold.|
| [index](/cells/python-net/sv/aspose.cells/row/index) | Hämtar indexet för den här raden.|
| [group_level](/cells/python-net/sv/aspose.cells/row/group_level) | Hämtar gruppnivån för raden.|
| [is_height_matched](/cells/python-net/sv/aspose.cells/row/is_height_matched) | Anger om radhöjden matchar arbetsbokens aktuella standardteckensnittsinställning.<br/> Sant för den här egenskapen anger också att radhöjden är "automatisk" utan ett anpassat höjdvärde som anges av användaren.|
| [has_custom_style](/cells/python-net/sv/aspose.cells/row/has_custom_style) | Anger om den här raden har anpassade formatinställningar (som skiljer sig från standardinställningen som ärvs från arbetsboken).|
| [first_cell](/cells/python-net/sv/aspose.cells/row/first_cell) | Hämtar det första cellobjektet i raden.|
| [first_data_cell](/cells/python-net/sv/aspose.cells/row/first_data_cell) |Hämtar den första cellen i raden som inte är tom.|
| [last_cell](/cells/python-net/sv/aspose.cells/row/last_cell) | Hämtar det sista cellobjektet i raden.|
| [last_data_cell](/cells/python-net/sv/aspose.cells/row/last_data_cell) | Hämtar den sista icke-tomma cellen i raden.|



Hämtar cellen.
###  Indexerare
| Namn| Beskrivning|
| :- | :- |
| [index] | Kolumnindexet|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_cell_by_index(self, index)`](/cells/python-net/sv/aspose.cells/row/get_cell_by_index/#int) | Hämta cellen efter specifikt index i cellsamlingen för den här raden.|
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/sv/aspose.cells/row/get_enumerator/#bool-bool) | Hämtar en uppräknare som itererar celler genom den här raden.|
| [`get_cell_or_null(self, column)`](/cells/python-net/sv/aspose.cells/row/get_cell_or_null/#int) | Hämtar cellen eller nullvärdet i det specifika indexet.|
| [`get_style(self)`](/cells/python-net/sv/aspose.cells/row/get_style/#) | Hämtar stilen för den här raden.|
| [`set_style(self, style)`](/cells/python-net/sv/aspose.cells/row/set_style/#aspose.cells.style) | Anger stilen för den här raden.|
| [`copy_settings(self, source, check_style)`](/cells/python-net/sv/aspose.cells/row/copy_settings/#aspose.cells.row-bool) | Kopiera inställningar för raden, såsom stil, höjd, synlighet, ...etc.|
| [`apply_style(self, style, flag)`](/cells/python-net/sv/aspose.cells/row/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för en hel rad.|
| [`equals(self, row)`](/cells/python-net/sv/aspose.cells/row/equals/#aspose.cells.row) | Kontrollerar om det här objektet refererar till samma rad som ett annat radobjekt.|



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
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Se även
* modul [`aspose.cells`](..)
