---
title: ColumnCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 250
url: /de/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection Klasse
Sammlung der [`Column`](/cells/python-net/de/aspose.cells/column) Objekte, die die einzelnen Spalten(einstellungen) in einem Arbeitsblatt darstellen.
Das Column-Objekt stellt lediglich die Einstellungen wie Spaltenbreite, Stile usw. für die gesamte Spalte dar,
hat nichts damit zu tun, dass es nicht leere Zellen (Daten) gibt oder diese nicht in der entsprechenden Spalte vorhanden sind.
Und die „Anzahl“ dieser Sammlung stellt nur die Anzahl der Spaltenobjekte dar, die in dieser Sammlung instanziiert wurden.
hat nichts damit zu tun, dass das Arbeitsblatt nicht leere Zellen (Daten) enthält oder nicht.



Der Typ ColumnCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/columncollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells/columncollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells/columncollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`get_by_index(self, index)`](/cells/python-net/de/aspose.cells/columncollection/get_by_index/#int) | Ruft das Spaltenobjekt über den Index ab.|
| [`get_column_by_index(self, index)`](/cells/python-net/de/aspose.cells/columncollection/get_column_by_index/#int) | Ruft das Objekt [`Column`](/cells/python-net/de/aspose.cells/column) anhand der Position in der Liste ab.|
| [`get(self, column_index)`](/cells/python-net/de/aspose.cells/columncollection/get/#int) | Fügen Sie API for Python über .Net hinzu.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Column`](/cells/python-net/de/aspose.cells/column)
