---
title: PivotTable Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 230
url: /de/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable Klasse
Zusammenfassende Beschreibung für PivotTable.



Der Typ PivotTable macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/de/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Gibt an, ob die PivotTable beim Aktualisieren mit Excel2003 kompatibel ist.<br/>Wenn wahr, muss eine Zeichenfolge kleiner oder gleich 255 Zeichen sein. Wenn die Zeichenfolge also größer als 255 Zeichen ist,<br/>es wird abgeschnitten. Wenn „false“ festgelegt ist, unterliegt eine Zeichenfolge nicht der oben genannten Einschränkung.<br/> Der Standardwert ist „true“.|
| [refreshed_by_who](/cells/python-net/de/aspose.cells.pivot/pivottable/refreshed_by_who) | Ruft den Namen des letzten Benutzers ab, der diese PivotTable aktualisiert hat|
| [refresh_date](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_date) | Ruft das Datum und die Uhrzeit der letzten Aktualisierung der PivotTable ab.|
| [pivot_table_style_name](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_table_style_name) | Ruft den PivotTable-Stilnamen ab und legt ihn fest.|
| [pivot_table_style_type](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_table_style_type) | Ruft den integrierten PivotTable-Stil ab und legt ihn fest.|
| [column_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/column_fields) | Gibt ein PivotFields-Objekt zurück, das derzeit als Spaltenfelder angezeigt wird.|
| [row_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/row_fields) | Gibt ein PivotFields-Objekt zurück, das derzeit als Zeilenfelder angezeigt wird.|
| [page_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/page_fields) | Gibt ein PivotFields-Objekt zurück, das derzeit als Seitenfelder angezeigt wird.|
| [data_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/data_fields) | Ruft ein PivotField-Objekt ab, das alle Datenfelder in einer PivotTable darstellt.<br/>Schreibgeschützt. Die Initialisierung erfolgt nur, wenn in den DataPiovtFiels zwei oder mehr Datenfelder vorhanden sind.<br/> Es wird nur verwendet, um DataPivotField zum Zeilen-/Spaltenbereich der PivotTable hinzuzufügen. Der Standardwert ist der Zeilenbereich.|
| [data_field](/cells/python-net/de/aspose.cells.pivot/pivottable/data_field) |Ruft ein [`PivotField`](/cells/python-net/de/aspose.cells.pivot/pivotfield)-Objekt ab, das alle Datenfelder in einer PivotTable darstellt.<br/>Schreibgeschützt.<br/>Es wird nur erstellt, wenn sich im Datenbereich zwei oder mehr Datenfelder befinden.<br/> Standardmäßig befindet es sich im Zeilenbereich. Sie können es mit der Methode PivotTable.AddFieldToArea() in den Zeilen-/Spaltenbereich ziehen.|
| [base_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/base_fields) | Gibt alle Basis-Pivotfelder in der PivotTable zurück.|
| [pivot_filters](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_filters) | Gibt alle Filter der Pivotfelder in der Pivottabelle zurück.|
| [column_range](/cells/python-net/de/aspose.cells.pivot/pivottable/column_range) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt<br/> der den Spaltenbereich im PivotTable-Bericht enthält. Schreibgeschützt.|
| [row_range](/cells/python-net/de/aspose.cells.pivot/pivottable/row_range) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt<br/> der den Zeilenbereich im PivotTable-Bericht enthält. Schreibgeschützt.|
| [data_body_range](/cells/python-net/de/aspose.cells.pivot/pivottable/data_body_range) | Gibt ein [`CellArea`](/cells/python-net/de/aspose.cells/cellarea)-Objekt zurück, das den Bereich darstellt, der den Datenbereich enthält<br/> in der Liste zwischen der Kopfzeile und der Einfügezeile. Schreibgeschützt.|
| [table_range1](/cells/python-net/de/aspose.cells.pivot/pivottable/table_range1) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt, der den gesamten PivotTable-Bericht enthält.<br/> enthält aber keine Seitenfelder. Schreibgeschützt.|
| [table_range2](/cells/python-net/de/aspose.cells.pivot/pivottable/table_range2) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt, der den gesamten PivotTable-Bericht enthält.<br/> enthält Seitenfelder. Schreibgeschützt.|
| [is_grid_drop_zones](/cells/python-net/de/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Gibt an, ob der PivotTable-Bericht das klassische PivotTable-Layout anzeigt.<br/> (ermöglicht das Ziehen von Feldern im Raster)|
| [show_column_grand_totals](/cells/python-net/de/aspose.cells.pivot/pivottable/show_column_grand_totals) |Gibt an, ob Gesamtsummen für Spalten dieser Pivot-Tabelle angezeigt werden sollen.|
| [show_row_grand_totals](/cells/python-net/de/aspose.cells.pivot/pivottable/show_row_grand_totals) | Gibt an, ob Gesamtsummen für die Zeilen der Pivot-Tabelle angezeigt werden sollen.|
| [column_grand](/cells/python-net/de/aspose.cells.pivot/pivottable/column_grand) | Gibt an, ob der PivotTable-Bericht Gesamtsummen für Spalten anzeigt.|
| [row_grand](/cells/python-net/de/aspose.cells.pivot/pivottable/row_grand) | Gibt an, ob Gesamtsummen für die Zeilen dieser Pivot-Tabelle angezeigt werden sollen.|
| [display_null_string](/cells/python-net/de/aspose.cells.pivot/pivottable/display_null_string) | Gibt an, ob der PivotTable-Bericht eine benutzerdefinierte Zeichenfolge anzeigt, wenn der Wert null ist.|
| [null_string](/cells/python-net/de/aspose.cells.pivot/pivottable/null_string) | Ruft die Zeichenfolge ab, die in Zellen angezeigt wird, die Nullwerte enthalten<br/> wenn die Eigenschaft DisplayNullString true ist. Der Standardwert ist eine leere Zeichenfolge.|
| [display_error_string](/cells/python-net/de/aspose.cells.pivot/pivottable/display_error_string) | Gibt an, ob der PivotTable-Bericht in Zellen, die Fehler enthalten, eine benutzerdefinierte Zeichenfolge anzeigt.|
| [data_field_header_name](/cells/python-net/de/aspose.cells.pivot/pivottable/data_field_header_name) | Ruft den Namen der Wertebereichsfeldüberschrift in der PivotTable ab und legt ihn fest.|
| [error_string](/cells/python-net/de/aspose.cells.pivot/pivottable/error_string) | Ruft die Zeichenfolge ab, die in Zellen angezeigt wird, die Fehler enthalten<br/> wenn die Eigenschaft DisplayErrorString true ist. Der Standardwert ist eine leere Zeichenfolge.|
| [is_auto_format](/cells/python-net/de/aspose.cells.pivot/pivottable/is_auto_format) | Gibt an, ob der PivotTable-Bericht automatisch formatiert wird.<br/>Kontrollkästchen "Tabelle automatisch formatieren", das sich in der PivotTable-Option für Excel 2003 befindet|
| [autofit_column_width_on_update](/cells/python-net/de/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Gibt an, ob die Spaltenbreite beim Update automatisch angepasst wird|
| [auto_format_type](/cells/python-net/de/aspose.cells.pivot/pivottable/auto_format_type) | Ruft den automatischen Formattyp der PivotTable ab und legt ihn fest.|
| [has_blank_rows](/cells/python-net/de/aspose.cells.pivot/pivottable/has_blank_rows) | Gibt an, ob leere Zeilen hinzugefügt werden sollen.<br/> Diese Eigenschaft gilt nur für die automatischen PivotTable-Formattypen, bei denen leere Zeilen hinzugefügt werden müssen.|
| [merge_labels](/cells/python-net/de/aspose.cells.pivot/pivottable/merge_labels) | „True“, wenn die Beschriftungen der äußeren Zeilenelemente, Spaltenelemente, Zwischensummen und Gesamtsummen des angegebenen PivotTable-Berichts verbundene Zellen verwenden.|
| [preserve_formatting](/cells/python-net/de/aspose.cells.pivot/pivottable/preserve_formatting) | Gibt an, ob die Formatierung beibehalten wird, wenn die PivotTable aktualisiert oder neu berechnet wird.|
| [show_drill](/cells/python-net/de/aspose.cells.pivot/pivottable/show_drill) | Ruft ab und legt fest, ob Schaltflächen zum Erweitern/Reduzieren angezeigt werden.|
| [enable_drilldown](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_drilldown) | Ruft ab, ob Drilldown aktiviert ist.|
| [enable_field_dialog](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_field_dialog) | Gibt an, ob das Dialogfeld PivotTable-Feld verfügbar ist<br/> wenn der Benutzer auf das PivotTable-Feld doppelklickt.|
| [enable_field_list](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_field_list) | Gibt an, ob die Feldliste für die PivotTable in der Excel-Ansicht verfügbar ist.|
| [enable_wizard](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_wizard) | Gibt an, ob der PivotTable-Assistent verfügbar ist.|
| [subtotal_hidden_page_items](/cells/python-net/de/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |Gibt an, ob ausgeblendete Seitenfeldelemente im PivotTable-Bericht<br/>sind in Zeilen- und Spaltenzwischensummen, Blocksummen und Gesamtsummen enthalten.<br/> Der Standardwert ist „False“.|
| [grand_total_name](/cells/python-net/de/aspose.cells.pivot/pivottable/grand_total_name) | Gibt die Beschriftung zurück, die in der Spalten- oder Zeilenüberschrift der Gesamtsumme angezeigt wird.<br/> Der Standardwert ist die Zeichenfolge „Gesamtsumme“.|
| [manual_update](/cells/python-net/de/aspose.cells.pivot/pivottable/manual_update) | Gibt an, ob der PivotTable-Bericht nur auf Anforderung des Benutzers neu berechnet wird.|
| [is_multiple_field_filters](/cells/python-net/de/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Gibt einen Booleschen Wert an, der angibt, ob für die Felder einer PivotTable mehrere Filter festgelegt werden können.|
| [allow_multiple_filters_per_field](/cells/python-net/de/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | Gibt einen Booleschen Wert an, der angibt, ob für die Felder einer PivotTable mehrere Filter festgelegt werden können.|
| [missing_items_limit](/cells/python-net/de/aspose.cells.pivot/pivottable/missing_items_limit) | Gibt einen Booleschen Wert an, der angibt, ob für die Felder einer PivotTable mehrere Filter festgelegt werden können.|
| [enable_data_value_editing](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_data_value_editing) | Gibt einen Booleschen Wert an, der angibt, ob der Benutzer die Zellen im Datenbereich der PivotTable bearbeiten darf.<br/> Aktivieren Sie die Zellenbearbeitung im Wertebereich|
| [show_data_tips](/cells/python-net/de/aspose.cells.pivot/pivottable/show_data_tips) | Gibt einen Booleschen Wert an, der angibt, ob QuickInfos für PivotTable-Datenzellen angezeigt werden sollen.|
| [show_member_property_tips](/cells/python-net/de/aspose.cells.pivot/pivottable/show_member_property_tips) | Gibt einen Booleschen Wert an, der angibt, ob Informationen zu den Elementeigenschaftsinformationen aus den QuickInfos der PivotTable weggelassen werden sollen.|
| [show_values_row](/cells/python-net/de/aspose.cells.pivot/pivottable/show_values_row) | Gibt an, ob die Wertezeile angezeigt wird.|
| [show_empty_col](/cells/python-net/de/aspose.cells.pivot/pivottable/show_empty_col) | Gibt an, ob leere Spalten in die Tabelle aufgenommen werden sollen|
| [show_empty_row](/cells/python-net/de/aspose.cells.pivot/pivottable/show_empty_row) |Gibt an, ob leere Zeilen in die Tabelle aufgenommen werden sollen.|
| [field_list_sort_ascending](/cells/python-net/de/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Gibt an, ob die Felder in der PivotTable in der Feldliste in einer nicht standardmäßigen Reihenfolge sortiert sind.|
| [print_drill](/cells/python-net/de/aspose.cells.pivot/pivottable/print_drill) | Gibt einen Booleschen Wert an, der angibt, ob Drillindikatoren gedruckt werden sollen.<br/> Schaltflächen zum Erweitern/Reduzieren drucken, wenn sie in der Pivot-Tabelle angezeigt werden.|
| [alt_text_title](/cells/python-net/de/aspose.cells.pivot/pivottable/alt_text_title) | Ruft den Titel des Änderungstextes ab und legt ihn fest.|
| [alt_text_description](/cells/python-net/de/aspose.cells.pivot/pivottable/alt_text_description) | Ruft die Beschreibung des Alternativtextes ab.|
| [name](/cells/python-net/de/aspose.cells.pivot/pivottable/name) | Ruft den Namen der PivotTable ab|
| [column_header_caption](/cells/python-net/de/aspose.cells.pivot/pivottable/column_header_caption) | Ruft die Spaltenüberschrift der PivotTable ab.|
| [indent](/cells/python-net/de/aspose.cells.pivot/pivottable/indent) | Gibt die Einrückungsrate für die kompakte Achse an und kann verwendet werden, um das Berichtslayout auf die kompakte Form einzustellen.|
| [row_header_caption](/cells/python-net/de/aspose.cells.pivot/pivottable/row_header_caption) | Ruft die Zeilenüberschrift der PivotTable ab.|
| [show_row_header_caption](/cells/python-net/de/aspose.cells.pivot/pivottable/show_row_header_caption) | Gibt an, ob die Zeilenüberschrift im PivotTable-Bericht angezeigt wird<br/> Gibt an, ob Feldbeschriftungen und Filter-Dropdowns angezeigt werden|
| [custom_list_sort](/cells/python-net/de/aspose.cells.pivot/pivottable/custom_list_sort) | Gibt an, ob beim Sortieren der Daten die integrierte benutzerdefinierte Liste berücksichtigt wird|
| [pivot_format_conditions](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_format_conditions) | Ruft die Formatbedingungen der Pivot-Tabelle ab.|
| [conditional_formats](/cells/python-net/de/aspose.cells.pivot/pivottable/conditional_formats) | Ruft die bedingten Formate der Pivot-Tabelle ab.|
| [page_field_order](/cells/python-net/de/aspose.cells.pivot/pivottable/page_field_order) |Ruft die Reihenfolge ab und legt sie fest, in der Seitenfelder zum Layout des PivotTable-Berichts hinzugefügt werden.|
| [page_field_wrap_count](/cells/python-net/de/aspose.cells.pivot/pivottable/page_field_wrap_count) | Ruft die Anzahl der Seitenfelder in jeder Spalte oder Zeile im PivotTable-Bericht ab.|
| [tag](/cells/python-net/de/aspose.cells.pivot/pivottable/tag) | Ruft eine mit dem PivotTable-Bericht gespeicherte Zeichenfolge ab.|
| [save_data](/cells/python-net/de/aspose.cells.pivot/pivottable/save_data) | Gibt an, ob Daten für den PivotTable-Bericht mit der Arbeitsmappe gespeichert werden.|
| [refresh_data_on_opening_file](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Gibt an, ob beim Öffnen der Datei die Daten aktualisiert werden sollen.|
| [refresh_data_flag](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data_flag) | Gibt an, ob die Daten aktualisiert werden oder nicht.|
| [source_type](/cells/python-net/de/aspose.cells.pivot/pivottable/source_type) | Ruft den Datenquellentyp der Pivot-Tabelle ab.|
| [external_connection_data_source](/cells/python-net/de/aspose.cells.pivot/pivottable/external_connection_data_source) | Ruft die externe Verbindungsdatenquelle ab.|
| [data_source](/cells/python-net/de/aspose.cells.pivot/pivottable/data_source) | Ruft die Datenquelle der Pivot-Tabelle ab und legt sie fest.|
| [pivot_formats](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_formats) | Ruft die Auflistung der auf die PivotTable angewendeten Formate ab.|
| [item_print_titles](/cells/python-net/de/aspose.cells.pivot/pivottable/item_print_titles) | Gibt an, ob PivotItem-Namen oben auf jeder gedruckten Seite wiederholt werden sollen.|
| [repeat_items_on_each_printed_page](/cells/python-net/de/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | Gibt an, ob bei Pivot-Feldern in tabellarischer Form die Beschriftungen der Pivot-Elemente im Zeilenbereich auf jeder gedruckten Seite wiederholt werden.|
| [print_titles](/cells/python-net/de/aspose.cells.pivot/pivottable/print_titles) | Gibt an, ob die Drucktitel für das Arbeitsblatt basierend auf<br/> im PivotTable-Bericht. Der Standardwert ist „false“.|
| [display_immediate_items](/cells/python-net/de/aspose.cells.pivot/pivottable/display_immediate_items) |Gibt an, ob Elemente in den Zeilen- und Spaltenbereichen sichtbar sind<br/> wenn der Datenbereich der PivotTable leer ist. Der Standardwert ist „true“.|
| [is_selected](/cells/python-net/de/aspose.cells.pivot/pivottable/is_selected) | Gibt an, ob diese PivotTable ausgewählt ist.|
| [show_pivot_style_row_header](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Gibt an, ob der Stil auf die Zeilenüberschrift in der Pivot-Tabelle angewendet werden soll.|
| [show_pivot_style_column_header](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Gibt an, ob der Stil auf die Spaltenüberschrift in der Pivot-Tabelle angewendet werden soll.|
| [show_pivot_style_row_stripes](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Gibt an, ob die Zeilenstreifenformatierung angewendet wird.|
| [show_pivot_style_column_stripes](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Gibt an, ob für die Spalte eine Streifenformatierung angewendet wird.|
| [show_pivot_style_last_column](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Gibt an, ob die Spaltenformatierung angewendet wird.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/de/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | Entfernt ein Feld aus einem bestimmten Feldbereich|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/de/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | Entfernt ein Feld aus einem bestimmten Feldbereich|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/de/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Feld aus bestimmtem Feldbereich entfernen|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/de/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | Fügt das Feld dem bestimmten Bereich hinzu.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/de/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | Fügt das Feld dem bestimmten Bereich hinzu.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/de/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Fügt das Feld dem bestimmten Bereich hinzu.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/de/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Fügt dem Pivot-Feld ein berechnetes Feld hinzu.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/de/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Fügt dem Pivot-Feld ein berechnetes Feld hinzu und zieht es in den Datenbereich.|
| [`move(self, row, column)`](/cells/python-net/de/aspose.cells.pivot/pivottable/move/#int-int) | Verschiebt die PivotTable an eine andere Position im Arbeitsblatt.|
| [`move(self, dest_cell_name)`](/cells/python-net/de/aspose.cells.pivot/pivottable/move/#str) | Verschiebt die PivotTable an eine andere Position im Arbeitsblatt.|
| [`move_to(self, row, column)`](/cells/python-net/de/aspose.cells.pivot/pivottable/move_to/#int-int) | Verschiebt die PivotTable an eine andere Position im Arbeitsblatt.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/de/aspose.cells.pivot/pivottable/move_to/#str) | Verschiebt die PivotTable an eine andere Position im Arbeitsblatt.|
| [`get_source(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_source/#) | Holen Sie sich die Quelldaten der Pivot-Tabelle.|
| [`get_source(self, is_original)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_source/#bool) | Holen Sie sich die Quelldaten der Pivot-Tabelle.|
| [`refresh_data(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data/#) |Aktualisiert die Daten und Einstellungen der PivotTabelle aus ihrer Datenquelle.|
| [`refresh_data(self, option)`](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | Aktualisiert die Daten und Einstellungen der PivotTabelle aus ihrer Datenquelle mit Optionen.|
| [`calculate_data(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/calculate_data/#) | Berechnet die Daten der PivotTabelle in Zellen.|
| [`calculate_data(self, option)`](/cells/python-net/de/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | Pivot-Tabellen mit Optionen berechnen|
| [`format(self, pivot_area, style)`](/cells/python-net/de/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | Formatiert den ausgewählten Bereich der PivotTable.|
| [`format(self, ca, style)`](/cells/python-net/de/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | Formatiert den ausgewählten Bereich der PivotTable.|
| [`format(self, row, column, style)`](/cells/python-net/de/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | Formatieren Sie die Zelle im PivotTable-Bereich|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Legt die automatische Feldgruppierung durch die PivotTable fest.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | Legt die automatische Feldgruppierung durch die PivotTable fest.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Legt die manuelle Feldgruppe durch die PivotTable fest.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | Legt die manuelle Feldgruppe durch die PivotTable fest.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | Legt die manuelle Feldgruppe durch die PivotTable fest.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | Legt die manuelle Feldgruppe durch die PivotTable fest.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_ungroup/#int) | Legt die Aufhebung der Gruppierung durch die PivotTable fest|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/de/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | Legt die Aufhebung der Gruppierung durch die PivotTable fest|
| [`copy_style(self, pivot_table)`](/cells/python-net/de/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | Kopiert den benannten Stil aus einer anderen Pivot-Tabelle.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | Alle Berichtsfilterseiten entsprechend dem PivotField anzeigen, das PivotField muss sich in den PageFields befinden.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Zeigen Sie alle Berichtsfilterseiten entsprechend dem Namen des PivotFields an. Das PivotField muss sich in den PageFields befinden.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Alle Reportfilterseiten entsprechend dem Positionsindex in den PageFields anzeigen|
| [`get_fields(self, field_type)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | Ruft die spezifische Pivot-Feldliste nach Region ab.|
| [`fields(self, field_type)`](/cells/python-net/de/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | Ruft die spezifischen Felder nach Feldtyp ab.|
| [`get_source_data_connections(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_source_data_connections/#) |Ruft die externen Verbindungsdatenquellen ab.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | Ruft den Namen externer Quelldatenverbindungen ab.|
| [`change_data_source(self, source)`](/cells/python-net/de/aspose.cells.pivot/pivottable/change_data_source/#list) | Legen Sie die Quelldaten der PivotTabelle fest.|
| [`clear_data(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/clear_data/#) | Löschen der Daten und Formatierung der PivotTable|
| [`calculate_range(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/calculate_range/#) | Berechnet den Bereich der Pivottabelle.|
| [`format_all(self, style)`](/cells/python-net/de/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | Formatieren Sie alle Zellen im PivotTable-Bereich|
| [`format_row(self, row, style)`](/cells/python-net/de/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | Formatieren Sie die Zeilendaten im PivotTable-Bereich|
| [`select_area(self, ca)`](/cells/python-net/de/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | Wählen Sie einen Bereich der PivotTable-Ansicht aus.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | Zeigen Sie die Details eines Elements im Datenbereich in einer neuen Tabelle an.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | Ruft horizontale Seitenumbrüche dieser Pivot-Tabelle ab.|
| [`get_horizontal_breaks(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Ruft die Indexliste der horizontalen Seitenumbrüche in der Pivot-Tabelle ab|
| [`show_in_compact_form(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Legt das Layout der PivotTable in kompakter Form fest.|
| [`show_in_outline_form(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Legt das Layout der PivotTable in Gliederungsform fest.|
| [`show_in_tabular_form(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Legt das Layout der PivotTable in Tabellenform fest.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Ruft das Objekt [`Cell`](/cells/python-net/de/aspose.cells/cell) anhand des Anzeigenamens von PivotField ab.|
| [`get_children(self)`](/cells/python-net/de/aspose.cells.pivot/pivottable/get_children/#) | Ruft die untergeordneten Pivot-Tabellen ab, die diese Pivot-Tabellendaten als Datenquelle verwenden.|



###  Beispiel

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.pivot`](..)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
* Klasse [`CellArea`](/cells/python-net/de/aspose.cells/cellarea)
* Klasse [`PivotField`](/cells/python-net/de/aspose.cells.pivot/pivotfield)
