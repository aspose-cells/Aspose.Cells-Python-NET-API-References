---
title: Range Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1180
url: /de/aspose.cells/range/
is_root: false
---
##  Range Klasse
Kapselt das Objekt ein, das einen Zellbereich in einer Kalkulationstabelle darstellt.



Der Typ Range macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [current_region](/cells/python-net/de/aspose.cells/range/current_region) | Gibt ein Range-Objekt zurück, das die aktuelle Region darstellt.<br/> Die aktuelle Region ist ein Bereich, der durch eine beliebige Kombination aus leeren Zeilen und leeren Spalten begrenzt ist.|
| [hyperlinks](/cells/python-net/de/aspose.cells/range/hyperlinks) | Ruft alle Hyperlinks im Bereich ab.|
| [row_count](/cells/python-net/de/aspose.cells/range/row_count) | Ruft die Anzahl der Zeilen im Bereich ab.|
| [column_count](/cells/python-net/de/aspose.cells/range/column_count) | Ruft die Anzahl der Spalten im Bereich ab.|
| [name](/cells/python-net/de/aspose.cells/range/name) | Ruft den Namen des Bereichs ab oder legt ihn fest.|
| [refers_to](/cells/python-net/de/aspose.cells/range/refers_to) | Ruft den Bereich ab, auf den sich der Bereich bezieht.|
| [address](/cells/python-net/de/aspose.cells/range/address) | Ruft die Adresse des Bereichs ab.|
| [left](/cells/python-net/de/aspose.cells/range/left) | Ruft den Abstand in Punkten vom linken Rand der Spalte A zum linken Rand des Bereichs ab.|
| [top](/cells/python-net/de/aspose.cells/range/top) | Ruft den Abstand in Punkten vom oberen Rand der Zeile 1 zum oberen Rand des Bereichs ab.|
| [width](/cells/python-net/de/aspose.cells/range/width) | Ruft die Breite eines Bereichs in Punkten ab.|
| [height](/cells/python-net/de/aspose.cells/range/height) | Ruft die Breite eines Bereichs in Punkten ab.|
| [first_row](/cells/python-net/de/aspose.cells/range/first_row) | Ruft den Index der ersten Zeile des Bereichs ab.|
| [first_column](/cells/python-net/de/aspose.cells/range/first_column) | Ruft den Index der ersten Spalte des Bereichs ab.|
| [value](/cells/python-net/de/aspose.cells/range/value) | Ruft den Wert des Bereichs ab und legt ihn fest.|
| [column_width](/cells/python-net/de/aspose.cells/range/column_width) | Setzt oder ruft die Spaltenbreite dieses Bereichs ab|
| [row_height](/cells/python-net/de/aspose.cells/range/row_height) | Setzt oder ruft die Höhe der Zeilen in diesem Bereich ab|
| [entire_column](/cells/python-net/de/aspose.cells/range/entire_column) |Ruft ein Range-Objekt ab, das die gesamte Spalte (oder Spalten) darstellt, die den angegebenen Bereich enthält.|
| [entire_row](/cells/python-net/de/aspose.cells/range/entire_row) | Ruft ein Range-Objekt ab, das die gesamte Zeile (oder Zeilen) darstellt, die den angegebenen Bereich enthält.|
| [worksheet](/cells/python-net/de/aspose.cells/range/worksheet) | Ruft das [`Range.worksheet`](/cells/python-net/de/aspose.cells/range#worksheet)-Objekt ab, das diesen Bereich enthält.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/de/aspose.cells/range/auto_fill/#aspose.cells.range) | Zielbereich automatisch ausfüllen.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/de/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Zielbereich automatisch ausfüllen.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/de/aspose.cells/range/set_style/#aspose.cells.style-bool) | Wenden Sie den Zellenstil an.|
| [`set_style(self, style)`](/cells/python-net/de/aspose.cells/range/set_style/#aspose.cells.style) | Legt den Stil des Bereichs fest.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/de/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Legt die Umrisse um einen Zellbereich mit demselben Rahmenstil und derselben Farbe fest.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/de/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Legt die Umrisse um einen Zellbereich mit demselben Rahmenstil und derselben Farbe fest.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/de/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Legt Linienränder um einen Zellbereich fest.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/de/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Legt einen Rahmen um einen Zellbereich fest.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/de/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Legt einen Rahmen um einen Zellbereich fest.|
| [`copy(self, range, options)`](/cells/python-net/de/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Kopieren des Bereichs mit den Optionen zum Einfügen von Inhalten.|
| [`copy(self, range)`](/cells/python-net/de/aspose.cells/range/copy/#aspose.cells.range) | Kopiert Daten (einschließlich Formeln), Formatierungen, Zeichenobjekte usw. aus einem Quellbereich.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/de/aspose.cells/range/add_hyperlink/#str-str-str) | Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.|
| [`is_intersect(self, range)`](/cells/python-net/de/aspose.cells/range/is_intersect/#aspose.cells.range) | Gibt an, ob der Bereich eine Schnittmenge ist.|
| [`intersect(self, range)`](/cells/python-net/de/aspose.cells/range/intersect/#aspose.cells.range) | Gibt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt zurück, das die rechteckige Schnittmenge zweier Bereiche darstellt.|
| [`union_rang(self, range)`](/cells/python-net/de/aspose.cells/range/union_rang/#aspose.cells.range) | Gibt das Vereinigungsergebnis zweier Bereiche zurück.|
| [`union_ranges(self, ranges)`](/cells/python-net/de/aspose.cells/range/union_ranges/#list) | Gibt das Vereinigungsergebnis zweier Bereiche zurück.|
| [`union(self, range)`](/cells/python-net/de/aspose.cells/range/union/#aspose.cells.range) | Gibt die Vereinigungsmenge zweier Bereiche zurück.|
| [`is_blank(self)`](/cells/python-net/de/aspose.cells/range/is_blank/#) | Gibt an, ob der Bereich Werte enthält.|
| [`merge(self)`](/cells/python-net/de/aspose.cells/range/merge/#) |Kombiniert einen Zellbereich zu einer einzigen Zelle.|
| [`un_merge(self)`](/cells/python-net/de/aspose.cells/range/un_merge/#) | Hebt die Verbindung zusammengeführter Zellen dieses Bereichs auf.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/de/aspose.cells/range/put_value/#str-bool-bool) | Setzt einen Wert in den Bereich. Gegebenenfalls wird der Wert in einen anderen Datentyp konvertiert und das Zahlenformat der Zelle wird zurückgesetzt.|
| [`apply_style(self, style, flag)`](/cells/python-net/de/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Wendet Formate für einen ganzen Bereich an.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/de/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Innerhalb der Grenzen des Bereichs festlegen.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/de/aspose.cells/range/move_to/#int-int) | Verschiebt den aktuellen Bereich in den Zielbereich.|
| [`copy_data(self, range)`](/cells/python-net/de/aspose.cells/range/copy_data/#aspose.cells.range) | Kopiert Zellendaten (einschließlich Formeln) aus einem Quellbereich.|
| [`copy_value(self, range)`](/cells/python-net/de/aspose.cells/range/copy_value/#aspose.cells.range) | Kopiert Zellenwerte aus einem Quellbereich.|
| [`copy_style(self, range)`](/cells/python-net/de/aspose.cells/range/copy_style/#aspose.cells.range) | Kopiert Stileinstellungen aus einem Quellbereich.|
| [`transpose(self)`](/cells/python-net/de/aspose.cells/range/transpose/#) | Transponieren (rotieren) Sie Daten von Zeilen in Spalten oder umgekehrt.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/de/aspose.cells/range/get/#int-int) | Add API for Python Via .Net.since this[int, int] wird nicht unterstützt|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/de/aspose.cells/range/get_cell_or_null/#int-int) | Ruft [`Cell`](/cells/python-net/de/aspose.cells/cell) Objekte oder null in diesem Bereich ab.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/de/aspose.cells/range/get_offset/#int-int) | Ruft den Bereich [`Range`](/cells/python-net/de/aspose.cells/range) nach Offset ab.|
| [`to_image(self, options)`](/cells/python-net/de/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Konvertiert den Bereich in ein Bild.|
| [`to_json(self, options)`](/cells/python-net/de/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Konvertieren Sie den Bereich in den Wert JSON.|
| [`to_html(self, save_options)`](/cells/python-net/de/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Konvertieren Sie den Bereich in HTML.|
| [`clear(self)`](/cells/python-net/de/aspose.cells/range/clear/#) | Löscht diesen Bereich.|
| [`clear_contents(self)`](/cells/python-net/de/aspose.cells/range/clear_contents/#) | Löscht den Inhalt dieses Bereichs.|
| [`clear_formats(self)`](/cells/python-net/de/aspose.cells/range/clear_formats/#) | Löscht die Formate dieses Bereichs.|
| [`clear_comments(self)`](/cells/python-net/de/aspose.cells/range/clear_comments/#) | Löscht die Kommentare dieses Bereichs.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/de/aspose.cells/range/clear_hyperlinks/#bool) | Entfernt nur Hyperlinks.|



###  Bemerkungen

Die Klasse Range bezeichnet einen Bereich einer Excel-Tabelle.
Damit können Sie den Wert des Bereichs formatieren und festlegen.
Und Sie können auch einfach den Bereich von Excel kopieren.

###  Beispiel

Das folgende Beispiel zeigt, wie Sie einen Bereich erstellen und den Wertbereich von Excel festlegen.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
