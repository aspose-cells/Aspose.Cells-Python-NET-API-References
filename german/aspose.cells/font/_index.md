---
title: Font Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 660
url: /de/aspose.cells/font/
is_root: false
---
##  Font Klasse
Kapselt das in einer Tabelle verwendete Schriftartobjekt ein.



Der Typ Font macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [charset](/cells/python-net/de/aspose.cells/font/charset) | Stellt den Zeichensatz dar.|
| [is_italic](/cells/python-net/de/aspose.cells/font/is_italic) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart kursiv ist.|
| [is_bold](/cells/python-net/de/aspose.cells/font/is_bold) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart fett ist.|
| [caps_type](/cells/python-net/de/aspose.cells/font/caps_type) | Ruft den Texttyp „Großbuchstaben“ ab und legt ihn fest.|
| [strike_type](/cells/python-net/de/aspose.cells/font/strike_type) | Ruft den Durchstreichungstyp des Textes ab.|
| [is_strikeout](/cells/python-net/de/aspose.cells/font/is_strikeout) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart einfach durchgestrichen ist.|
| [script_offset](/cells/python-net/de/aspose.cells/font/script_offset) | Ruft den Skript-Offset in Prozent ab und legt ihn fest.|
| [is_superscript](/cells/python-net/de/aspose.cells/font/is_superscript) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart hochgestellt ist.|
| [is_subscript](/cells/python-net/de/aspose.cells/font/is_subscript) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart tiefgestellt ist.|
| [underline](/cells/python-net/de/aspose.cells/font/underline) | Ruft den Unterstreichungstyp der Schriftart ab oder legt ihn fest.|
| [name](/cells/python-net/de/aspose.cells/font/name) | Ruft den Namen von [`Font`](/cells/python-net/de/aspose.cells/font) ab oder legt ihn fest.|
| [double_size](/cells/python-net/de/aspose.cells/font/double_size) | Ruft die doppelte Schriftgröße ab und legt sie fest.|
| [size](/cells/python-net/de/aspose.cells/font/size) | Ruft die Größe der Schriftart ab oder legt sie fest.|
| [theme_color](/cells/python-net/de/aspose.cells/font/theme_color) | Ruft die Designfarbe ab und legt sie fest.|
| [color](/cells/python-net/de/aspose.cells/font/color) | Ruft die Farbe der Schriftart ab oder legt sie fest.|
| [argb_color](/cells/python-net/de/aspose.cells/font/argb_color) | Ruft die Farbe mit einem 32-Bit-ARGB-Wert ab und legt sie fest.|
| [is_normalize_heights](/cells/python-net/de/aspose.cells/font/is_normalize_heights) | Gibt an, ob die Normalisierung der Höhe auf den Textlauf angewendet werden soll.|
| [scheme_type](/cells/python-net/de/aspose.cells/font/scheme_type) |Ruft den Schematyp der Schriftart ab und legt ihn fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`equals(self, font)`](/cells/python-net/de/aspose.cells/font/equals/#aspose.cells.font) | Überprüft, ob zwei Schriftarten gleich sind.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Hello Aspose!")
font = cell.get_style().font
# Setting the font name to "Times New Roman"
font.name = "Times New Roman"
# Setting font size to 14
font.size = 14
# setting font color as Red
font.color = Color.red
# Saving the Excel file
workbook.save(r"dest.xls")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Font`](/cells/python-net/de/aspose.cells/font)
