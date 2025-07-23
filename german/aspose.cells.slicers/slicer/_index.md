---
title: Slicer Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.slicers/slicer/
is_root: false
---
##  Slicer Klasse
zusammenfassende Beschreibung von Slicer Ansicht



Der Typ Slicer macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [title](/cells/python-net/de/aspose.cells.slicers/slicer/title) | Gibt den Titel des aktuellen Slicer-Objekts an.|
| [alternative_text](/cells/python-net/de/aspose.cells.slicers/slicer/alternative_text) | Gibt die beschreibende (alternative) Textzeichenfolge des Slicer-Objekts zurück oder legt sie fest.|
| [is_printable](/cells/python-net/de/aspose.cells.slicers/slicer/is_printable) | Gibt an, ob das Slicer-Objekt druckbar ist.|
| [is_locked](/cells/python-net/de/aspose.cells.slicers/slicer/is_locked) | Gibt an, ob die Slicerform gesperrt ist.|
| [placement](/cells/python-net/de/aspose.cells.slicers/slicer/placement) | Stellt die Art und Weise dar, wie das Zeichenobjekt mit den darunterliegenden Zellen verbunden ist.<br/> Die Eigenschaft steuert die Platzierung eines Objekts auf einem Arbeitsblatt.|
| [locked_aspect_ratio](/cells/python-net/de/aspose.cells.slicers/slicer/locked_aspect_ratio) | Gibt an, ob das Seitenverhältnis gesperrt werden soll.|
| [locked_position](/cells/python-net/de/aspose.cells.slicers/slicer/locked_position) |Gibt an, ob der angegebene Slicer mithilfe der Benutzeroberfläche verschoben oder in der Größe geändert werden kann.|
| [shape](/cells/python-net/de/aspose.cells.slicers/slicer/shape) | Gibt das Shape-Objekt zurück, das dem angegebenen Slicer zugeordnet ist. Schreibgeschützt.|
| [slicer_cache](/cells/python-net/de/aspose.cells.slicers/slicer/slicer_cache) | Gibt das mit dem Slicer verknüpfte SlicerCache-Objekt zurück. Schreibgeschützt.|
| [parent](/cells/python-net/de/aspose.cells.slicers/slicer/parent) | Gibt das Objekt [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet) zurück, das diesen Slicer enthält. Schreibgeschützt.|
| [style_type](/cells/python-net/de/aspose.cells.slicers/slicer/style_type) | Geben Sie den Typ des integrierten Slicer-Stils an<br/> der Standardtyp ist SlicerStyleLight1|
| [name](/cells/python-net/de/aspose.cells.slicers/slicer/name) | Gibt den Namen des angegebenen Slicers zurück oder setzt ihn|
| [caption](/cells/python-net/de/aspose.cells.slicers/slicer/caption) | Gibt die Beschriftung des angegebenen Slicers zurück oder legt sie fest.|
| [caption_visible](/cells/python-net/de/aspose.cells.slicers/slicer/caption_visible) | Gibt zurück oder legt fest, ob die Kopfzeile, die die Slicer-Beschriftung anzeigt, sichtbar ist<br/> der Standardwert ist true|
| [number_of_columns](/cells/python-net/de/aspose.cells.slicers/slicer/number_of_columns) | Gibt die Anzahl der Spalten im angegebenen Slicer zurück oder legt sie fest.|
| [left_pixel](/cells/python-net/de/aspose.cells.slicers/slicer/left_pixel) | Gibt den horizontalen Versatz der Slicer-Form von ihrer linken Spalte in Pixeln zurück oder legt ihn fest.|
| [top_pixel](/cells/python-net/de/aspose.cells.slicers/slicer/top_pixel) | Gibt den vertikalen Versatz der Slicer-Form von ihrer obersten Zeile in Pixeln zurück oder legt ihn fest.|
| [width](/cells/python-net/de/aspose.cells.slicers/slicer/width) | Gibt die Breite des angegebenen Slicers in Punkten zurück oder legt sie fest.|
| [width_pixel](/cells/python-net/de/aspose.cells.slicers/slicer/width_pixel) |Gibt die Breite des angegebenen Slicers in Pixeln zurück oder legt sie fest.|
| [height](/cells/python-net/de/aspose.cells.slicers/slicer/height) | Gibt die Höhe des angegebenen Slicers in Punkten zurück oder legt sie fest.|
| [height_pixel](/cells/python-net/de/aspose.cells.slicers/slicer/height_pixel) | Gibt die Höhe des angegebenen Slicers in Pixeln zurück oder legt sie fest.|
| [column_width_pixel](/cells/python-net/de/aspose.cells.slicers/slicer/column_width_pixel) | Ruft die Breite jeder Spalte im Slicer in Pixeln ab oder legt sie fest.|
| [column_width](/cells/python-net/de/aspose.cells.slicers/slicer/column_width) | Gibt die Breite jeder Spalte im Slicer in Punkten zurück oder legt sie fest.|
| [row_height_pixel](/cells/python-net/de/aspose.cells.slicers/slicer/row_height_pixel) | Gibt die Höhe jeder Zeile im angegebenen Slicer in Pixel zurück oder legt sie fest.|
| [row_height](/cells/python-net/de/aspose.cells.slicers/slicer/row_height) | Gibt die Höhe jeder Zeile im angegebenen Slicer in Punkten zurück oder legt sie fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_pivot_connection(self, pivot)`](/cells/python-net/de/aspose.cells.slicers/slicer/add_pivot_connection/#aspose.cells.pivot.pivottable) | Fügt eine PivotTable-Verbindung hinzu.|
| [`remove_pivot_connection(self, pivot)`](/cells/python-net/de/aspose.cells.slicers/slicer/remove_pivot_connection/#aspose.cells.pivot.pivottable) | Entfernt die PivotTable-Verbindung.|
| [`refresh(self)`](/cells/python-net/de/aspose.cells.slicers/slicer/refresh/#) | Aktualisieren des Slicers. In der Zwischenzeit werden relative PivotTables aktualisiert und berechnet.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
items = slicer.slicer_cache.slicer_cache_items
item = items[0]
item.selected = False
# do your business
book.save("out.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.slicers`](..)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
