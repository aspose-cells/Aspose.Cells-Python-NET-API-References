---
title: HtmlLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 800
url: /de/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions Klasse
Stellt Optionen beim Importieren einer HTML-Datei dar.



**Nachlass:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)



Der Typ HtmlLoadOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/htmlloadoptions/__init__/#) | Erstellt Optionen zum Laden der Datei.|
| [__init__](/cells/python-net/de/aspose.cells/htmlloadoptions/__init__/#aspose.cells.LoadFormat) | Erstellt Optionen zum Laden der Datei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells/htmlloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells/htmlloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Gibt an, ob zwischengespeicherte Pivot-Datensätze beim Laden der Datei analysiert werden.<br/> Der Standardwert ist false.|
| [language_code](/cells/python-net/de/aspose.cells/htmlloadoptions/language_code) | Ruft die Benutzeroberflächensprache der Arbeitsmappenversion basierend auf dem CountryCode ab, der die Datei gespeichert hat, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells/htmlloadoptions/region) |Ruft die regionalen Systemeinstellungen basierend auf CountryCode zum Zeitpunkt des Ladens der Datei ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells/htmlloadoptions/default_style_settings) | Ruft die Standardstileinstellungen zum Initialisieren von Stilen der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells/htmlloadoptions/standard_font) | Legt den standardmäßigen Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells/htmlloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [interrupt_monitor](/cells/python-net/de/aspose.cells/htmlloadoptions/interrupt_monitor) | Ruft den Interrupt-Monitor ab und legt ihn fest.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells/htmlloadoptions/ignore_not_printed) | Ignorieren Sie die Daten, die nicht gedruckt werden, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells/htmlloadoptions/check_data_valid) | Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/htmlloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Excel erlaubt beispielsweise keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string) und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.<br/>Wenn diese Eigenschaft falsch ist, akzeptieren wir Ihren Eingabezeichenfolgenwert später als Zellwert<br/>Sie können den vollständigen String-Wert für andere Dateiformate wie CSV ausgeben.<br/>Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/> Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler in der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells/htmlloadoptions/keep_unparsed_data) | Legt fest, ob die ungeparsten Daten für die Arbeitsmappe im Speicher bleiben, wenn sie aus der Vorlagendatei geladen wird. Der Standardwert ist wahr.|
| [load_filter](/cells/python-net/de/aspose.cells/htmlloadoptions/load_filter) | Der Filter, der angibt, wie Daten geladen werden.|
| [light_cells_data_handler](/cells/python-net/de/aspose.cells/htmlloadoptions/light_cells_data_handler) | Der Datenhandler zum Verarbeiten von Zelldaten beim Lesen der Vorlagendatei.|
| [memory_setting](/cells/python-net/de/aspose.cells/htmlloadoptions/memory_setting) | Ruft die Speichernutzungsoptionen ab oder legt diese fest.|
| [warning_callback](/cells/python-net/de/aspose.cells/htmlloadoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells/htmlloadoptions/auto_fitter_options) | Ruft die Auto-Fitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells/htmlloadoptions/auto_filter) | Gibt an, ob die Daten beim Laden der Dateien automatisch gefiltert werden.|
| [font_configs](/cells/python-net/de/aspose.cells/htmlloadoptions/font_configs) | Ruft einzelne Schriftartkonfigurationen ab und legt diese fest.<br/> Funktioniert nur für die [`Workbook`](/cells/python-net/de/aspose.cells/workbook), die diese [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [ignore_useless_shapes](/cells/python-net/de/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Gibt an, ob nutzlose Formen ignoriert werden.|
| [preserve_padding_spaces_in_formula](/cells/python-net/de/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Gibt an, ob die zwischen Formeltoken aufgefüllten Leerzeichen und Zeilenumbrüche beibehalten werden<br/>beim Abrufen und Festlegen von Formeln.<br/> Der Standardwert ist falsch.|
| [encoding](/cells/python-net/de/aspose.cells/htmlloadoptions/encoding) |Ruft die Standardkodierung ab und legt sie fest. Gilt nur für CSV-Dateien.|
| [load_style_strategy](/cells/python-net/de/aspose.cells/htmlloadoptions/load_style_strategy) | Gibt die Strategie zum Anwenden des Stils auf analysierte Werte an, wenn ein Zeichenfolgewert in eine Zahl oder eine Datums-/Uhrzeitkonvertierung umgewandelt wird.|
| [convert_numeric_data](/cells/python-net/de/aspose.cells/htmlloadoptions/convert_numeric_data) | Ruft einen Wert ab oder legt diesen fest, der angibt, ob die Zeichenfolge in der Textdatei in numerische Daten konvertiert wird.|
| [convert_date_time_data](/cells/python-net/de/aspose.cells/htmlloadoptions/convert_date_time_data) | Ruft einen Wert ab oder legt diesen fest, der angibt, ob die Zeichenfolge in der Textdatei in Datumsdaten konvertiert wird.|
| [keep_precision](/cells/python-net/de/aspose.cells/htmlloadoptions/keep_precision) | Gibt an, ob ein Zeichenfolgenwert nicht analysiert wird, wenn die Länge 15 beträgt.|
| [attached_files_directory](/cells/python-net/de/aspose.cells/htmlloadoptions/attached_files_directory) | Das Verzeichnis, in dem die angehängten Dateien gespeichert werden.|
| [load_formulas](/cells/python-net/de/aspose.cells/htmlloadoptions/load_formulas) | Gibt an, ob Formeln importiert werden, wenn die ursprüngliche HTML-Datei Formeln enthält|
| [support_div_tag](/cells/python-net/de/aspose.cells/htmlloadoptions/support_div_tag) |Gibt an, ob das Layout des Tags `<div>` unterstützt wird, wenn die HTML-Datei es enthält.<br/> Der Standardwert ist false.|
| [delete_redundant_spaces](/cells/python-net/de/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Gibt an, ob redundante Leerzeichen gelöscht werden, wenn der Text Zeilen mit dem Tag `<br>` umbricht.<br/> Der Standardwert ist false.|
| [auto_fit_cols_and_rows](/cells/python-net/de/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Gibt an, ob Spalten und Zeilen automatisch angepasst werden. Der Standardwert ist false.|
| [convert_formulas_data](/cells/python-net/de/aspose.cells/htmlloadoptions/convert_formulas_data) | Wenn „true“, wird die Zeichenfolge in eine Formel umgewandelt, wenn der Zeichenfolgenwert mit dem Zeichen „=“ beginnt. Der Standardwert ist „false“.|
| [has_formula](/cells/python-net/de/aspose.cells/htmlloadoptions/has_formula) | Gibt an, ob der Text eine Formel ist, wenn er mit „=" beginnt.|
| [stream_provider](/cells/python-net/de/aspose.cells/htmlloadoptions/stream_provider) | Ruft die StreamProviderImportHtmlFile zum Importieren von Objekten ab oder legt sie fest.|
| [prog_id](/cells/python-net/de/aspose.cells/htmlloadoptions/prog_id) | Ruft die Programm-ID zum Erstellen der Datei ab.<br/> Nur für MHT-Dateien.|
| [table_load_options](/cells/python-net/de/aspose.cells/htmlloadoptions/table_load_options) | Rufen Sie die HtmlTableLoadOptionCollection-Instanz ab|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_paper_size](/cells/python-net/de/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Legt das Standarddruckpapierformat anhand der Standarddruckereinstellung fest.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`AbstractTextLoadOptions`](/cells/python-net/de/aspose.cells/abstracttextloadoptions)
* Klasse [`HtmlLoadOptions`](/cells/python-net/de/aspose.cells/htmlloadoptions)
* Klasse [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
