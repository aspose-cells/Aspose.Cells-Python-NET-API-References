---
title: Hyperlink Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 840
url: /de/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink Klasse
Kapselt das Objekt, das einen Hyperlink darstellt.



Der Typ Hyperlink macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [address](/cells/python-net/de/aspose.cells/hyperlink/address) | Stellt die Adresse eines Hyperlinks dar.|
| [text_to_display](/cells/python-net/de/aspose.cells/hyperlink/text_to_display) | Stellt den Text dar, der für den angegebenen Hyperlink angezeigt werden soll. Der Standardwert ist die Adresse des Hyperlinks.|
| [area](/cells/python-net/de/aspose.cells/hyperlink/area) | Ruft den Bereich des Hyperlinks ab.|
| [screen_tip](/cells/python-net/de/aspose.cells/hyperlink/screen_tip) | Gibt den QuickInfo-Text für den angegebenen Hyperlink zurück oder legt ihn fest.|
| [link_type](/cells/python-net/de/aspose.cells/hyperlink/link_type) | Ruft den Linktyp ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [delete](/cells/python-net/de/aspose.cells/hyperlink/delete/#) |Löscht diesen Hyperlink|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
