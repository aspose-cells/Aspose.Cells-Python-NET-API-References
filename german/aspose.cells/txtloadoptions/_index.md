---
title: TxtLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1490
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
| [`__init__(self)`](/cells/python-net/de/aspose.cells/txtloadoptions/__init__/#) | Erstellt die Optionen zum Laden der Textdatei.|
| [`__init__(self, load_format)`](/cells/python-net/de/aspose.cells/txtloadoptions/__init__/#aspose.cells.loadformat) | Erstellt die Optionen zum Laden der Textdatei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells/txtloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells/txtloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells/txtloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Gibt an, ob beim Laden der Datei die zwischengespeicherten Pivot-Datensätze analysiert werden.<br/> Der Standardwert ist „false“.|
| [language_code](/cells/python-net/de/aspose.cells/txtloadoptions/language_code) | Ruft die Benutzeroberflächensprache der Arbeitsmappenversion basierend auf dem Ländercode ab, in dem die Datei gespeichert wurde, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells/txtloadoptions/region) | Ruft die regionalen Einstellungen für die zu ladende Arbeitsmappe ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells/txtloadoptions/default_style_settings) | Ruft die Standard-Stileinstellungen zum Initialisieren der Stile der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells/txtloadoptions/standard_font) | Legt den Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells/txtloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells/txtloadoptions/ignore_not_printed) | Ignorieren Sie die Daten, die nicht gedruckt werden, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells/txtloadoptions/check_data_valid) | Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/txtloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string), und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.<br/>Wenn diese Eigenschaft falsch ist, akzeptieren wir den eingegebenen Stringwert als Zellenwert, sodass später<br/>Sie können den vollständigen Zeichenfolgenwert für andere Dateiformate wie CSV ausgeben.<br/>Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/>Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu unerwarteten Fehlern bei der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells/txtloadoptions/keep_unparsed_data) | Ob die nicht analysierten Daten für die Arbeitsmappe im Speicher bleiben, wenn sie aus einer Vorlagendatei geladen wird. Der Standardwert ist „true“.|
| [load_filter](/cells/python-net/de/aspose.cells/txtloadoptions/load_filter) | Der Filter gibt an, wie Daten geladen werden.|
| [memory_setting](/cells/python-net/de/aspose.cells/txtloadoptions/memory_setting) | Ruft den Speichermodus für die geladene Arbeitsmappe ab oder legt ihn fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells/txtloadoptions/auto_fitter_options) | Ruft die Auto-Fitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells/txtloadoptions/auto_filter) | Gibt an, ob beim Laden der Dateien eine automatische Filterung der Daten erfolgen soll.|
| [font_configs](/cells/python-net/de/aspose.cells/txtloadoptions/font_configs) | Ruft einzelne Schriftartkonfigurationen ab und legt sie fest.<br/> Funktioniert nur für [`Workbook`](/cells/python-net/de/aspose.cells/workbook), das diese [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [ignore_useless_shapes](/cells/python-net/de/aspose.cells/txtloadoptions/ignore_useless_shapes) | Gibt an, ob unnötige Formen ignoriert werden.|
| [preserve_padding_spaces_in_formula](/cells/python-net/de/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Gibt an, ob die Leerzeichen und Zeilenumbrüche zwischen den Formel-Tokens beibehalten werden sollen.<br/>beim Abrufen und Festlegen von Formeln.<br/> Der Standardwert ist „false“.|
| [encoding](/cells/python-net/de/aspose.cells/txtloadoptions/encoding) | Ruft die Standardkodierung ab und legt sie fest. Gilt nur für CSV-Dateien.|
| [load_style_strategy](/cells/python-net/de/aspose.cells/txtloadoptions/load_style_strategy) | Gibt die Strategie zum Anwenden des Stils auf analysierte Werte an, wenn Zeichenfolgenwerte in Zahlen oder Datums-/Uhrzeitwerte konvertiert werden.|
| [convert_numeric_data](/cells/python-net/de/aspose.cells/txtloadoptions/convert_numeric_data) |Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Zeichenfolge in der Textdatei in numerische Daten konvertiert wird.|
| [convert_date_time_data](/cells/python-net/de/aspose.cells/txtloadoptions/convert_date_time_data) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Zeichenfolge in der Textdatei in Datumsdaten konvertiert wird.|
| [keep_precision](/cells/python-net/de/aspose.cells/txtloadoptions/keep_precision) | Gibt an, ob ein Zeichenfolgenwert analysiert wird, wenn die Länge 15 beträgt.|
| [separator](/cells/python-net/de/aspose.cells/txtloadoptions/separator) | Ruft das Zeichentrennzeichen der Textdatei ab und legt es fest.|
| [separator_string](/cells/python-net/de/aspose.cells/txtloadoptions/separator_string) | Ruft einen Zeichenfolgenwert als Trennzeichen ab und legt ihn fest.|
| [is_multi_encoded](/cells/python-net/de/aspose.cells/txtloadoptions/is_multi_encoded) | True bedeutet, dass die Datei mehrere Kodierungen enthält.|
| [preferred_parsers](/cells/python-net/de/aspose.cells/txtloadoptions/preferred_parsers) | Ruft bevorzugte Werteparser zum Laden von Textdateien ab und legt sie fest.|
| [has_formula](/cells/python-net/de/aspose.cells/txtloadoptions/has_formula) | Gibt an, ob es sich bei dem Text um eine Formel handelt, wenn er mit „=“ beginnt.|
| [has_text_qualifier](/cells/python-net/de/aspose.cells/txtloadoptions/has_text_qualifier) | Gibt an, ob für den Zellenwert ein Textqualifizierer vorhanden ist. Der Standardwert ist „true“.|
| [text_qualifier](/cells/python-net/de/aspose.cells/txtloadoptions/text_qualifier) | Gibt den Textqualifizierer für Zellenwerte an. Der Standardqualifizierer ist „“.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/de/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Ob aufeinanderfolgende Trennzeichen als eins behandelt werden sollen.|
| [treat_quote_prefix_as_value](/cells/python-net/de/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Gibt an, ob das führende einfache Anführungszeichen als Teil des Werts einer Zelle betrachtet werden soll.<br/>Der Standardwert ist „true“. Wenn er „false“ ist, wird das führende einfache Anführungszeichen aus dem entsprechenden Zellenwert entfernt.<br/> und [`Style.quote_prefix`](/cells/python-net/de/aspose.cells/style#quote_prefix) wird für die Zelle als wahr festgelegt.|
| [extend_to_next_sheet](/cells/python-net/de/aspose.cells/txtloadoptions/extend_to_next_sheet) | Ob die Daten auf das nächste Blatt erweitert werden, wenn die Datenzeilen oder -spalten den Grenzwert überschreiten.<br/> Der Standardwert ist „false“.|
| [header_rows_count](/cells/python-net/de/aspose.cells/txtloadoptions/header_rows_count) |Die Anzahl der Kopfzeilen, die für erweiterte Blätter wiederholt werden sollen.|
| [header_columns_count](/cells/python-net/de/aspose.cells/txtloadoptions/header_columns_count) | Die Anzahl der Kopfspalten, die für erweiterte Blätter wiederholt werden sollen.|
| [max_row_count](/cells/python-net/de/aspose.cells/txtloadoptions/max_row_count) | Die maximale Anzahl der für ein Blatt zu importierenden Zeilen.|
| [max_column_count](/cells/python-net/de/aspose.cells/txtloadoptions/max_column_count) | Die maximale Anzahl der für ein Blatt zu importierenden Spalten.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/de/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.papersizetype) | Legt die Standarddruckpapiergröße anhand der Standardeinstellungen des Druckers fest.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`AbstractTextLoadOptions`](/cells/python-net/de/aspose.cells/abstracttextloadoptions)
* Klasse [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [`TxtLoadOptions`](/cells/python-net/de/aspose.cells/txtloadoptions)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
