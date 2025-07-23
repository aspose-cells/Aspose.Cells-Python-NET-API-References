---
title: OdsLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1030
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
| [`__init__(self)`](/cells/python-net/de/aspose.cells/odsloadoptions/__init__/#) | Stellt die Optionen zum Laden der ODS-Datei dar.|
| [`__init__(self, type)`](/cells/python-net/de/aspose.cells/odsloadoptions/__init__/#aspose.cells.loadformat) | Stellt die Optionen zum Laden der ODS-Datei dar.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells/odsloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells/odsloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells/odsloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Gibt an, ob beim Laden der Datei die zwischengespeicherten Pivot-Datensätze analysiert werden.<br/> Der Standardwert ist „false“.|
| [language_code](/cells/python-net/de/aspose.cells/odsloadoptions/language_code) | Ruft die Benutzeroberflächensprache der Arbeitsmappenversion basierend auf dem Ländercode ab, in dem die Datei gespeichert wurde, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells/odsloadoptions/region) | Ruft die regionalen Einstellungen für die zu ladende Arbeitsmappe ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells/odsloadoptions/default_style_settings) | Ruft die Standard-Stileinstellungen zum Initialisieren der Stile der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells/odsloadoptions/standard_font) | Legt den Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells/odsloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells/odsloadoptions/ignore_not_printed) | Ignorieren Sie die Daten, die nicht gedruckt werden, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells/odsloadoptions/check_data_valid) | Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/odsloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string), und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.<br/>Wenn diese Eigenschaft falsch ist, akzeptieren wir den eingegebenen Stringwert als Zellenwert, sodass später<br/>Sie können den vollständigen Zeichenfolgenwert für andere Dateiformate wie CSV ausgeben.<br/>Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/>Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu unerwarteten Fehlern bei der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells/odsloadoptions/keep_unparsed_data) | Ob die nicht analysierten Daten für die Arbeitsmappe im Speicher bleiben, wenn sie aus einer Vorlagendatei geladen wird. Der Standardwert ist „true“.|
| [load_filter](/cells/python-net/de/aspose.cells/odsloadoptions/load_filter) | Der Filter gibt an, wie Daten geladen werden.|
| [memory_setting](/cells/python-net/de/aspose.cells/odsloadoptions/memory_setting) | Ruft den Speichermodus für die geladene Arbeitsmappe ab oder legt ihn fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells/odsloadoptions/auto_fitter_options) | Ruft die Auto-Fitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells/odsloadoptions/auto_filter) | Gibt an, ob beim Laden der Dateien eine automatische Filterung der Daten erfolgen soll.|
| [font_configs](/cells/python-net/de/aspose.cells/odsloadoptions/font_configs) | Ruft einzelne Schriftartkonfigurationen ab und legt sie fest.<br/> Funktioniert nur für [`Workbook`](/cells/python-net/de/aspose.cells/workbook), das diese [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [ignore_useless_shapes](/cells/python-net/de/aspose.cells/odsloadoptions/ignore_useless_shapes) | Gibt an, ob unnötige Formen ignoriert werden.|
| [preserve_padding_spaces_in_formula](/cells/python-net/de/aspose.cells/odsloadoptions/preserve_padding_spaces_in_formula) | Gibt an, ob die Leerzeichen und Zeilenumbrüche zwischen den Formel-Tokens beibehalten werden sollen.<br/>beim Abrufen und Festlegen von Formeln.<br/> Der Standardwert ist „false“.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/de/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Gibt an, ob der Standardstil von Excel auf den Hyperlink angewendet werden soll.|
| [refresh_pivot_tables](/cells/python-net/de/aspose.cells/odsloadoptions/refresh_pivot_tables) | Gibt an, ob Pivot-Tabellen beim Laden der Datei aktualisiert werden sollen.|
| [is_classic_pivot_table](/cells/python-net/de/aspose.cells/odsloadoptions/is_classic_pivot_table) | Gibt an, ob die Pivot-Tabelle klassisch ist.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/de/aspose.cells/odsloadoptions/set_paper_size/#aspose.cells.papersizetype) | Legt die Standarddruckpapiergröße anhand der Standardeinstellungen des Druckers fest.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [`OdsLoadOptions`](/cells/python-net/de/aspose.cells/odsloadoptions)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
