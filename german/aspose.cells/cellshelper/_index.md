---
title: CellsHelper Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 240
url: /de/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper Klasse
Stellt Hilfsfunktionen bereit.



Der Typ CellsHelper macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [significant_digits](/cells/python-net/de/aspose.cells/cellshelper/significant_digits) | Ruft die Anzahl der signifikanten Ziffern ab und legt sie fest.<br/> Der Standardwert ist 17.|
| [dpi](/cells/python-net/de/aspose.cells/cellshelper/dpi) | Ruft die DPI des Computers ab.|
| [startup_path](/cells/python-net/de/aspose.cells/cellshelper/startup_path) | Ruft den Startpfad ab, auf den einige externe Formelverweise verweisen, oder legt diesen fest.|
| [alt_start_path](/cells/python-net/de/aspose.cells/cellshelper/alt_start_path) | Ruft den alternativen Startpfad ab, auf den einige externe Formelverweise verweisen, oder legt diesen fest.|
| [library_path](/cells/python-net/de/aspose.cells/cellshelper/library_path) | Ruft den Bibliothekspfad ab, auf den einige externe Formelverweise verweisen, oder legt diesen fest.|
| [custom_implementation_factory](/cells/python-net/de/aspose.cells/cellshelper/custom_implementation_factory) | Ruft die Factory zum Erstellen von Instanzen mit spezieller Implementierung ab oder legt diese fest.|
| [is_cloud_platform](/cells/python-net/de/aspose.cells/cellshelper/is_cloud_platform) | Bitte setzen Sie diese Eigenschaft auf „True“, wenn Sie auf einer Cloud-Plattform wie Azure, AWSLambda usw. ausgeführt werden.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/de/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Überprüft den angegebenen Blattnamen und erstellt bei Bedarf einen gültigen.<br/>Wenn der angegebene Tabellenname den Regeln des Excel-Tabellennamens entspricht, geben Sie ihn zurück.<br/>Andernfalls wird die Zeichenfolge abgeschnitten, wenn die Länge das Limit überschreitet<br/>und ungültige Zeichen werden durch „“ ersetzt und geben dann den neu erstellten Zeichenfolgenwert zurück.|
| [create_safe_sheet_name](/cells/python-net/de/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Überprüft den angegebenen Blattnamen und erstellt bei Bedarf einen gültigen.<br/>Wenn der angegebene Tabellenname den Regeln des Excel-Tabellennamens entspricht, geben Sie ihn zurück.<br/>Andernfalls wird die Zeichenfolge abgeschnitten, wenn die Länge das Limit überschreitet<br/> und ungültige Zeichen werden durch das angegebene Zeichen ersetzt, dann wird der neu erstellte Zeichenfolgenwert zurückgegeben.|
| [get_text_width](/cells/python-net/de/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | Ermitteln Sie die Breite des Textes in Punkteinheiten.|
| [get_version](/cells/python-net/de/aspose.cells/cellshelper/get_version/#) | Holen Sie sich die Release-Version.|
| [cell_name_to_index](/cells/python-net/de/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Ruft die Zeilen- und Spaltenindizes der Zelle entsprechend ihrem Namen ab.|
| [cell_index_to_name](/cells/python-net/de/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Ruft den Zellnamen entsprechend seinen Zeilen- und Spaltenindizes ab.|
| [column_index_to_name](/cells/python-net/de/aspose.cells/cellshelper/column_index_to_name/#int) | Ruft den Spaltennamen gemäß dem Spaltenindex ab.|
| [column_name_to_index](/cells/python-net/de/aspose.cells/cellshelper/column_name_to_index/#str) | Ruft den Spaltenindex entsprechend dem Spaltennamen ab.|
| [row_index_to_name](/cells/python-net/de/aspose.cells/cellshelper/row_index_to_name/#int) | Ruft den Zeilennamen entsprechend dem Zeilenindex ab.|
| [row_name_to_index](/cells/python-net/de/aspose.cells/cellshelper/row_name_to_index/#str) | Ruft den Zeilenindex entsprechend dem Zeilennamen ab.|
| [convert_r1c1_formula_to_a1](/cells/python-net/de/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Konvertiert die r1c1-Formel der Zelle in die A1-Formel.|
| [convert_a1_formula_to_r1c1](/cells/python-net/de/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | Konvertiert die A1-Formel der Zelle in die r1c1-Formel.|
| [get_date_time_from_double](/cells/python-net/de/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Konvertieren Sie den Double-Wert in den Datum-Uhrzeit-Wert.|
| [get_double_from_date_time](/cells/python-net/de/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | Konvertieren Sie das Datum und die Uhrzeit in einen doppelten Wert.|
| [get_used_colors](/cells/python-net/de/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | Ruft alle verwendeten Farben in der Arbeitsmappe ab.|
| [add_add_in_function](/cells/python-net/de/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | Add-In-Funktion hinzufügen.|
| [merge_files](/cells/python-net/de/aspose.cells/cellshelper/merge_files/#list-str-str) | Führt einige große XLS-Dateien zu einer XLS-Datei zusammen.|
| [need_quote_in_formula](/cells/python-net/de/aspose.cells/cellshelper/need_quote_in_formula/#str) |Gibt an, ob der Name des Blatts in einfache Anführungszeichen gesetzt werden soll|
| [init_for_dot_net_core](/cells/python-net/de/aspose.cells/cellshelper/init_for_dot_net_core/#) | Führen Sie die Initialisierung für das .NetCore-Programm durch.<br/> Wir empfehlen Ihnen, diese Methode zuerst für alle .NetCore-Initialisierungen aufzurufen.<br/>Zum Beispiel:<br/>CellsHelper.InitForDotNetCore();<br/> Arbeitsmappe wb = new Workbook();|



###  Siehe auch
* Modul [`aspose.cells`](..)
