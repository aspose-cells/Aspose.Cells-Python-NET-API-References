---
title: Row Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1340
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
| [height](/cells/python-net/de/aspose.cells/row/height) | Ruft die Zeilenhöhe in der Einheit Punkte ab und legt sie fest.|
| [is_hidden](/cells/python-net/de/aspose.cells/row/is_hidden) | Gibt an, ob die Zeile ausgeblendet ist.|
| [index](/cells/python-net/de/aspose.cells/row/index) | Ruft den Index dieser Zeile ab.|
| [group_level](/cells/python-net/de/aspose.cells/row/group_level) | Ruft die Gruppenebene der Zeile ab.|
| [is_height_matched](/cells/python-net/de/aspose.cells/row/is_height_matched) | Gibt an, ob die Zeilenhöhe mit der aktuellen Standardschriftarteinstellung der Arbeitsmappe übereinstimmt.<br/>„True“ dieser Eigenschaft bedeutet auch, dass die Zeilenhöhe „automatisch“ ist, ohne dass vom Benutzer ein benutzerdefinierter Höhenwert festgelegt wird.|
| [has_custom_style](/cells/python-net/de/aspose.cells/row/has_custom_style) | Gibt an, ob diese Zeile über benutzerdefinierte Stileinstellungen verfügt (anders als die von der Arbeitsmappe geerbten Standardeinstellungen).|
| [first_cell](/cells/python-net/de/aspose.cells/row/first_cell) | Ruft das erste Zellobjekt in der Zeile ab.|
| [first_data_cell](/cells/python-net/de/aspose.cells/row/first_data_cell) | Ruft die erste nicht leere Zelle in der Zeile ab.|
| [last_cell](/cells/python-net/de/aspose.cells/row/last_cell) | Ruft das letzte Zellobjekt in der Zeile ab.|
| [last_data_cell](/cells/python-net/de/aspose.cells/row/last_data_cell) | Ruft die letzte nicht leere Zelle in der Zeile ab.|



Ruft die Zelle ab.
###  Indexer
| Name| Beschreibung|
| :- | :- |
| [index] | Der Spaltenindex|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [get_cell_by_index](/cells/python-net/de/aspose.cells/row/get_cell_by_index/#int) | Rufen Sie die Zelle nach einem bestimmten Index in der Zellsammlung dieser Zeile ab.|
| [get_enumerator](/cells/python-net/de/aspose.cells/row/get_enumerator/#bool-bool) | Ruft einen Enumerator ab, der Zellen durch diese Zeile iteriert.|
| [get_cell_or_null](/cells/python-net/de/aspose.cells/row/get_cell_or_null/#int) | Ruft die Zelle oder Null im spezifischen Index ab.|
| [get_style](/cells/python-net/de/aspose.cells/row/get_style/#) | Ruft den Stil dieser Zeile ab.|
| [set_style](/cells/python-net/de/aspose.cells/row/set_style/#aspose.cells.Style) | Legt den Stil dieser Zeile fest.|
| [copy_settings](/cells/python-net/de/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | Kopieren Sie die Einstellungen der Zeile, z. B. Stil, Höhe, Sichtbarkeit usw.|
| [apply_style](/cells/python-net/de/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Wendet Formate für eine ganze Zeile an.|
| [equals](/cells/python-net/de/aspose.cells/row/equals/#aspose.cells.Row) | Prüft, ob dieses Objekt auf dieselbe Zeile mit einem anderen Zeilenobjekt verweist.|



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
