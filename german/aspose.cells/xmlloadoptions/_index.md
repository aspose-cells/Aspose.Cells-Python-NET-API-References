---
title: XmlLoadOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1660
url: /de/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions Klasse
Stellt die Optionen zum Laden von XML dar.



**Nachlass:** [`XmlLoadOptions`](/cells/python-net/aspose.cells/xmlloadoptions) → 
[`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)



Der Typ XmlLoadOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/xmlloadoptions/__init__/#) | Stellt die Optionen zum Laden der XML-Datei dar.|
| [`__init__(self, type)`](/cells/python-net/de/aspose.cells/xmlloadoptions/__init__/#aspose.cells.loadformat) | Stellt die Optionen zum Laden der XML-Datei dar.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_format](/cells/python-net/de/aspose.cells/xmlloadoptions/load_format) | Ruft das Ladeformat ab.|
| [password](/cells/python-net/de/aspose.cells/xmlloadoptions/password) | Ruft das Kennwort der Arbeitsmappe ab und legt es fest.|
| [parsing_formula_on_open](/cells/python-net/de/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Gibt an, ob die Formel beim Lesen der Datei analysiert wird.|
| [parsing_pivot_cached_records](/cells/python-net/de/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Gibt an, ob beim Laden der Datei die zwischengespeicherten Pivot-Datensätze analysiert werden.<br/> Der Standardwert ist „false“.|
| [language_code](/cells/python-net/de/aspose.cells/xmlloadoptions/language_code) | Ruft die Benutzeroberflächensprache der Arbeitsmappenversion basierend auf dem Ländercode ab, in dem die Datei gespeichert wurde, oder legt diese fest.|
| [region](/cells/python-net/de/aspose.cells/xmlloadoptions/region) | Ruft die regionalen Einstellungen für die zu ladende Arbeitsmappe ab oder legt diese fest.|
| [default_style_settings](/cells/python-net/de/aspose.cells/xmlloadoptions/default_style_settings) | Ruft die Standard-Stileinstellungen zum Initialisieren der Stile der Arbeitsmappe ab|
| [standard_font](/cells/python-net/de/aspose.cells/xmlloadoptions/standard_font) | Legt den Standardschriftnamen fest|
| [standard_font_size](/cells/python-net/de/aspose.cells/xmlloadoptions/standard_font_size) | Legt die standardmäßige Standardschriftgröße fest.|
| [ignore_not_printed](/cells/python-net/de/aspose.cells/xmlloadoptions/ignore_not_printed) | Ignorieren Sie die Daten, die nicht gedruckt werden, wenn Sie die Datei direkt drucken|
| [check_data_valid](/cells/python-net/de/aspose.cells/xmlloadoptions/check_data_valid) | Prüfen Sie, ob die Daten in der Vorlagendatei gültig sind.|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/xmlloadoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/>Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string), und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.<br/>Wenn diese Eigenschaft falsch ist, akzeptieren wir den eingegebenen Stringwert als Zellenwert, sodass später<br/>Sie können den vollständigen Zeichenfolgenwert für andere Dateiformate wie CSV ausgeben.<br/>Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,<br/>Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu unerwarteten Fehlern bei der generierten Excel-Datei kommen.|
| [keep_unparsed_data](/cells/python-net/de/aspose.cells/xmlloadoptions/keep_unparsed_data) | Ob die nicht analysierten Daten für die Arbeitsmappe im Speicher bleiben, wenn sie aus einer Vorlagendatei geladen wird. Der Standardwert ist „true“.|
| [load_filter](/cells/python-net/de/aspose.cells/xmlloadoptions/load_filter) | Der Filter gibt an, wie Daten geladen werden.|
| [memory_setting](/cells/python-net/de/aspose.cells/xmlloadoptions/memory_setting) | Ruft den Speichermodus für die geladene Arbeitsmappe ab oder legt ihn fest.|
| [auto_fitter_options](/cells/python-net/de/aspose.cells/xmlloadoptions/auto_fitter_options) | Ruft die Auto-Fitter-Optionen ab und legt sie fest|
| [auto_filter](/cells/python-net/de/aspose.cells/xmlloadoptions/auto_filter) | Gibt an, ob beim Laden der Dateien eine automatische Filterung der Daten erfolgen soll.|
| [font_configs](/cells/python-net/de/aspose.cells/xmlloadoptions/font_configs) | Ruft einzelne Schriftartkonfigurationen ab und legt sie fest.<br/> Funktioniert nur für [`Workbook`](/cells/python-net/de/aspose.cells/workbook), das diese [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) zum Laden verwendet.|
| [ignore_useless_shapes](/cells/python-net/de/aspose.cells/xmlloadoptions/ignore_useless_shapes) | Gibt an, ob unnötige Formen ignoriert werden.|
| [preserve_padding_spaces_in_formula](/cells/python-net/de/aspose.cells/xmlloadoptions/preserve_padding_spaces_in_formula) | Gibt an, ob die Leerzeichen und Zeilenumbrüche zwischen den Formel-Tokens beibehalten werden sollen.<br/>beim Abrufen und Festlegen von Formeln.<br/> Der Standardwert ist „false“.|
| [start_cell](/cells/python-net/de/aspose.cells/xmlloadoptions/start_cell) | Ruft die Startzelle ab und legt sie fest.|
| [is_xml_map](/cells/python-net/de/aspose.cells/xmlloadoptions/is_xml_map) | Gibt an, ob XML Excel zugeordnet wird.<br/> Der Standardwert ist „false“.|
| [contains_multiple_worksheets](/cells/python-net/de/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Gibt an, ob XML als mehrere Arbeitsblätter importiert wird.|
| [convert_numeric_or_date](/cells/python-net/de/aspose.cells/xmlloadoptions/convert_numeric_or_date) | Gibt an, ob der Wert in der XML-Datei in eine Zahl oder ein Datum konvertiert wird.|
| [number_format](/cells/python-net/de/aspose.cells/xmlloadoptions/number_format) | Ruft das Format des numerischen Werts ab und legt es fest.|
| [date_format](/cells/python-net/de/aspose.cells/xmlloadoptions/date_format) | Ruft das Format des Datumswerts ab und legt es fest.|
| [ignore_root_attributes](/cells/python-net/de/aspose.cells/xmlloadoptions/ignore_root_attributes) | Gibt an, ob Attribute des Stammelements ignoriert werden sollen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/de/aspose.cells/xmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Legt die Standarddruckpapiergröße anhand der Standardeinstellungen des Druckers fest.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
* Klasse [`XmlLoadOptions`](/cells/python-net/de/aspose.cells/xmlloadoptions)
