---
title: Name Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1000
url: /de/aspose.cells/name/
is_root: false
---
##  Name Klasse
Stellt einen definierten Namen für einen Zellbereich dar.



Der Typ Name macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [comment](/cells/python-net/de/aspose.cells/name/comment) | Ruft den Kommentar des Namens ab und legt ihn fest.<br/> Gilt nur für Excel 2007 oder höhere Versionen.|
| [text](/cells/python-net/de/aspose.cells/name/text) | Ruft den Namenstext des Objekts ab.|
| [full_text](/cells/python-net/de/aspose.cells/name/full_text) | Ruft den vollständigen Text des Objektnamens mit der Bereichseinstellung ab.|
| [refers_to](/cells/python-net/de/aspose.cells/name/refers_to) | Gibt die Formel zurück oder legt sie fest, auf die sich der Name laut Definition bezieht, beginnend mit einem Gleichheitszeichen.|
| [r1c1_refers_to](/cells/python-net/de/aspose.cells/name/r1c1_refers_to) |Ruft eine R1C1-Referenz von [`Name`](/cells/python-net/de/aspose.cells/name) ab oder legt diese fest.|
| [is_referred](/cells/python-net/de/aspose.cells/name/is_referred) | Gibt an, ob auf diesen Namen in anderen Formeln verwiesen wird.|
| [is_visible](/cells/python-net/de/aspose.cells/name/is_visible) | Gibt an, ob der Name sichtbar ist.|
| [sheet_index](/cells/python-net/de/aspose.cells/name/sheet_index) | Gibt an, dass dieser Name zur Arbeitsmappe oder zum Arbeitsblatt gehört.<br/> 0 = Globaler Name, sonst Index zum Blatt (einsbasiert)|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_refers_to(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/name/get_refers_to/#bool-bool) | Holen Sie sich die Referenz dieses Namens.|
| [`get_refers_to(self, is_r1c1, is_local, row, column)`](/cells/python-net/de/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Holen Sie sich die Referenz dieses Namens basierend auf der angegebenen Zelle.|
| [`get_ranges(self)`](/cells/python-net/de/aspose.cells/name/get_ranges/#) | Ruft alle Bereiche ab, auf die dieser Name verweist.|
| [`get_ranges(self, recalculate)`](/cells/python-net/de/aspose.cells/name/get_ranges/#bool) | Ruft alle Bereiche ab, auf die dieser Name verweist.|
| [`get_range(self)`](/cells/python-net/de/aspose.cells/name/get_range/#) | Ruft den Bereich ab, wenn dieser Name auf einen Bereich verweist.|
| [`get_range(self, recalculate)`](/cells/python-net/de/aspose.cells/name/get_range/#bool) | Ruft den Bereich ab, wenn dieser Name auf einen Bereich verweist|
| [`get_range(self, sheet_index, row, column)`](/cells/python-net/de/aspose.cells/name/get_range/#int-int-int) | Ruft den Bereich ab, wenn dieser Name auf einen Bereich verweist.<br/> Wenn der Bezug dieses Namens nicht absolut ist, kann der Bereich für verschiedene Zellen unterschiedlich sein.|
| [`set_refers_to(self, refers_to, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/name/set_refers_to/#str-bool-bool) | Legen Sie die Referenz dieses Namens fest.|
| [`get_referred_areas(self, recalculate)`](/cells/python-net/de/aspose.cells/name/get_referred_areas/#bool) | Ruft alle Referenzen ab, auf die dieser Name verweist.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Name`](/cells/python-net/de/aspose.cells/name)
