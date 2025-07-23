---
title: Workbook Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1570
url: /de/aspose.cells/workbook/
is_root: false
---
##  Workbook Klasse
Stellt ein Stammobjekt zum Erstellen einer Excel-Tabelle dar.



Der Typ Workbook macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/workbook/__init__/#) | Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook).|
| [`__init__(self, file_format_type)`](/cells/python-net/de/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) | Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook).|
| [`__init__(self, file)`](/cells/python-net/de/aspose.cells/workbook/__init__/#str) | Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet eine Datei.|
| [`__init__(self, stream)`](/cells/python-net/de/aspose.cells/workbook/__init__/#io.rawiobase) | Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet einen Stream.|
| [`__init__(self, file, load_options)`](/cells/python-net/de/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) | Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet eine Datei.|
| [`__init__(self, stream, load_options)`](/cells/python-net/de/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) | Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet den Stream.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [settings](/cells/python-net/de/aspose.cells/workbook/settings) | Stellt die Arbeitsmappeneinstellungen dar.|
| [worksheets](/cells/python-net/de/aspose.cells/workbook/worksheets) | Ruft die Sammlung [`WorksheetCollection`](/cells/python-net/de/aspose.cells/worksheetcollection) in der Tabelle ab.|
| [is_licensed](/cells/python-net/de/aspose.cells/workbook/is_licensed) | Gibt an, ob eine Lizenz festgelegt ist.|
| [colors](/cells/python-net/de/aspose.cells/workbook/colors) | Gibt Farben in der Palette für die Tabelle zurück.|
| [count_of_styles_in_pool](/cells/python-net/de/aspose.cells/workbook/count_of_styles_in_pool) | Ruft die Anzahl der Stile im Stilpool ab.|
| [default_style](/cells/python-net/de/aspose.cells/workbook/default_style) | Ruft das Standardobjekt [`Style`](/cells/python-net/de/aspose.cells/style) der Arbeitsmappe ab oder legt es fest.|
| [is_digitally_signed](/cells/python-net/de/aspose.cells/workbook/is_digitally_signed) | Gibt an, ob diese Tabelle digital signiert ist.|
| [is_workbook_protected_with_password](/cells/python-net/de/aspose.cells/workbook/is_workbook_protected_with_password) | Gibt an, ob die Struktur oder das Fenster mit einem Passwort geschützt ist.|
| [vba_project](/cells/python-net/de/aspose.cells/workbook/vba_project) |Ruft die [`Workbook.vba_project`](/cells/python-net/de/aspose.cells/workbook#vba_project) in einer Tabelle ab.|
| [has_macro](/cells/python-net/de/aspose.cells/workbook/has_macro) | Gibt an, ob diese Tabelle Makros/VBA enthält.|
| [has_revisions](/cells/python-net/de/aspose.cells/workbook/has_revisions) | Ruft ab, ob die Arbeitsmappe nachverfolgte Änderungen enthält|
| [file_name](/cells/python-net/de/aspose.cells/workbook/file_name) | Ruft den aktuellen Dateinamen ab und legt ihn fest.|
| [cells_data_table_factory](/cells/python-net/de/aspose.cells/workbook/cells_data_table_factory) | Ruft die Factory zum Erstellen von ICellsDataTable aus benutzerdefinierten Objekten ab.|
| [data_sorter](/cells/python-net/de/aspose.cells/workbook/data_sorter) | Ruft ein DataSorter-Objekt zum Sortieren von Daten ab.|
| [theme](/cells/python-net/de/aspose.cells/workbook/theme) | Ruft den Designnamen ab.|
| [built_in_document_properties](/cells/python-net/de/aspose.cells/workbook/built_in_document_properties) | Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle integrierten Dokumenteigenschaften der Tabelle darstellt.|
| [custom_document_properties](/cells/python-net/de/aspose.cells/workbook/custom_document_properties) | Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle benutzerdefinierten Dokumenteigenschaften der Tabelle darstellt.|
| [file_format](/cells/python-net/de/aspose.cells/workbook/file_format) | Ruft das Dateiformat ab und legt es fest.|
| [has_custom_function](/cells/python-net/de/aspose.cells/workbook/has_custom_function) | Erkennt, ob in dieser Arbeitsmappe eine benutzerdefinierte Funktion verwendet wird.<br/> wie etwa in der Zellformel, in definierten Namen ...|
| [content_type_properties](/cells/python-net/de/aspose.cells/workbook/content_type_properties) | Ruft die Liste der [`ContentTypeProperty`](/cells/python-net/de/aspose.cells.properties/contenttypeproperty) Objekte in der Arbeitsmappe ab.|
| [custom_xml_parts](/cells/python-net/de/aspose.cells/workbook/custom_xml_parts) | Stellt einen benutzerdefinierten XML-Datenspeicherteil dar (benutzerdefinierte XML-Daten innerhalb eines Pakets).|
| [data_mashup](/cells/python-net/de/aspose.cells/workbook/data_mashup) | Ruft Mashup-Daten ab.|
| [ribbon_xml](/cells/python-net/de/aspose.cells/workbook/ribbon_xml) | Ruft die XML-Datei ab und legt sie fest, die die Menüband-Benutzeroberfläche definiert.|
| [absolute_path](/cells/python-net/de/aspose.cells/workbook/absolute_path) | Ruft den absoluten Pfad der Datei ab und legt ihn fest.|
| [data_connections](/cells/python-net/de/aspose.cells/workbook/data_connections) |Ruft die ExternalConnection-Sammlung ab.|
| [data_model](/cells/python-net/de/aspose.cells/workbook/data_model) | Ruft das Datenmodell in der Arbeitsmappe ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/de/aspose.cells/workbook/save/#str-aspose.cells.saveformat) | Speichert die Arbeitsmappe auf der Festplatte.|
| [`save(self, file_name)`](/cells/python-net/de/aspose.cells/workbook/save/#str) | Speichern Sie die Arbeitsmappe auf der Festplatte.|
| [`save(self, file_name, save_options)`](/cells/python-net/de/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) | Speichert die Arbeitsmappe auf der Festplatte.|
| [`save(self, stream, save_format)`](/cells/python-net/de/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) | Speichert die Arbeitsmappe im Stream.|
| [`save(self, stream, save_options)`](/cells/python-net/de/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) | Speichert die Arbeitsmappe im Stream.|
| [`create_style(self)`](/cells/python-net/de/aspose.cells/workbook/create_style/#) | Erstellt einen neuen Stil.|
| [`create_style(self, clone_default_style)`](/cells/python-net/de/aspose.cells/workbook/create_style/#bool) | Erstellt einen neuen Stil.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-str) | Ersetzt den Wert einer Zelle durch eine neue Zeichenfolge.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-int) | Ersetzt den Wert einer Zelle durch eine neue Ganzzahl.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-float) | Ersetzt den Wert einer Zelle durch einen neuen Double-Wert.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-list-bool) | Ersetzt den Wert einer Zelle durch ein neues Zeichenfolgenarray.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-list-bool) | Ersetzt die Werte der Zellen durch ein ganzzahliges Array.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-list-bool) | Ersetzt die Zellenwerte durch ein doppeltes Array.|
| [`replace(self, bool_value, new_value)`](/cells/python-net/de/aspose.cells/workbook/replace/#bool-any) | Ersetzt die Werte der Zellen durch neue Daten.|
| [`replace(self, int_value, new_value)`](/cells/python-net/de/aspose.cells/workbook/replace/#int-any) | Ersetzt die Werte der Zellen durch neue Daten.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/de/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) | Ersetzt den Wert einer Zelle durch eine neue Zeichenfolge.|
| [`copy(self, source, copy_options)`](/cells/python-net/de/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) | Kopiert ein anderes Workbook-Objekt.|
| [`copy(self, source)`](/cells/python-net/de/aspose.cells/workbook/copy/#aspose.cells.workbook) | Kopiert Daten aus einem Quell-Workbook-Objekt.|
| [`calculate_formula(self)`](/cells/python-net/de/aspose.cells/workbook/calculate_formula/#) | Berechnet das Ergebnis von Formeln.|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/de/aspose.cells/workbook/calculate_formula/#bool) | Berechnet das Ergebnis von Formeln.|
| [`calculate_formula(self, options)`](/cells/python-net/de/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) | Berechnungsformeln in dieser Arbeitsmappe.|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/de/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Aktualisiert dynamische Array-Formeln (Überlauf in einen neuen Bereich benachbarter Zellen entsprechend den aktuellen Daten)<br/> Andere Formeln in der Arbeitsmappe werden nicht rekursiv berechnet, selbst wenn sie von dynamischen Arrayformeln verwendet wurden.|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/de/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |Aktualisiert dynamische Array-Formeln (Überlauf in einen neuen Bereich benachbarter Zellen entsprechend den aktuellen Daten)|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/de/aspose.cells/workbook/import_xml/#str-str-int-int) | Importiert/aktualisiert eine XML-Datendatei in die Arbeitsmappe.|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/de/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) | Importiert/aktualisiert eine XML-Datendatei in die Arbeitsmappe.|
| [`export_xml(self, map_name, path)`](/cells/python-net/de/aspose.cells/workbook/export_xml/#str-str) | Exportieren Sie XML-Daten, die durch die angegebene XML-Zuordnung verknüpft sind.|
| [`export_xml(self, map_name, stream)`](/cells/python-net/de/aspose.cells/workbook/export_xml/#str-io.rawiobase) | XML-Daten exportieren.|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/de/aspose.cells/workbook/parse_formulas/#bool) | Analysiert alle Formeln, die beim Laden aus der Vorlagendatei oder beim Festlegen in einer Zelle nicht analysiert wurden.|
| [`start_access_cache(self, opts)`](/cells/python-net/de/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) | Startet die Sitzung, die Caches für den Datenzugriff verwendet.|
| [`close_access_cache(self, opts)`](/cells/python-net/de/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) | Schließt die Sitzung, die Caches für den Datenzugriff verwendet.|
| [`remove_unused_styles(self)`](/cells/python-net/de/aspose.cells/workbook/remove_unused_styles/#) | Entfernen Sie alle nicht verwendeten Stile.|
| [`create_builtin_style(self, type)`](/cells/python-net/de/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) | Erstellt einen integrierten Stil nach dem angegebenen Typ.|
| [`create_cells_color(self)`](/cells/python-net/de/aspose.cells/workbook/create_cells_color/#) | Erstellt ein [`CellsColor`](/cells/python-net/de/aspose.cells/cellscolor)-Objekt.|
| [`combine(self, second_workbook)`](/cells/python-net/de/aspose.cells/workbook/combine/#aspose.cells.workbook) | Kombiniert ein anderes Workbook-Objekt.|
| [`get_style_in_pool(self, index)`](/cells/python-net/de/aspose.cells/workbook/get_style_in_pool/#int) | Ruft den Stil im Stilpool ab.<br/>Alle Stile in der Arbeitsmappe werden in einem Pool gesammelt.<br/> In den Zellen befindet sich lediglich ein einfacher Referenzindex.|
| [`get_fonts(self)`](/cells/python-net/de/aspose.cells/workbook/get_fonts/#) | Ruft alle Schriftarten im Stilpool ab.|
| [`get_named_style(self, name)`](/cells/python-net/de/aspose.cells/workbook/get_named_style/#str) | Ruft den benannten Stil im Stilpool ab.|
| [`merge_named_styles(self, source)`](/cells/python-net/de/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) | Fügt benannte Stile aus der anderen Excel-Datei zusammen.|
| [`change_palette(self, color, index)`](/cells/python-net/de/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) | Ändert die Palette für die Tabelle im angegebenen Index.|
| [`is_color_in_palette(self, color)`](/cells/python-net/de/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) | Überprüft, ob eine Farbe in der Palette für die Tabelle vorhanden ist.|
| [`get_matching_color(self, raw_color)`](/cells/python-net/de/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |Finden Sie die am besten passende Farbe in der aktuellen Palette.|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/de/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) | Legen Sie die Verschlüsselungsoptionen fest.|
| [`protect(self, protection_type, password)`](/cells/python-net/de/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) | Schützt eine Arbeitsmappe.|
| [`protect_shared_workbook(self, password)`](/cells/python-net/de/aspose.cells/workbook/protect_shared_workbook/#str) | Schützt eine freigegebene Arbeitsmappe.|
| [`unprotect(self, password)`](/cells/python-net/de/aspose.cells/workbook/unprotect/#str) | Hebt den Schutz einer Arbeitsmappe auf.|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/de/aspose.cells/workbook/unprotect_shared_workbook/#str) | Hebt den Schutz einer freigegebenen Arbeitsmappe auf.|
| [`remove_macro(self)`](/cells/python-net/de/aspose.cells/workbook/remove_macro/#) | Entfernt VBA/Makro aus dieser Tabelle.|
| [`remove_digital_signature(self)`](/cells/python-net/de/aspose.cells/workbook/remove_digital_signature/#) | Entfernt die digitale Signatur aus dieser Tabelle.|
| [`accept_all_revisions(self)`](/cells/python-net/de/aspose.cells/workbook/accept_all_revisions/#) | Akzeptiert alle nachverfolgten Änderungen in der Arbeitsmappe.|
| [`remove_external_links(self)`](/cells/python-net/de/aspose.cells/workbook/remove_external_links/#) | Entfernt alle externen Links in der Arbeitsmappe.|
| [`get_theme_color(self, type)`](/cells/python-net/de/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) | Ruft die Designfarbe ab.|
| [`set_theme_color(self, type, color)`](/cells/python-net/de/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) | Legt die Themenfarbe fest|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/de/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) | Passt das Thema an.|
| [`copy_theme(self, source)`](/cells/python-net/de/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) | Kopiert das Design aus einer anderen Arbeitsmappe.|
| [`has_exernal_links(self)`](/cells/python-net/de/aspose.cells/workbook/has_exernal_links/#) | Gibt an, ob diese Arbeitsmappe externe Links zu anderen Datenquellen enthält.|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/de/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) | Aktualisiert die Definition benutzerdefinierter Funktionen.|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/de/aspose.cells/workbook/update_linked_data_source/#list) | Wenn diese Arbeitsmappe externe Links zu anderen Datenquellen enthält,<br/> Aspose.Cells versucht, die neuesten Daten aus den angegebenen Quellen abzurufen.|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/de/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Legt eine digitale Signatur für eine Tabellenkalkulationsdatei fest (Excel 2007 und höher).|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/de/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Fügt einer OOXML-Tabellenkalkulationsdatei eine digitale Signatur hinzu (Excel 2007 und höher).|
| [`get_digital_signature(self)`](/cells/python-net/de/aspose.cells/workbook/get_digital_signature/#) |Ruft die digitale Signatur aus der Datei ab.|
| [`remove_personal_information(self)`](/cells/python-net/de/aspose.cells/workbook/remove_personal_information/#) | Entfernt persönliche Informationen.|
| [`close(self)`](/cells/python-net/de/aspose.cells/workbook/close/#) | Dispose() wird vom Wrapper seit dem Protokoll Python übersprungen|



###  Bemerkungen

Die Klasse Workbook bezeichnet eine Excel-Tabelle. Jede Tabelle kann mehrere Arbeitsblätter enthalten.
Die grundlegende Funktion der Klasse besteht darin, native Excel-Dateien zu öffnen und zu speichern.
Die Klasse verfügt über einige erweiterte Funktionen wie das Kopieren von Daten aus anderen Arbeitsmappen, das Kombinieren zweier Arbeitsmappen, das Konvertieren von Excel in PDF, das Rendern von Excel in ein Bild und das Schützen der Excel-Tabelle.

###  Beispiel

Das folgende Beispiel lädt eine Workbook aus einer Excel-Datei namens designer.xls und macht die horizontalen und vertikalen Bildlaufleisten unsichtbar.
 Anschließend werden innerhalb der Tabelle zwei Zeichenfolgenwerte durch einen Integer-Wert bzw. einen Zeichenfolgenwert ersetzt und die Arbeitsmappe schließlich als Excel-XLSX-Datei gespeichert.

```python
from aspose.cells import Workbook

# Open a designer file
designerFile = "designer.xls"
workbook = Workbook(designerFile)
# Set scroll bars
workbook.settings.is_h_scroll_bar_visible = False
workbook.settings.is_v_scroll_bar_visible = False
# Replace the placeholder string with new values
newInt = 100
workbook.replace("OldInt", newInt)
newString = "Hello!"
workbook.replace("OldString", newString)
workbook.save("result.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`CellsColor`](/cells/python-net/de/aspose.cells/cellscolor)
* Klasse [`ContentTypeProperty`](/cells/python-net/de/aspose.cells.properties/contenttypeproperty)
* Klasse [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)
* Klasse [`Style`](/cells/python-net/de/aspose.cells/style)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
* Klasse [`WorksheetCollection`](/cells/python-net/de/aspose.cells/worksheetcollection)
