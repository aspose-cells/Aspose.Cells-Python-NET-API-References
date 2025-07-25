---
title: Row Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1230
url: /de/aspose.cells/row/
is_root: false
---
##  Row Klasse
Stellt eine einzelne Zeile in einem Arbeitsblatt dar.



Der Typ Row macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_blank](/cells/python-net/de/aspose.cells/row/is_blank) | Gibt an, ob die Zeile Daten enthält|
| [is_collapsed](/cells/python-net/de/aspose.cells/row/is_collapsed) | ob die Zeile reduziert ist|
| [height](/cells/python-net/de/aspose.cells/row/height) | Ruft die Zeilenhöhe in der Einheit „Punkte“ ab und legt sie fest.|
| [is_hidden](/cells/python-net/de/aspose.cells/row/is_hidden) | Gibt an, ob die Zeile ausgeblendet ist.|
| [index](/cells/python-net/de/aspose.cells/row/index) | Ruft den Index dieser Zeile ab.|
| [group_level](/cells/python-net/de/aspose.cells/row/group_level) | Ruft die Gruppierungsebene der Zeile ab.|
| [is_height_matched](/cells/python-net/de/aspose.cells/row/is_height_matched) | Gibt an, ob die Zeilenhöhe der aktuellen Standardschriftarteinstellung der Arbeitsmappe entspricht.<br/> Der Wert „True“ dieser Eigenschaft bedeutet auch, dass die Zeilenhöhe „automatisch“ ist, ohne dass der Benutzer einen benutzerdefinierten Höhenwert festlegen muss.|
| [has_custom_style](/cells/python-net/de/aspose.cells/row/has_custom_style) | Gibt an, ob diese Zeile benutzerdefinierte Stileinstellungen hat (anders als die aus der Arbeitsmappe übernommenen Standardeinstellungen).|
| [first_cell](/cells/python-net/de/aspose.cells/row/first_cell) | Ruft das erste Zellenobjekt in der Zeile ab.|
| [first_data_cell](/cells/python-net/de/aspose.cells/row/first_data_cell) |Ruft die erste nicht leere Zelle in der Zeile ab.|
| [last_cell](/cells/python-net/de/aspose.cells/row/last_cell) | Ruft das letzte Zellenobjekt in der Zeile ab.|
| [last_data_cell](/cells/python-net/de/aspose.cells/row/last_data_cell) | Ruft die letzte nicht leere Zelle in der Zeile ab.|



Ruft die Zelle ab.
###  Indexer
| Name| Beschreibung|
| :- | :- |
| [index] | Der Spaltenindex|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_cell_by_index(self, index)`](/cells/python-net/de/aspose.cells/row/get_cell_by_index/#int) | Holen Sie sich die Zelle nach einem bestimmten Index in der Zellensammlung dieser Zeile.|
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/de/aspose.cells/row/get_enumerator/#bool-bool) | Ruft einen Enumerator ab, der die Zellen dieser Zeile durchläuft.|
| [`get_cell_or_null(self, column)`](/cells/python-net/de/aspose.cells/row/get_cell_or_null/#int) | Ruft die Zelle oder Null im spezifischen Index ab.|
| [`get_style(self)`](/cells/python-net/de/aspose.cells/row/get_style/#) | Ruft den Stil dieser Zeile ab.|
| [`set_style(self, style)`](/cells/python-net/de/aspose.cells/row/set_style/#aspose.cells.style) | Legt den Stil dieser Zeile fest.|
| [`copy_settings(self, source, check_style)`](/cells/python-net/de/aspose.cells/row/copy_settings/#aspose.cells.row-bool) | Kopieren Sie die Zeileneinstellungen, z. B. Stil, Höhe, Sichtbarkeit usw.|
| [`apply_style(self, style, flag)`](/cells/python-net/de/aspose.cells/row/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Wendet Formate für eine ganze Zeile an.|
| [`equals(self, row)`](/cells/python-net/de/aspose.cells/row/equals/#aspose.cells.row) | Überprüft, ob dieses Objekt auf dieselbe Zeile wie ein anderes Zeilenobjekt verweist.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
