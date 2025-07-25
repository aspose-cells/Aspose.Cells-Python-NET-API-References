---
title: GlobalizationSettings Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 740
url: /de/aspose.cells/globalizationsettings/
is_root: false
---
##  GlobalizationSettings Klasse
Stellt die Globalisierungseinstellungen dar.



Der Typ GlobalizationSettings macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/__init__/#) | Erstellt eine neue Instanz von GlobalizationSettings|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [chart_settings](/cells/python-net/de/aspose.cells/globalizationsettings/chart_settings) | Ruft die Globalisierungseinstellungen für das Diagramm ab oder legt sie fest.|
| [pivot_settings](/cells/python-net/de/aspose.cells/globalizationsettings/pivot_settings) | Ruft die Globalisierungseinstellungen für die Pivot-Tabelle ab oder legt sie fest.|
| [list_separator](/cells/python-net/de/aspose.cells/globalizationsettings/list_separator) | Ruft das Trennzeichen für Listen, Funktionsparameter usw. ab.|
| [row_separator_of_formula_array](/cells/python-net/de/aspose.cells/globalizationsettings/row_separator_of_formula_array) | Ruft das Trennzeichen für Zeilen in Array-Daten in der Formel ab.|
| [column_separator_of_formula_array](/cells/python-net/de/aspose.cells/globalizationsettings/column_separator_of_formula_array) |Ruft das Trennzeichen für die Elemente in den Zeilendaten des Arrays in der Formel ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_pivot_total_name/#) | Ruft den Namen der Beschriftung „Gesamt“ in der PivotTable ab.<br/> Sie müssen diese Methode überschreiben, wenn die PivotTable zwei oder mehr PivotFields im Datenbereich enthält.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_pivot_grand_total_name/#) | Ruft den Namen der Beschriftung „Gesamtsumme“ in der PivotTable ab.|
| [`get_multiple_items_name(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_multiple_items_name/#) | Ruft den Namen der Beschriftung „(Mehrere Elemente)“ in der PivotTable ab.|
| [`get_all_name(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_all_name/#) | Ruft den Namen der Beschriftung „(Alle)“ in der PivotTable ab.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_protection_name_of_pivot_table/#) | Ruft den Schutznamen in der PivotTable ab.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_column_labels_of_pivot_table/#) | Ruft den Namen der Beschriftung „Spaltenbeschriftungen“ in der PivotTable ab.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_row_labels_name_of_pivot_table/#) | Ruft den Namen der Beschriftung „Zeilenbeschriftungen“ in der PivotTable ab.|
| [`get_empty_data_name(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_empty_data_name/#) | Ruft den Namen der Beschriftung „(leer)“ in der PivotTable ab.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_data_field_header_name_of_pivot_table/#) | Ruft den Namen der Wertebereichsfeldüberschrift in der PivotTable ab.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | Ruft den Namen des Typs [`PivotFieldSubtotalType`](/cells/python-net/de/aspose.cells.pivot/pivotfieldsubtotaltype) in der PivotTable ab.|
| [`get_total_name(self, function_type)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Ruft den vollständigen Namen der Funktion ab.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Ruft den Gesamtnamen der Funktion ab.|
| [`get_default_sheet_name(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_default_sheet_name/#) |Ruft den Standardblattnamen zum automatischen Hinzufügen eines Arbeitsblatts ab.<br/> Der Standardwert ist „Blatt“.|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_table_row_type_of_headers/#) | Ruft den Typnamen der Tabellenzeilen ab, der aus der Tabellenüberschrift besteht.<br/> Der Standardwert ist „Überschriften“, daher stellt in der Formel „#Überschriften“ die Tabellenüberschrift dar.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_table_row_type_of_data/#) | Ruft den Typnamen der Tabellenzeilen ab, die aus dem Datenbereich der referenzierten Tabelle bestehen.<br/> Der Standardwert ist „Daten“, daher stellt in der Formel „#Daten“ den Datenbereich der Tabelle dar.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_table_row_type_of_all/#) | Ruft den Typnamen der Tabellenzeilen ab, die aus allen Zeilen in der referenzierten Tabelle bestehen.<br/> Der Standardwert ist „Alle“, daher stellt „#Alle“ in der Formel alle Zeilen in der referenzierten Tabelle dar.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_table_row_type_of_totals/#) | Ruft den Typnamen der Tabellenzeilen ab, die aus der Gesamtzeile der referenzierten Tabelle bestehen.<br/> Der Standardwert ist „Summen“, daher stellt „#Summen“ in der Formel die Gesamtzeile der referenzierten Tabelle dar.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_table_row_type_of_current/#) | Ruft den Typnamen der Tabellenzeilen ab, die aus der aktuellen Zeile in der referenzierten Tabelle bestehen.<br/>Der Standardwert ist „Diese Zeile“, daher stellt in der Formel „#Diese Zeile“ die aktuelle Zeile in der referenzierten Tabelle dar.|
| [`get_error_value_string(self, err)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_error_value_string/#str) | Ruft den Anzeigezeichenfolgenwert für den Fehlerwert der Zelle ab|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_boolean_value_string/#bool) | Ruft den Anzeige-Stringwert für den Booleschen Wert der Zelle ab|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_local_function_name/#str) | Ruft den lokalabhängigen Funktionsnamen entsprechend dem angegebenen Standardfunktionsnamen ab.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_standard_function_name/#str) | Ruft den Standardfunktionsnamen entsprechend dem angegebenen gebietsschemaabhängigen Funktionsnamen ab.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_local_built_in_name/#str) | Ruft den gebietsschemaabhängigen Text für den integrierten Namen gemäß dem angegebenen Standardtext ab.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_standard_built_in_name/#str) | Ruft den Standardtext des integrierten Namens gemäß dem angegebenen gebietsschemaabhängigen Text ab.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_standard_header_footer_font_style_name/#str) | Ruft den standardmäßigen englischen Schriftstilnamen (Normal, Fett, Kursiv) für Kopf-/Fußzeilen entsprechend dem angegebenen lokalen Schriftstilnamen ab.|
| [`get_comment_title_name(self, type)`](/cells/python-net/de/aspose.cells/globalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Ruft den länderabhängigen Kommentartitelnamen entsprechend dem Kommentartiteltyp ab.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/de/aspose.cells/globalizationsettings/compare/#str-str-bool) | Vergleicht zwei Zeichenfolgenwerte gemäß bestimmten Sortierregeln.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`PivotFieldSubtotalType`](/cells/python-net/de/aspose.cells.pivot/pivotfieldsubtotaltype)
