---
title: FindOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 640
url: /de/aspose.cells/findoptions/
is_root: false
---
##  FindOptions Klasse
Stellt Suchoptionen dar.



Der Typ FindOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/findoptions/__init__/#) | Erstellt eine neue Instanz von FindOptions|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_case_sensitive](/cells/python-net/de/aspose.cells/findoptions/is_case_sensitive) | Gibt an, ob bei der gesuchten Zeichenfolge die Groß-/Kleinschreibung beachtet wird.|
| [case_sensitive](/cells/python-net/de/aspose.cells/findoptions/case_sensitive) | Gibt an, ob bei der gesuchten Zeichenfolge die Groß-/Kleinschreibung beachtet wird.|
| [look_at_type](/cells/python-net/de/aspose.cells/findoptions/look_at_type) | Schauen Sie sich den Typ an.|
| [is_range_set](/cells/python-net/de/aspose.cells/findoptions/is_range_set) | Gibt an, ob der gesuchte Bereich festgelegt ist.|
| [search_next](/cells/python-net/de/aspose.cells/findoptions/search_next) |Suchreihenfolge. True: Nächstes suchen. False: Vorheriges suchen.|
| [search_backward](/cells/python-net/de/aspose.cells/findoptions/search_backward) | Ob rückwärts nach Zellen gesucht werden soll.|
| [seach_order_by_rows](/cells/python-net/de/aspose.cells/findoptions/seach_order_by_rows) | Gibt an, ob die Suchreihenfolge nach Zeilen oder Spalten erfolgt.|
| [search_order_by_rows](/cells/python-net/de/aspose.cells/findoptions/search_order_by_rows) | Gibt an, ob die Suchreihenfolge nach Zeilen oder Spalten erfolgt.|
| [look_in_type](/cells/python-net/de/aspose.cells/findoptions/look_in_type) | Schauen Sie in der Schrift nach.|
| [regex_key](/cells/python-net/de/aspose.cells/findoptions/regex_key) | Gibt an, ob der gesuchte Schlüssel ein regulärer Ausdruck ist.<br/>Wenn wahr, wird der gesuchte Schlüssel als regulärer Ausdruck genommen und analysiert.<br/> Andernfalls wird der Schlüssel gemäß den Regeln in MS Excel analysiert.|
| [value_type_sensitive](/cells/python-net/de/aspose.cells/findoptions/value_type_sensitive) | Gibt an, ob der gesuchte Zellenwerttyp mit dem gesuchten Schlüssel identisch sein soll.|
| [style](/cells/python-net/de/aspose.cells/findoptions/style) | Das zu suchende Format.|
| [convert_numeric_data](/cells/python-net/de/aspose.cells/findoptions/convert_numeric_data) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der gesuchte Zeichenfolgenwert in numerische Daten konvertiert wird.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_range(self)`](/cells/python-net/de/aspose.cells/findoptions/get_range/#) | Ruft den durchsuchten Bereich ab und legt ihn fest.|
| [`set_range(self, ca)`](/cells/python-net/de/aspose.cells/findoptions/set_range/#aspose.cells.cellarea) | Legt den Suchbereich fest.|



###  Beispiel

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  Siehe auch
* Modul [`aspose.cells`](..)
