---
title: Hyperlink klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 840
url: /sv/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink klass
Kapslar in objektet som representerar en hyperlänk.



Typen Hyperlink avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [address](/cells/python-net/sv/aspose.cells/hyperlink/address) | Representerar adressen till en hyperlänk.|
| [text_to_display](/cells/python-net/sv/aspose.cells/hyperlink/text_to_display) | Representerar texten som ska visas för den angivna hyperlänken. Standardvärdet är adressen till hyperlänken.|
| [area](/cells/python-net/sv/aspose.cells/hyperlink/area) | Får utbudet av hyperlänkar.|
| [screen_tip](/cells/python-net/sv/aspose.cells/hyperlink/screen_tip) | Returnerar eller ställer in skärmtipstexten för den angivna hyperlänken.|
| [link_type](/cells/python-net/sv/aspose.cells/hyperlink/link_type) | Får länktypen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [delete](/cells/python-net/sv/aspose.cells/hyperlink/delete/#) |Tar bort denna hyperlänk|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Adding a hyperlink to a URL at "A1" cell
index = worksheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Getting a Hyperlink by index.
hyperlink = worksheet.hyperlinks[index]
# Setting display text of this hyperlink.
hyperlink.text_to_display = "Aspose"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Se även
* modul [`aspose.cells`](..)
