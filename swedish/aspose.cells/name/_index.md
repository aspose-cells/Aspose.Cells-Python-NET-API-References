---
title: Name klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1110
url: /sv/aspose.cells/name/
is_root: false
---
##  Name klass
Representerar ett definierat namn för ett cellintervall.



Typen Name avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [comment](/cells/python-net/sv/aspose.cells/name/comment) | Hämtar och ställer in kommentaren till namnet.<br/> Gäller endast Excel 2007 eller högre versioner.|
| [text](/cells/python-net/sv/aspose.cells/name/text) | Hämtar namntexten för objektet.|
| [full_text](/cells/python-net/sv/aspose.cells/name/full_text) | Hämtar namnet i fulltext för objektet med omfattningsinställningen.|
| [refers_to](/cells/python-net/sv/aspose.cells/name/refers_to) | Returnerar eller ställer in formeln som namnet är definierat för att referera till, som börjar med ett likhetstecken.|
| [r1c1_refers_to](/cells/python-net/sv/aspose.cells/name/r1c1_refers_to) | Hämtar eller ställer in en R1C1-referens för [`Name`](/cells/python-net/sv/aspose.cells/name).|
| [is_referred](/cells/python-net/sv/aspose.cells/name/is_referred) | Anger om detta namn refereras av andra formler.|
| [is_visible](/cells/python-net/sv/aspose.cells/name/is_visible) | Indikerar om namnet är synligt.|
| [sheet_index](/cells/python-net/sv/aspose.cells/name/sheet_index) | Indikerar att detta namn tillhör arbetsboken eller arbetsbladet.<br/> 0 = Globalt namn, annars indexera till ark (en-baserat)|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [get_refers_to](/cells/python-net/sv/aspose.cells/name/get_refers_to/#bool-bool) | Få referensen till detta namn.|
| [get_refers_to](/cells/python-net/sv/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Få referensen till detta namn baserat på specificerad cell.|
| [get_ranges](/cells/python-net/sv/aspose.cells/name/get_ranges/#) | Hämtar alla intervall som hänvisas till med detta namn.|
| [get_ranges](/cells/python-net/sv/aspose.cells/name/get_ranges/#bool) | Hämtar alla intervall som hänvisas till med detta namn.|
| [get_range](/cells/python-net/sv/aspose.cells/name/get_range/#) |Hämtar intervallet om detta namn hänvisar till ett intervall.|
| [get_range](/cells/python-net/sv/aspose.cells/name/get_range/#bool) | Hämtar intervallet om detta namn hänvisar till ett intervall|
| [get_range](/cells/python-net/sv/aspose.cells/name/get_range/#int-int-int) | Hämtar intervallet om detta namn hänvisar till ett intervall.<br/> Om referensen för detta namn inte är absolut kan intervallet vara annorlunda för olika celler.|
| [set_refers_to](/cells/python-net/sv/aspose.cells/name/set_refers_to/#str-bool-bool) | Ange referensen för detta namn.|
| [get_referred_areas](/cells/python-net/sv/aspose.cells/name/get_referred_areas/#bool) | Får alla referenser som hänvisas till med detta namn.|



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
