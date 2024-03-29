---
title: OdsLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1140
url: /de/aspose.cells/odsloadoptions/
is_root: false
---
##  OdsLoadOptions Klasse
Stellt die Optionen zum Laden der ODS-Datei dar.



**Nachlass:** [`OdsLoadOptions`](/cells/python-net/aspose.cells/odsloadoptions) → 
[`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)



Der Typ OdsLoadOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/odsloadoptions/__init__/#) | Stellt die Optionen zum Laden der ODS-Datei dar.|
| [__init__](/cells/python-net/de/aspose.cells/odsloadoptions/__init__/#aspose.cells.LoadFormat) | Stellt die Optionen zum Laden der ODS-Datei dar.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells/odsloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells/odsloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells/odsloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Gibt an, ob zwischengespeicherte Pivot-Datensätze beim Laden der Datei analysiert werden.<br/> Der Standardwert ist false.|
| [language_code](/cells/python-net/de/aspose.cells/odsloadoptions/language_code) | Ruft die Benutzeroberflächensprache der Arbeitsmappenversion basierend auf dem CountryCode ab, der die Datei gespeichert hat, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells/odsloadoptions/region) |Ruft die regionalen Systemeinstellungen basierend auf CountryCode zum Zeitpunkt des Ladens der Datei ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells/odsloadoptions/default_style_settings) | Ruft die Standardstileinstellungen zum Initialisieren von Stilen der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells/odsloadoptions/standard_font) | Legt den standardmäßigen Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells/odsloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [interrupt_monitor](/cells/python-net/de/aspose.cells/odsloadoptions/interrupt_monitor) | Ruft den Interrupt-Monitor ab und legt ihn fest.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells/odsloadoptions/ignore_not_printed) | Ignorieren Sie die Daten, die nicht gedruckt werden, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells/odsloadoptions/check_data_valid) | Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/odsloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Excel erlaubt beispielsweise keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string) und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.<br/>Wenn diese Eigenschaft falsch ist, akzeptieren wir Ihren Eingabezeichenfolgenwert später als Zellwert<br/>Sie können den vollständigen String-Wert für andere Dateiformate wie CSV ausgeben.<br/>Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/> Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler in der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells/odsloadoptions/keep_unparsed_data) | Legt fest, ob die ungeparsten Daten für die Arbeitsmappe im Speicher bleiben, wenn sie aus der Vorlagendatei geladen wird. Der Standardwert ist wahr.|
| [load_filter](/cells/python-net/de/aspose.cells/odsloadoptions/load_filter) | Der Filter, der angibt, wie Daten geladen werden.|
| [light_cells_data_handler](/cells/python-net/de/aspose.cells/odsloadoptions/light_cells_data_handler) | Der Datenhandler zum Verarbeiten von Zelldaten beim Lesen der Vorlagendatei.|
| [memory_setting](/cells/python-net/de/aspose.cells/odsloadoptions/memory_setting) | Ruft die Speichernutzungsoptionen ab oder legt diese fest.|
| [warning_callback](/cells/python-net/de/aspose.cells/odsloadoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells/odsloadoptions/auto_fitter_options) | Ruft die Auto-Fitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells/odsloadoptions/auto_filter) | Gibt an, ob die Daten beim Laden der Dateien automatisch gefiltert werden.|
| [font_configs](/cells/python-net/de/aspose.cells/odsloadoptions/font_configs) | Ruft einzelne Schriftartkonfigurationen ab und legt diese fest.<br/> Funktioniert nur für die [`Workbook`](/cells/python-net/de/aspose.cells/workbook), die diese [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [ignore_useless_shapes](/cells/python-net/de/aspose.cells/odsloadoptions/ignore_useless_shapes) | Gibt an, ob nutzlose Formen ignoriert werden.|
| [preserve_padding_spaces_in_formula](/cells/python-net/de/aspose.cells/odsloadoptions/preserve_padding_spaces_in_formula) | Gibt an, ob die zwischen Formeltoken aufgefüllten Leerzeichen und Zeilenumbrüche beibehalten werden<br/>beim Abrufen und Festlegen von Formeln.<br/> Der Standardwert ist falsch.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/de/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Gibt an, ob der Standardstil von Excel auf Hyperlinks angewendet wird.|
| [refresh_pivot_tables](/cells/python-net/de/aspose.cells/odsloadoptions/refresh_pivot_tables) | Gibt an, ob Pivot-Tabellen beim Laden der Datei aktualisiert werden sollen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_paper_size](/cells/python-net/de/aspose.cells/odsloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Legt das Standarddruckpapierformat anhand der Standarddruckereinstellung fest.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [`OdsLoadOptions`](/cells/python-net/de/aspose.cells/odsloadoptions)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
