---
title: Name klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1000
url: /sv/aspose.cells/name/
is_root: false
---
##  Name klass
Representerar ett definierat namn för ett cellområde.



Typen Name avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [comment](/cells/python-net/sv/aspose.cells/name/comment) | Hämtar och anger kommentaren till namnet.<br/> Gäller endast för Excel 2007 eller senare versioner.|
| [text](/cells/python-net/sv/aspose.cells/name/text) | Hämtar objektets namntext.|
| [full_text](/cells/python-net/sv/aspose.cells/name/full_text) | Hämtar objektets namn i sin helhet med omfångsinställningen.|
| [refers_to](/cells/python-net/sv/aspose.cells/name/refers_to) | Returnerar eller anger formeln som namnet är definierat att referera till, med början med ett likhetstecken.|
| [r1c1_refers_to](/cells/python-net/sv/aspose.cells/name/r1c1_refers_to) |Hämtar eller ställer in en R1C1-referens för [`Name`](/cells/python-net/sv/aspose.cells/name).|
| [is_referred](/cells/python-net/sv/aspose.cells/name/is_referred) | Anger om detta namn hänvisas till av andra formler.|
| [is_visible](/cells/python-net/sv/aspose.cells/name/is_visible) | Anger om namnet är synligt.|
| [sheet_index](/cells/python-net/sv/aspose.cells/name/sheet_index) | Indikerar att det här namnet tillhör arbetsboken eller arbetsbladet.<br/> 0 = Globalt namn, annars index till ark (en-baserat)|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_refers_to(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/name/get_refers_to/#bool-bool) | Hämta referensen till detta namn.|
| [`get_refers_to(self, is_r1c1, is_local, row, column)`](/cells/python-net/sv/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Hämta referensen för detta namn baserat på den angivna cellen.|
| [`get_ranges(self)`](/cells/python-net/sv/aspose.cells/name/get_ranges/#) | Hämtar alla intervall som refereras med detta namn.|
| [`get_ranges(self, recalculate)`](/cells/python-net/sv/aspose.cells/name/get_ranges/#bool) | Hämtar alla intervall som refereras med detta namn.|
| [`get_range(self)`](/cells/python-net/sv/aspose.cells/name/get_range/#) | Hämtar intervallet om namnet refererar till ett intervall.|
| [`get_range(self, recalculate)`](/cells/python-net/sv/aspose.cells/name/get_range/#bool) | Hämtar intervallet om detta namn refererar till ett intervall|
| [`get_range(self, sheet_index, row, column)`](/cells/python-net/sv/aspose.cells/name/get_range/#int-int-int) | Hämtar intervallet om namnet refererar till ett intervall.<br/> Om referensen till detta namn inte är absolut kan intervallet vara olika för olika celler.|
| [`set_refers_to(self, refers_to, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/name/set_refers_to/#str-bool-bool) | Ange referensen för detta namn.|
| [`get_referred_areas(self, recalculate)`](/cells/python-net/sv/aspose.cells/name/get_referred_areas/#bool) | Hämtar alla referenser som refereras med detta namn.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating a named range
range = worksheet.cells.create_range("B4", "G14")
# Setting the name of the named range
range.name = "TestRange"
# Saving the modified Excel file in default (that is Excel 2000) format
workbook.save("output.xls")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Name`](/cells/python-net/sv/aspose.cells/name)
