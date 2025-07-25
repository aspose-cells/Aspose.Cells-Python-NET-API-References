---
title: DataSorter Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 410
url: /de/aspose.cells/datasorter/
is_root: false
---
##  DataSorter Klasse
Zusammenfassende Beschreibung für DataSorter.



Der Typ DataSorter macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [keys](/cells/python-net/de/aspose.cells/datasorter/keys) | Ruft die Schlüsselliste des Datensortierers ab.|
| [has_headers](/cells/python-net/de/aspose.cells/datasorter/has_headers) | Gibt an, ob der Bereich Überschriften hat.|
| [key1](/cells/python-net/de/aspose.cells/datasorter/key1) | Stellt den ersten sortierten Spaltenindex dar (absolute Position, Spalte A ist 0, B ist 1, …).|
| [order1](/cells/python-net/de/aspose.cells/datasorter/order1) | Stellt die Sortierreihenfolge des ersten Schlüssels dar.|
| [key2](/cells/python-net/de/aspose.cells/datasorter/key2) | Stellt den zweiten sortierten Spaltenindex dar (absolute Position, Spalte A ist 0, B ist 1, ...).|
| [order2](/cells/python-net/de/aspose.cells/datasorter/order2) | Stellt die Sortierreihenfolge des zweiten Schlüssels dar.|
| [key3](/cells/python-net/de/aspose.cells/datasorter/key3) | Stellt den dritten sortierten Spaltenindex dar (absolute Position, Spalte A ist 0, B ist 1, ...).|
| [order3](/cells/python-net/de/aspose.cells/datasorter/order3) | Stellt die Sortierreihenfolge des dritten Schlüssels dar.|
| [sort_left_to_right](/cells/python-net/de/aspose.cells/datasorter/sort_left_to_right) |„True“ bedeutet, dass die Sortierausrichtung von links nach rechts erfolgt.<br/>„False“ bedeutet, dass die Sortierausrichtung von oben nach unten erfolgt.<br/> Der Standardwert ist „false“.|
| [case_sensitive](/cells/python-net/de/aspose.cells/datasorter/case_sensitive) | Ruft ab und legt fest, ob beim Vergleichen von Zeichenfolgen zwischen Groß- und Kleinschreibung unterschieden wird.|
| [sort_as_number](/cells/python-net/de/aspose.cells/datasorter/sort_as_number) | Gibt an, ob alles sortiert wird, was wie eine Zahl aussieht.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/de/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | Fügt sortierten Spaltenindex und Sortierreihenfolge hinzu.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/de/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | Fügt einen sortierten Spaltenindex und eine Sortierreihenfolge mit benutzerdefinierter Sortierliste hinzu.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/de/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | Fügt einen sortierten Spaltenindex und eine Sortierreihenfolge mit benutzerdefinierter Sortierliste hinzu.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/de/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | Fügt einen sortierten Spaltenindex und eine Sortierreihenfolge mit benutzerdefinierter Sortierliste hinzu.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/de/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | Sortiert die Daten des Bereichs.|
| [`sort(self, cells, area)`](/cells/python-net/de/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | Sortieren Sie die Daten des Bereichs.|
| [`sort(self)`](/cells/python-net/de/aspose.cells/datasorter/sort/#) | Sortieren Sie die Daten im Bereich.|
| [`clear(self)`](/cells/python-net/de/aspose.cells/datasorter/clear/#) | Alle Einstellungen löschen.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/de/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | Fügt einen Farbsortierschlüssel hinzu.|



###  Beispiel

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
