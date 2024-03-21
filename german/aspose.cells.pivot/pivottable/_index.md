---
title: PivotTable Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 180
url: /de/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable Klasse
Zusammenfassende Beschreibung für PivotTable.



Der Typ PivotTable macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/de/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Gibt an, ob die PivotTable beim Aktualisieren von PivotTable mit Excel2003 kompatibel ist.<br/>Wenn „true“, muss eine Zeichenfolge kleiner oder gleich 255 Zeichen sein. Wenn die Zeichenfolge also größer als 255 Zeichen ist,<br/>es wird abgeschnitten. Bei „false“ unterliegt eine Zeichenfolge nicht der oben genannten Einschränkung.<br/> Der Standardwert ist wahr.|
| [refreshed_by_who](/cells/python-net/de/aspose.cells.pivot/pivottable/refreshed_by_who) | Ruft den Namen des Benutzers ab, der die PivotTable zuletzt aktualisiert hat|
| [refresh_date](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_date) | Ruft das Datum ab, an dem die PivotTable zuletzt aktualisiert wurde.|
| [pivot_table_style_name](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_table_style_name) | Ruft den Namen des Pivottable-Stils ab und legt ihn fest.|
| [pivot_table_style_type](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_table_style_type) | Ruft den integrierten Pivot-Tabellenstil ab und legt ihn fest.|
| [column_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/column_fields) | Gibt ein PivotFields-Objekt zurück, das derzeit als Spaltenfelder angezeigt wird.|
| [row_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/row_fields) | Gibt ein PivotFields-Objekt zurück, das derzeit als Zeilenfelder angezeigt wird.|
| [page_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/page_fields) | Gibt ein PivotFields-Objekt zurück, das derzeit als Seitenfelder angezeigt wird.|
| [data_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/data_fields) | Ruft ein PivotField-Objekt ab, das alle Datenfelder in einer PivotTable darstellt.<br/>Schreibgeschützt. Es wäre nur dann init, wenn in den DataPiovtFiels zwei oder mehr Datenfelder vorhanden sind.<br/> Es wird nur zum Hinzufügen von DataPivotField zum Zeilen-/Spaltenbereich der PivotTable verwendet. Die Standardeinstellung ist im Zeilenbereich.|
| [data_field](/cells/python-net/de/aspose.cells.pivot/pivottable/data_field) | Ruft ein PivotField-Objekt ab, das alle Datenfelder in einer PivotTable darstellt.<br/>Schreibgeschützt. Es wäre nur dann init, wenn in den DataPiovtFiels zwei oder mehr Datenfelder vorhanden sind.<br/> Es wird nur zum Hinzufügen von DataPivotField zum Zeilen-/Spaltenbereich der PivotTable verwendet. Die Standardeinstellung ist im Zeilenbereich.|
| [base_fields](/cells/python-net/de/aspose.cells.pivot/pivottable/base_fields) | Gibt ein PivotFields-Objekt zurück, das alle Felder im PivotTable-Bericht enthält|
| [pivot_filters](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_filters) | Gibt ein PivotFilterCollection-Objekt zurück.|
| [column_range](/cells/python-net/de/aspose.cells.pivot/pivottable/column_range) |Gibt ein CellArea-Objekt zurück, das den Bereich darstellt<br/> das den Spaltenbereich im PivotTable-Bericht enthält. Schreibgeschützt.|
| [row_range](/cells/python-net/de/aspose.cells.pivot/pivottable/row_range) |Gibt ein CellArea-Objekt zurück, das den Bereich darstellt<br/> das den Zeilenbereich im PivotTable-Bericht enthält. Schreibgeschützt.|
| [data_body_range](/cells/python-net/de/aspose.cells.pivot/pivottable/data_body_range) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt, der den Datenbereich enthält<br/> in der Liste zwischen der Kopfzeile und der Einfügezeile. Schreibgeschützt.|
| [table_range1](/cells/python-net/de/aspose.cells.pivot/pivottable/table_range1) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt, der den gesamten PivotTable-Bericht enthält.<br/> enthält jedoch keine Seitenfelder. Schreibgeschützt.|
| [table_range2](/cells/python-net/de/aspose.cells.pivot/pivottable/table_range2) | Gibt ein CellArea-Objekt zurück, das den Bereich darstellt, der den gesamten PivotTable-Bericht enthält.<br/> Enthält Seitenfelder. Schreibgeschützt.|
| [column_grand](/cells/python-net/de/aspose.cells.pivot/pivottable/column_grand) | Gibt an, ob im PivotTable-Bericht Gesamtsummen für Spalten angezeigt werden.|
| [is_grid_drop_zones](/cells/python-net/de/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Gibt an, ob der PivotTable-Bericht das klassische PivotTable-Layout anzeigt.<br/> (ermöglicht das Ziehen von Feldern im Raster)|
| [row_grand](/cells/python-net/de/aspose.cells.pivot/pivottable/row_grand) | Gibt an, ob im PivotTable-Bericht Gesamtsummen für Zeilen angezeigt werden.|
| [display_null_string](/cells/python-net/de/aspose.cells.pivot/pivottable/display_null_string) | Gibt an, ob der PivotTable-Bericht eine benutzerdefinierte Zeichenfolge anzeigt<br/> in Zellen, die Nullwerte enthalten.|
| [null_string](/cells/python-net/de/aspose.cells.pivot/pivottable/null_string) | Ruft die Zeichenfolge ab, die in Zellen angezeigt wird, die Nullwerte enthalten<br/>wenn die DisplayNullString-Eigenschaft wahr ist. Der Standardwert ist eine leere Zeichenfolge.|
| [display_error_string](/cells/python-net/de/aspose.cells.pivot/pivottable/display_error_string) | Gibt an, ob der PivotTable-Bericht eine benutzerdefinierte Zeichenfolge in Zellen anzeigt, die Fehler enthalten.|
| [data_field_header_name](/cells/python-net/de/aspose.cells.pivot/pivottable/data_field_header_name) | Ruft den Namen des Wertebereichsfeldheaders in der PivotTable ab und legt ihn fest.|
| [error_string](/cells/python-net/de/aspose.cells.pivot/pivottable/error_string) | Ruft die Zeichenfolge ab, die in Zellen angezeigt wird, die Fehler enthalten<br/> wenn die DisplayErrorString-Eigenschaft wahr ist. Der Standardwert ist eine leere Zeichenfolge.|
| [is_auto_format](/cells/python-net/de/aspose.cells.pivot/pivottable/is_auto_format) | Gibt an, ob der PivotTable-Bericht automatisch formatiert wird.<br/> Kontrollkästchen „Tabelle automatisch formatieren“, das sich in der Pivottable-Option für Excel 2003 befindet|
| [autofit_column_width_on_update](/cells/python-net/de/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Gibt an, ob die Spaltenbreite bei der Aktualisierung automatisch angepasst wird|
| [auto_format_type](/cells/python-net/de/aspose.cells.pivot/pivottable/auto_format_type) | Ruft den automatischen Formattyp der PivotTable ab.|
| [has_blank_rows](/cells/python-net/de/aspose.cells.pivot/pivottable/has_blank_rows) | Gibt an, ob leere Zeilen hinzugefügt werden sollen.<br/> Diese Eigenschaft gilt nur für die automatischen PivotTable-Formattypen, bei denen leere Zeilen hinzugefügt werden müssen.|
| [merge_labels](/cells/python-net/de/aspose.cells.pivot/pivottable/merge_labels) | Gibt an, ob das äußere Zeilenelement, das Spaltenelement, die Zwischensumme usw. des angegebenen PivotTable-Berichts<br/> und Gesamtsummenbeschriftungen verwenden zusammengeführte Zellen.|
| [preserve_formatting](/cells/python-net/de/aspose.cells.pivot/pivottable/preserve_formatting) |Gibt an, ob die Formatierung beibehalten wird, wenn die PivotTable aktualisiert oder neu berechnet wird.|
| [show_drill](/cells/python-net/de/aspose.cells.pivot/pivottable/show_drill) | Ruft ab, ob Schaltflächen zum Erweitern/Reduzieren angezeigt werden.|
| [enable_drilldown](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_drilldown) | Ruft ab, ob Drilldown aktiviert ist.|
| [enable_field_dialog](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_field_dialog) | Gibt an, ob das Dialogfeld „PivotTable-Feld“ verfügbar ist<br/> wenn der Benutzer auf das PivotTable-Feld doppelklickt.|
| [enable_field_list](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_field_list) | Ruft ab, ob die Feldliste für die PivotTable aktiviert wird.|
| [enable_wizard](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_wizard) | Gibt an, ob der PivotTable-Assistent verfügbar ist.|
| [subtotal_hidden_page_items](/cells/python-net/de/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Gibt an, ob Seitenfeldelemente im PivotTable-Bericht ausgeblendet sind<br/>sind in Zeilen- und Spaltenzwischensummen, Blocksummen und Gesamtsummen enthalten.<br/> Der Standardwert ist False.|
| [grand_total_name](/cells/python-net/de/aspose.cells.pivot/pivottable/grand_total_name) | Gibt die Textzeichenfolgenbeschriftung zurück, die in der Gesamtsummenspalten- oder Zeilenüberschrift angezeigt wird.<br/> Der Standardwert ist die Zeichenfolge „Grand Total“.|
| [manual_update](/cells/python-net/de/aspose.cells.pivot/pivottable/manual_update) | Gibt an, ob der PivotTable-Bericht nur auf Anfrage des Benutzers neu berechnet wird.|
| [is_multiple_field_filters](/cells/python-net/de/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Gibt einen booleschen Wert an, der angibt, ob für die Felder einer PivotTable mehrere Filter festgelegt werden können.|
| [missing_items_limit](/cells/python-net/de/aspose.cells.pivot/pivottable/missing_items_limit) | Gibt einen booleschen Wert an, der angibt, ob für die Felder einer PivotTable mehrere Filter festgelegt werden können.|
| [enable_data_value_editing](/cells/python-net/de/aspose.cells.pivot/pivottable/enable_data_value_editing) |Gibt einen booleschen Wert an, der angibt, ob der Benutzer die Zellen im Datenbereich der Pivot-Tabelle bearbeiten darf.<br/> Aktivieren Sie die Zellenbearbeitung im Wertebereich|
| [show_data_tips](/cells/python-net/de/aspose.cells.pivot/pivottable/show_data_tips) | Gibt einen booleschen Wert an, der angibt, ob QuickInfos für PivotTable-Datenzellen angezeigt werden sollen.|
| [show_member_property_tips](/cells/python-net/de/aspose.cells.pivot/pivottable/show_member_property_tips) | Gibt einen booleschen Wert an, der angibt, ob Informationen zu Mitgliedseigenschaften in den PivotTable-QuickInfos weggelassen werden sollen.|
| [show_values_row](/cells/python-net/de/aspose.cells.pivot/pivottable/show_values_row) | Gibt einen booleschen Wert an, der angibt, ob die Wertezeile angezeigt wird.<br/> Zeigt die Wertezeile an|
| [show_empty_col](/cells/python-net/de/aspose.cells.pivot/pivottable/show_empty_col) | Gibt einen booleschen Wert an, der angibt, ob leere Spalten in die Tabelle aufgenommen werden sollen|
| [show_empty_row](/cells/python-net/de/aspose.cells.pivot/pivottable/show_empty_row) | Gibt einen booleschen Wert an, der angibt, ob leere Zeilen in die Tabelle aufgenommen werden sollen.|
| [field_list_sort_ascending](/cells/python-net/de/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Gibt einen booleschen Wert an, der angibt, ob Felder in der PivotTable in der Feldliste in einer nicht standardmäßigen Reihenfolge sortiert sind.|
| [print_drill](/cells/python-net/de/aspose.cells.pivot/pivottable/print_drill) | Gibt einen booleschen Wert an, der angibt, ob Bohrindikatoren gedruckt werden sollen.<br/> Schaltflächen zum Erweitern/Reduzieren drucken, wenn sie auf der Pivottabelle angezeigt werden.|
| [alt_text_title](/cells/python-net/de/aspose.cells.pivot/pivottable/alt_text_title) |Ruft den Titel des Altertexts ab|
| [alt_text_description](/cells/python-net/de/aspose.cells.pivot/pivottable/alt_text_description) | Ruft die Beschreibung des Alternativtexts ab|
| [name](/cells/python-net/de/aspose.cells.pivot/pivottable/name) | Ruft den Namen der PivotTable ab|
| [column_header_caption](/cells/python-net/de/aspose.cells.pivot/pivottable/column_header_caption) | Ruft die Spaltenüberschrift der PivotTable ab.|
| [indent](/cells/python-net/de/aspose.cells.pivot/pivottable/indent) | Gibt das Einrückungsinkrement für die kompakte Achse an und kann verwendet werden, um das Berichtslayout auf „Kompakte Form“ festzulegen.|
| [row_header_caption](/cells/python-net/de/aspose.cells.pivot/pivottable/row_header_caption) | Ruft die Zeilenkopfbeschriftung der PivotTable ab.|
| [show_row_header_caption](/cells/python-net/de/aspose.cells.pivot/pivottable/show_row_header_caption) | Gibt an, ob die Beschriftung der Zeilenüberschrift im PivotTable-Bericht angezeigt wird<br/> Gibt an, ob Feldbeschriftungen und Filter-Dropdowns angezeigt werden|
| [custom_list_sort](/cells/python-net/de/aspose.cells.pivot/pivottable/custom_list_sort) | Gibt an, ob beim Sortieren von Daten die integrierte benutzerdefinierte Liste berücksichtigt wird|
| [pivot_format_conditions](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_format_conditions) | Ruft die Formatbedingungen der Pivot-Tabelle ab.|
| [page_field_order](/cells/python-net/de/aspose.cells.pivot/pivottable/page_field_order) | Ruft die Reihenfolge ab, in der Seitenfelder zum Layout des PivotTable-Berichts hinzugefügt werden.|
| [page_field_wrap_count](/cells/python-net/de/aspose.cells.pivot/pivottable/page_field_wrap_count) | Ruft die Anzahl der Seitenfelder in jeder Spalte oder Zeile im PivotTable-Bericht ab.|
| [tag](/cells/python-net/de/aspose.cells.pivot/pivottable/tag) | Ruft eine mit dem PivotTable-Bericht gespeicherte Zeichenfolge ab.|
| [save_data](/cells/python-net/de/aspose.cells.pivot/pivottable/save_data) | Gibt an, ob Daten für den PivotTable-Bericht mit der Arbeitsmappe gespeichert werden.|
| [refresh_data_on_opening_file](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Gibt an, ob Daten beim Öffnen der Datei aktualisiert werden sollen.|
| [refresh_data_flag](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data_flag) |Gibt an, ob Daten aktualisiert werden oder nicht.|
| [external_connection_data_source](/cells/python-net/de/aspose.cells.pivot/pivottable/external_connection_data_source) | Ruft die externe Verbindungsdatenquelle ab.|
| [data_source](/cells/python-net/de/aspose.cells.pivot/pivottable/data_source) | Ruft die Datenquelle der Pivot-Tabelle ab und legt sie fest.|
| [pivot_formats](/cells/python-net/de/aspose.cells.pivot/pivottable/pivot_formats) | Ruft die Auflistung der auf PivotTable angewendeten Formate ab.|
| [item_print_titles](/cells/python-net/de/aspose.cells.pivot/pivottable/item_print_titles) | Ein Bit, das angibt, ob Elementbeschriftungen auf der Zeilenachse gedreht werden sollen<br/> werden auf jeder gedruckten Seite für Pivotfelder in Tabellenform wiederholt.|
| [print_titles](/cells/python-net/de/aspose.cells.pivot/pivottable/print_titles) | Gibt an, ob die Drucktitel für das Arbeitsblatt basierend festgelegt werden<br/> im PivotTable-Bericht. Der Standardwert ist false.|
| [display_immediate_items](/cells/python-net/de/aspose.cells.pivot/pivottable/display_immediate_items) | Gibt an, ob Elemente in den Zeilen- und Spaltenbereichen sichtbar sind<br/> wenn der Datenbereich der PivotTable leer ist. Der Standardwert ist wahr.|
| [is_selected](/cells/python-net/de/aspose.cells.pivot/pivottable/is_selected) | Gibt an, ob die PivotTable ausgewählt ist.|
| [show_pivot_style_row_header](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Gibt an, ob der Stil auf den Zeilenkopf in der Pivot-Tabelle angewendet werden soll.|
| [show_pivot_style_column_header](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Gibt an, ob der Stil auf die Spaltenüberschrift in der Pivot-Tabelle angewendet werden soll.|
| [show_pivot_style_row_stripes](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Gibt an, ob Zeilenstreifenformatierung angewendet wird.|
| [show_pivot_style_column_stripes](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Gibt an, ob die Spaltenstreifenformatierung angewendet wird.|
| [show_pivot_style_last_column](/cells/python-net/de/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Gibt an, ob die Spaltenstreifenformatierung angewendet wird.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [remove_field](/cells/python-net/de/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) |Entfernt ein Feld aus einem bestimmten Feldbereich|
| [remove_field](/cells/python-net/de/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) |Entfernt ein Feld aus einem bestimmten Feldbereich|
| [remove_field](/cells/python-net/de/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Feld aus einem bestimmten Feldbereich entfernen|
| [add_field_to_area](/cells/python-net/de/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Fügt das Feld dem spezifischen Bereich hinzu.|
| [add_field_to_area](/cells/python-net/de/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Fügt das Feld dem spezifischen Bereich hinzu.|
| [add_field_to_area](/cells/python-net/de/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Fügt das Feld dem spezifischen Bereich hinzu.|
| [add_calculated_field](/cells/python-net/de/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Fügt ein berechnetes Feld zum Pivotfeld hinzu.|
| [add_calculated_field](/cells/python-net/de/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Fügt ein berechnetes Feld zum Pivotfeld hinzu und zieht es in den Datenbereich.|
| [move](/cells/python-net/de/aspose.cells.pivot/pivottable/move/#int-int) | Verschiebt die PivotTable an eine andere Position im Arbeitsblatt.|
| [move](/cells/python-net/de/aspose.cells.pivot/pivottable/move/#str) | Verschiebt die PivotTable an eine andere Position im Arbeitsblatt.|
| [format](/cells/python-net/de/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Formatiert den ausgewählten Bereich der PivotTable.|
| [format](/cells/python-net/de/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Formatieren Sie die Zelle im Pivottable-Bereich|
| [set_auto_group_field](/cells/python-net/de/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Legt die automatische Feldgruppe nach der PivotTable fest.|
| [set_auto_group_field](/cells/python-net/de/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Legt die automatische Feldgruppe nach der PivotTable fest.|
| [set_manual_group_field](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Legt die manuelle Feldgruppe nach der PivotTable fest.|
| [set_manual_group_field](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Legt die manuelle Feldgruppe nach der PivotTable fest.|
| [set_manual_group_field](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Legt die manuelle Feldgruppe nach der PivotTable fest.|
| [set_manual_group_field](/cells/python-net/de/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Legt die manuelle Feldgruppe nach der PivotTable fest.|
| [set_ungroup](/cells/python-net/de/aspose.cells.pivot/pivottable/set_ungroup/#int) | Legt die Aufhebung der Gruppierung durch die PivotTable fest|
| [set_ungroup](/cells/python-net/de/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Legt die Aufhebung der Gruppierung durch die PivotTable fest|
| [copy_style](/cells/python-net/de/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Kopiert den benannten Stil aus einer anderen Pivot-Tabelle.|
| [show_report_filter_page](/cells/python-net/de/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Zeigt alle Berichtsfilterseiten nach PivotField an. Das PivotField muss sich in den PageFields befinden.|
| [show_report_filter_page_by_name](/cells/python-net/de/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Zeigt alle Berichtsfilterseiten entsprechend dem Namen von PivotField an. Das PivotField muss sich in den PageFields befinden.|
| [show_report_filter_page_by_index](/cells/python-net/de/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Alle Berichtsfilterseiten entsprechend dem Positionsindex in den PageFields anzeigen|
| [fields](/cells/python-net/de/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Ruft die spezifischen Felder nach Feldtyp ab.|
| [change_data_source](/cells/python-net/de/aspose.cells.pivot/pivottable/change_data_source/#list) |Legen Sie die Quelldaten der Pivottable fest.<br/> Blatt1!$A$1:$C$3|
| [get_source](/cells/python-net/de/aspose.cells.pivot/pivottable/get_source/#) | Rufen Sie die Quelldaten von Pivottable ab.|
| [refresh_data](/cells/python-net/de/aspose.cells.pivot/pivottable/refresh_data/#) | Aktualisiert die Daten und Einstellungen der Pivottable aus der Datenquelle.|
| [calculate_data](/cells/python-net/de/aspose.cells.pivot/pivottable/calculate_data/#) | Berechnet die Daten der Pivottable in Zellen.|
| [clear_data](/cells/python-net/de/aspose.cells.pivot/pivottable/clear_data/#) | Löschen Sie die Daten und Formatierungen von PivotTable|
| [calculate_range](/cells/python-net/de/aspose.cells.pivot/pivottable/calculate_range/#) | Berechnet den Bereich der Pivottable.|
| [format_all](/cells/python-net/de/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Formatieren Sie alle Zellen im Pivottable-Bereich|
| [format_row](/cells/python-net/de/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Formatieren Sie die Zeilendaten im Pivottable-Bereich|
| [get_horizontal_breaks](/cells/python-net/de/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Rufen Sie die Indexliste der horizontalen Seitenumbrüche in der Pivot-Tabelle ab|
| [show_in_compact_form](/cells/python-net/de/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Layoutt die PivotTable in kompakter Form.|
| [show_in_outline_form](/cells/python-net/de/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Legt das Layout der PivotTable in Gliederungsform an.|
| [show_in_tabular_form](/cells/python-net/de/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Layoutt die PivotTable in tabellarischer Form.|
| [get_cell_by_display_name](/cells/python-net/de/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Ruft das [`Cell`](/cells/python-net/de/aspose.cells/cell)-Objekt über den Anzeigenamen von PivotField ab.|
| [get_children](/cells/python-net/de/aspose.cells.pivot/pivottable/get_children/#) | Ruft die untergeordneten Pivot-Tabellen ab, die diese PivotTable-Daten als Datenquelle verwenden.|



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
