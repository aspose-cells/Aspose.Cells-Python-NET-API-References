---
title: NumbersLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.numbers/numbersloadoptions/
is_root: false
---
##  NumbersLoadOptions Klasse
Stellt die Optionen zum Laden von Apple Numbers-Dateien dar.



**Nachlass:** [NumbersLoadOptions](/cells/python-net/aspose.cells.numbers/numbersloadoptions) → 
[LoadOptions](/cells/python-net/de/aspose.cells/loadoptions)



Der Typ NumbersLoadOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [NumbersLoadOptions()](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/__init__/#) | Konstrukteur.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/parsing_pivot_cached_records) | Gibt an, ob beim Laden der Datei zwischengespeicherte Pivot-Datensätze analysiert werden.<br/> Der Standardwert ist falsch.|
| [language_code](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/language_code) | Ruft die Sprache der Benutzeroberfläche der Workbook-Version basierend auf dem CountryCode ab, der die Datei gespeichert hat, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/region) | Ruft die regionalen Systemeinstellungen basierend auf CountryCode zum Zeitpunkt des Ladens der Datei ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/default_style_settings) | Ruft die Standardstileinstellungen zum Initialisieren von Stilen der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/standard_font) | Legt den standardmäßigen Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [interrupt_monitor](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/interrupt_monitor) | Ruft den Interrupt-Monitor ab und setzt ihn.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/ignore_not_printed) | Ignorieren Sie die nicht gedruckten Daten, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/check_data_valid) |Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, wie z. B. Cell.PutValue(string), erhalten Sie eine Ausnahme, wenn diese Eigenschaft wahr ist.<br/>Wenn diese Eigenschaft "false" ist, akzeptieren wir Ihren Eingabe-String-Wert als Wert der Zelle, damit dies später möglich ist<br/>bei anderen Dateiformaten wie CSV können Sie den kompletten Stringwert ausgeben.<br/>Wenn Sie jedoch einen solchen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/> Sie sollten die Arbeitsmappe später nicht als Excel-Dateiformat speichern. Andernfalls kann es zu unerwarteten Fehlern in der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/keep_unparsed_data) | Ob die ungeparsten Daten für die Arbeitsmappe im Arbeitsspeicher bleiben, wenn sie aus der Vorlagendatei geladen wird. Standard ist wahr.|
| [load_filter](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/load_filter) | Der Filter, der angibt, wie Daten geladen werden.|
| [light_cells_data_handler](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/light_cells_data_handler) | Der Datenhandler zum Verarbeiten von Zellendaten beim Lesen der Vorlagendatei.|
| [memory_setting](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/memory_setting) | Ruft die Speichernutzungsoptionen ab oder legt diese fest.|
| [warning_callback](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/warning_callback) | Ruft einen Warnungsrückruf ab oder legt ihn fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/auto_fitter_options) | Ruft die Autofitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/auto_filter) | Gibt an, ob die Daten beim Laden der Dateien automatisch gefiltert werden.|
| [font_configs](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/font_configs) | Ruft individuelle Schriftartkonfigurationen ab und legt sie fest.<br/> Funktioniert nur für die [Workbook](/cells/python-net/de/aspose.cells/workbook), die diese [LoadOptions](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [load_table_type](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/load_table_type) | Ruft den Typ zum Laden mehrerer Tabellen in einem Arbeitsblatt ab und legt diesen fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions/set_paper_size/#PaperSizeType) | Legt das Standarddruckpapierformat aus der Standarddruckereinstellung fest.|



###  Siehe auch
* Modul [aspose.cells.numbers](..)
* Klasse [LoadOptions](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [NumbersLoadOptions](/cells/python-net/de/aspose.cells.numbers/numbersloadoptions)
* Klasse [Workbook](/cells/python-net/de/aspose.cells/workbook)
