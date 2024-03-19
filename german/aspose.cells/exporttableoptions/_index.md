---
title: ExportTableOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 580
url: /de/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions Klasse
Stellt alle Exporttabellenoptionen dar.



Der Typ ExportTableOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/exporttableoptions/__init__/#) | Konstruiert eine neue Instanz von ExportTableOptions|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [export_column_name](/cells/python-net/de/aspose.cells/exporttableoptions/export_column_name) | Gibt an, ob die Daten in der ersten Zeile in den Spaltennamen der DataTable exportiert werden.<br/> Der Standardwert ist false.|
| [skip_error_value](/cells/python-net/de/aspose.cells/exporttableoptions/skip_error_value) | Gibt an, ob ein ungültiger Wert für die Spalte übersprungen wird.<br/> Wenn der Spaltentyp beispielsweise „decimal“ ist, ist der Wert größer als „decimal.MaxValue“.<br/>und diese Eigenschaft wahr ist, werden wir keine Ausnahme mehr auslösen.<br/> Der Standardwert ist false.|
| [plot_visible_cells](/cells/python-net/de/aspose.cells/exporttableoptions/plot_visible_cells) | Exportiert nur sichtbare Zellen.|
| [plot_visible_rows](/cells/python-net/de/aspose.cells/exporttableoptions/plot_visible_rows) | Exportiert nur sichtbare Zeilen.|
| [plot_visible_columns](/cells/python-net/de/aspose.cells/exporttableoptions/plot_visible_columns) | Exportiert nur sichtbare Spalten.|
| [export_as_string](/cells/python-net/de/aspose.cells/exporttableoptions/export_as_string) | Exportiert den Zeichenfolgenwert der Zellen in die DataTable.|
| [export_as_html_string](/cells/python-net/de/aspose.cells/exporttableoptions/export_as_html_string) | Exportiert den HTML-Stringwert der Zellen in die DataTable.|
| [format_strategy](/cells/python-net/de/aspose.cells/exporttableoptions/format_strategy) | Ruft die Formatstrategie beim Exportieren des Werts als Zeichenfolgenwert ab und legt diese fest.|
| [check_mixed_value_type](/cells/python-net/de/aspose.cells/exporttableoptions/check_mixed_value_type) | Falsch, Aspose.Cells legt den Typ der Datenspalte aus Leistungsgründen auf den Werttyp der ersten Zeile fest.<br/> Richtig, Aspose.Cells prüft, ob die Wertetypen in der Spalte gemischt sind, bevor der Typ der Datenspalte festgelegt wird<br/>Und wenn die Werttypen gemischt sind, ist der Typ der Datenspalte ein String.|
| [allow_db_null](/cells/python-net/de/aspose.cells/exporttableoptions/allow_db_null) | Dieser Wert gibt an, ob DBNulls in dieser Tabelle zulässig sind.|
| [is_vertical](/cells/python-net/de/aspose.cells/exporttableoptions/is_vertical) | True, wenn eine Zeile in der Arbeitsmappendatei eine Zeile in der Datentabelle darstellt. Falsch, wenn eine Spalte in der Arbeitsmappendatei eine Zeile in der Datentabelle darstellt.|
| [indexes](/cells/python-net/de/aspose.cells/exporttableoptions/indexes) | Die Indizes der Spalten/Zeilen, die exportiert werden sollen.|
| [rename_strategy](/cells/python-net/de/aspose.cells/exporttableoptions/rename_strategy) | Strategie für doppelte Spaltennamen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/de/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) | Verarbeiten Sie den Wert der aktuellen Zelle, die exportiert werden soll, vor.|



###  Bemerkungen

Wenn es besondere Anforderungen an den Export gibt, wie z. B. das Ignorieren von Fehlerwerten, kann der Benutzer diese Klasse erweitern
um die entsprechenden APIs zu überschreiben, um das Ziel zu erreichen.

###  Siehe auch
* Modul [`aspose.cells`](..)
