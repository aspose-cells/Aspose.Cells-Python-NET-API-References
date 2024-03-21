---
title: TxtLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1580
url: /de/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions Klasse
Stellt die Optionen zum Laden einer Textdatei dar.



**Nachlass:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)



Der Typ TxtLoadOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/txtloadoptions/__init__/#) | Erstellt die Optionen zum Laden einer Textdatei.|
| [__init__](/cells/python-net/de/aspose.cells/txtloadoptions/__init__/#aspose.cells.LoadFormat) | Erstellt die Optionen zum Laden einer Textdatei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells/txtloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells/txtloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells/txtloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Gibt an, ob zwischengespeicherte Pivot-Datensätze beim Laden der Datei analysiert werden.<br/> Der Standardwert ist false.|
| [language_code](/cells/python-net/de/aspose.cells/txtloadoptions/language_code) | Ruft die Benutzeroberflächensprache der Arbeitsmappenversion basierend auf dem CountryCode ab, der die Datei gespeichert hat, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells/txtloadoptions/region) |Ruft die regionalen Systemeinstellungen basierend auf CountryCode zum Zeitpunkt des Ladens der Datei ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells/txtloadoptions/default_style_settings) | Ruft die Standardstileinstellungen zum Initialisieren von Stilen der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells/txtloadoptions/standard_font) | Legt den standardmäßigen Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells/txtloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [interrupt_monitor](/cells/python-net/de/aspose.cells/txtloadoptions/interrupt_monitor) | Ruft den Interrupt-Monitor ab und legt ihn fest.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells/txtloadoptions/ignore_not_printed) | Ignorieren Sie die Daten, die nicht gedruckt werden, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells/txtloadoptions/check_data_valid) | Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/txtloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Excel erlaubt beispielsweise keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string) und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.<br/>Wenn diese Eigenschaft falsch ist, akzeptieren wir Ihren Eingabezeichenfolgenwert später als Zellwert<br/>Sie können den vollständigen String-Wert für andere Dateiformate wie CSV ausgeben.<br/>Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/> Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler in der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells/txtloadoptions/keep_unparsed_data) | Legt fest, ob die ungeparsten Daten für die Arbeitsmappe im Speicher bleiben, wenn sie aus der Vorlagendatei geladen wird. Der Standardwert ist wahr.|
| [load_filter](/cells/python-net/de/aspose.cells/txtloadoptions/load_filter) | Der Filter, der angibt, wie Daten geladen werden.|
| [light_cells_data_handler](/cells/python-net/de/aspose.cells/txtloadoptions/light_cells_data_handler) | Der Datenhandler zum Verarbeiten von Zelldaten beim Lesen der Vorlagendatei.|
| [memory_setting](/cells/python-net/de/aspose.cells/txtloadoptions/memory_setting) | Ruft die Speichernutzungsoptionen ab oder legt diese fest.|
| [warning_callback](/cells/python-net/de/aspose.cells/txtloadoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells/txtloadoptions/auto_fitter_options) | Ruft die Auto-Fitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells/txtloadoptions/auto_filter) | Gibt an, ob die Daten beim Laden der Dateien automatisch gefiltert werden.|
| [font_configs](/cells/python-net/de/aspose.cells/txtloadoptions/font_configs) | Ruft einzelne Schriftartkonfigurationen ab und legt diese fest.<br/> Funktioniert nur für die [`Workbook`](/cells/python-net/de/aspose.cells/workbook), die diese [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [ignore_useless_shapes](/cells/python-net/de/aspose.cells/txtloadoptions/ignore_useless_shapes) | Gibt an, ob nutzlose Formen ignoriert werden.|
| [preserve_padding_spaces_in_formula](/cells/python-net/de/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Gibt an, ob die zwischen Formeltoken aufgefüllten Leerzeichen und Zeilenumbrüche beibehalten werden<br/>beim Abrufen und Festlegen von Formeln.<br/> Der Standardwert ist falsch.|
| [encoding](/cells/python-net/de/aspose.cells/txtloadoptions/encoding) |Ruft die Standardkodierung ab und legt sie fest. Gilt nur für CSV-Dateien.|
| [load_style_strategy](/cells/python-net/de/aspose.cells/txtloadoptions/load_style_strategy) | Gibt die Strategie zum Anwenden des Stils auf analysierte Werte an, wenn ein Zeichenfolgewert in eine Zahl oder eine Datums-/Uhrzeitkonvertierung umgewandelt wird.|
| [convert_numeric_data](/cells/python-net/de/aspose.cells/txtloadoptions/convert_numeric_data) | Ruft einen Wert ab oder legt diesen fest, der angibt, ob die Zeichenfolge in der Textdatei in numerische Daten konvertiert wird.|
| [convert_date_time_data](/cells/python-net/de/aspose.cells/txtloadoptions/convert_date_time_data) | Ruft einen Wert ab oder legt diesen fest, der angibt, ob die Zeichenfolge in der Textdatei in Datumsdaten konvertiert wird.|
| [keep_precision](/cells/python-net/de/aspose.cells/txtloadoptions/keep_precision) | Gibt an, ob ein Zeichenfolgenwert nicht analysiert wird, wenn die Länge 15 beträgt.|
| [separator](/cells/python-net/de/aspose.cells/txtloadoptions/separator) | Ruft das Zeichentrennzeichen der Textdatei ab und legt es fest.|
| [separator_string](/cells/python-net/de/aspose.cells/txtloadoptions/separator_string) | Ruft einen Zeichenfolgenwert als Trennzeichen ab und legt diesen fest.|
| [is_multi_encoded](/cells/python-net/de/aspose.cells/txtloadoptions/is_multi_encoded) |True bedeutet, dass die Datei mehrere Kodierungen enthält.|
| [preferred_parsers](/cells/python-net/de/aspose.cells/txtloadoptions/preferred_parsers) | Ruft bevorzugte Wertparser zum Laden einer Textdatei ab und legt diese fest.|
| [has_formula](/cells/python-net/de/aspose.cells/txtloadoptions/has_formula) | Gibt an, ob der Text eine Formel ist, wenn er mit „=" beginnt.|
| [has_text_qualifier](/cells/python-net/de/aspose.cells/txtloadoptions/has_text_qualifier) | Ob es einen Textqualifizierer für den Zellenwert gibt. Der Standardwert ist wahr.|
| [text_qualifier](/cells/python-net/de/aspose.cells/txtloadoptions/text_qualifier) | Gibt den Textqualifizierer für Zellwerte an. Der Standardqualifikator ist „““.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/de/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Ob aufeinanderfolgende Trennzeichen als eins behandelt werden sollen.|
| [treat_quote_prefix_as_value](/cells/python-net/de/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Gibt an, ob das führende einfache Anführungszeichen als Teil des Werts einer Zelle verwendet werden soll.<br/>Der Standardwert ist wahr. Wenn es falsch ist, wird das führende einfache Anführungszeichen aus dem Wert der entsprechenden Zelle entfernt<br/> und [`Style.quote_prefix`](/cells/python-net/de/aspose.cells/style#quote_prefix) werden für die Zelle auf „true“ gesetzt.|
| [extend_to_next_sheet](/cells/python-net/de/aspose.cells/txtloadoptions/extend_to_next_sheet) | Ob die Daten auf das nächste Blatt erweitert werden, wenn die Datenzeilen oder -spalten den Grenzwert überschreiten.<br/> Der Standardwert ist falsch.|
| [header_rows_count](/cells/python-net/de/aspose.cells/txtloadoptions/header_rows_count) | Die Anzahl der Kopfzeilen, die für erweiterte Blätter wiederholt werden sollen.|
| [header_columns_count](/cells/python-net/de/aspose.cells/txtloadoptions/header_columns_count) | Die Anzahl der Kopfspalten, die für erweiterte Blätter wiederholt werden sollen.|
| [max_row_count](/cells/python-net/de/aspose.cells/txtloadoptions/max_row_count) | Die maximale Anzahl der Zeilen, die für ein Blatt importiert werden sollen.|
| [max_column_count](/cells/python-net/de/aspose.cells/txtloadoptions/max_column_count) | Die maximale Anzahl der Spalten, die für ein Blatt importiert werden sollen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_paper_size](/cells/python-net/de/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Legt das Standarddruckpapierformat anhand der Standarddruckereinstellung fest.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`AbstractTextLoadOptions`](/cells/python-net/de/aspose.cells/abstracttextloadoptions)
* Klasse [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [`TxtLoadOptions`](/cells/python-net/de/aspose.cells/txtloadoptions)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
