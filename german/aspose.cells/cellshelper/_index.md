---
title: CellsHelper Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 210
url: /de/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper Klasse
Bietet Hilfsfunktionen.



Der Typ CellsHelper macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [significant_digits](/cells/python-net/de/aspose.cells/cellshelper/significant_digits) | Ruft die Anzahl der signifikanten Ziffern ab und legt sie fest.<br/> Der Standardwert ist 17.|
| [dpi](/cells/python-net/de/aspose.cells/cellshelper/dpi) | Ruft die DPI der Maschine ab.|
| [startup_path](/cells/python-net/de/aspose.cells/cellshelper/startup_path) | Ruft den Startpfad ab oder legt ihn fest, auf den einige externe Formelreferenzen verweisen.|
| [alt_start_path](/cells/python-net/de/aspose.cells/cellshelper/alt_start_path) | Ruft den alternativen Startpfad ab oder legt ihn fest, auf den einige externe Formelreferenzen verweisen.|
| [library_path](/cells/python-net/de/aspose.cells/cellshelper/library_path) |Ruft den Bibliothekspfad ab oder legt ihn fest, auf den einige externe Formelreferenzen verweisen.|
| [custom_implementation_factory](/cells/python-net/de/aspose.cells/cellshelper/custom_implementation_factory) | Ruft die Factory zum Erstellen von Instanzen mit spezieller Implementierung ab oder legt sie fest.|
| [is_cloud_platform](/cells/python-net/de/aspose.cells/cellshelper/is_cloud_platform) | Bitte setzen Sie diese Eigenschaft auf „True“, wenn Sie auf einer Cloud-Plattform wie Azure, AWSLambda usw. arbeiten.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/de/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Überprüft den angegebenen Blattnamen und erstellt bei Bedarf einen gültigen.<br/>Wenn der angegebene Blattname den Regeln für Excel-Blattnamen entspricht, geben Sie ihn zurück.<br/>Andernfalls wird die Zeichenfolge abgeschnitten, wenn die Länge das Limit überschreitet<br/> und ungültige Zeichen werden durch „ “ ersetzt, dann wird der neu erstellte Zeichenfolgenwert zurückgegeben.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/de/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Überprüft den angegebenen Blattnamen und erstellt bei Bedarf einen gültigen.<br/>Wenn der angegebene Blattname den Regeln für Excel-Blattnamen entspricht, geben Sie ihn zurück.<br/>Andernfalls wird die Zeichenfolge abgeschnitten, wenn die Länge das Limit überschreitet<br/> und ungültige Zeichen werden durch das angegebene Zeichen ersetzt, dann wird der neu erstellte Zeichenfolgenwert zurückgegeben.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/de/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | Ermitteln Sie die Textbreite in Punkten.|
| [`get_version()`](/cells/python-net/de/aspose.cells/cellshelper/get_version/#) | Holen Sie sich die Release-Version.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/de/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Ruft die Zeilen- und Spaltenindizes der Zelle entsprechend ihrem Namen ab.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/de/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Ruft den Zellennamen entsprechend seinen Zeilen- und Spaltenindizes ab.|
| [`column_index_to_name(, column)`](/cells/python-net/de/aspose.cells/cellshelper/column_index_to_name/#int) | Ruft den Spaltennamen entsprechend dem Spaltenindex ab.|
| [`column_name_to_index(, column_name)`](/cells/python-net/de/aspose.cells/cellshelper/column_name_to_index/#str) | Ruft den Spaltenindex entsprechend dem Spaltennamen ab.|
| [`row_index_to_name(, row)`](/cells/python-net/de/aspose.cells/cellshelper/row_index_to_name/#int) | Ruft den Zeilennamen entsprechend dem Zeilenindex ab.|
| [`row_name_to_index(, row_name)`](/cells/python-net/de/aspose.cells/cellshelper/row_name_to_index/#str) | Ruft den Zeilenindex entsprechend dem Zeilennamen ab.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/de/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Konvertiert die r1c1-Formel der Zelle in die A1-Formel.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/de/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |Konvertiert die A1-Formel der Zelle in die r1c1-Formel.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/de/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Konvertieren Sie den Double-Wert in den Datums-/Uhrzeitwert.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/de/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | Konvertieren Sie Datum und Uhrzeit in einen doppelten Wert.|
| [`get_used_colors(, workbook)`](/cells/python-net/de/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | Ruft alle in der Arbeitsmappe verwendeten Farben ab.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/de/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | Add-In-Funktion hinzufügen.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/de/aspose.cells/cellshelper/merge_files/#list-str-str) | Fügt mehrere große XLS-Dateien zu einer XLS-Datei zusammen.|
| [`get_cache_folder()`](/cells/python-net/de/aspose.cells/cellshelper/get_cache_folder/#) | Ruft den Ordner für temporäre Dateien ab, die als Datencache verwendet werden können.|
| [`set_cache_folder(, cache)`](/cells/python-net/de/aspose.cells/cellshelper/set_cache_folder/#str) | Legt den Ordner für temporäre Dateien fest, die als Datencache verwendet werden können.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/de/aspose.cells/cellshelper/need_quote_in_formula/#str) | Gibt an, ob der Name des Blattes in einfache Anführungszeichen gesetzt werden soll|
| [`init_for_dot_net_core()`](/cells/python-net/de/aspose.cells/cellshelper/init_for_dot_net_core/#) | Führen Sie die Initialisierung für das .NetCore-Programm durch.<br/> Wir empfehlen Ihnen, diese Methode zuerst für alle .NetCore-Initialisierungen aufzurufen.<br/>Zum Beispiel:<br/>CellsHelper.InitForDotNetCore();<br/> Arbeitsmappe wb = neue Arbeitsmappe();|



###  Siehe auch
* Modul [`aspose.cells`](..)
