---
title: HtmlSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 790
url: /de/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions Klasse
Stellt die Optionen zum Speichern der HTML-Datei dar.



**Nachlass:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ HtmlSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/htmlsaveoptions/__init__/#) | Erstellt Optionen zum Speichern von HTML-Dateien.|
| [`__init__(self, save_format)`](/cells/python-net/de/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.saveformat) | Erstellt Optionen zum Speichern der HTM-Datei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/htmlsaveoptions/save_format) | Ruft das Format der gespeicherten Datei ab.|
| [clear_data](/cells/python-net/de/aspose.cells/htmlsaveoptions/clear_data) | Leeren Sie die Arbeitsmappe, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/htmlsaveoptions/cached_file_folder) | Der Ordner für temporäre Dateien, die als Datencache verwendet werden können.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/htmlsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden sollen.|
| [merge_areas](/cells/python-net/de/aspose.cells/htmlsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden sollen.|
| [create_directory](/cells/python-net/de/aspose.cells/htmlsaveoptions/create_directory) | Wenn der Wert auf „true“ gesetzt ist und das Verzeichnis nicht existiert, wird das Verzeichnis vor dem Speichern der Datei automatisch erstellt.|
| [sort_names](/cells/python-net/de/aspose.cells/htmlsaveoptions/sort_names) |Gibt an, ob vor dem Speichern der Datei die definierten Namen sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/htmlsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Gibt an, ob die Aktualisierung der Diagramm-Cache-Daten|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/htmlsaveoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/> Wenn Sie einen Wert eingeben, der länger als 32 KB ist, wird er abgeschnitten.|
| [update_smart_art](/cells/python-net/de/aspose.cells/htmlsaveoptions/update_smart_art) | Gibt an, ob die SmartArt-Einstellung aktualisiert wird.<br/> Der Standardwert ist „false“.|
| [encrypt_document_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/encrypt_document_properties) | Gibt an, ob Dokumenteigenschaften beim Speichern als XLS-Datei verschlüsselt werden sollen.<br/> Der Standardwert ist „true“.|
| [ignore_invisible_shapes](/cells/python-net/de/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Geben Sie an, ob diese nicht sichtbaren Formen exportiert werden sollen|
| [page_title](/cells/python-net/de/aspose.cells/htmlsaveoptions/page_title) | Der Titel der HTML-Seite.<br/> Nur zum Speichern im HTML-Stream.|
| [attached_files_directory](/cells/python-net/de/aspose.cells/htmlsaveoptions/attached_files_directory) | Das Verzeichnis, in dem die angehängten Dateien gespeichert werden.<br/> Nur zum Speichern im HTML-Stream.|
| [attached_files_url_prefix](/cells/python-net/de/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Geben Sie das URL-Präfix angehängter Dateien wie etwa Bilder in der HTML-Datei an.<br/> Nur zum Speichern im HTML-Stream.|
| [default_font_name](/cells/python-net/de/aspose.cells/htmlsaveoptions/default_font_name) | Geben Sie den Standardschriftnamen für den HTML-Export an. Die Standardschrift wird verwendet, wenn die Schriftart des Stils nicht vorhanden ist.<br/>Wenn diese Eigenschaft null ist, verwendet Aspose.Cells eine universelle Schriftart, die zur selben Familie wie die Originalschriftart gehört.<br/> der Standardwert ist null.|
| [add_generic_font](/cells/python-net/de/aspose.cells/htmlsaveoptions/add_generic_font) |Gibt an, ob der CSS-Schriftfamilie eine generische Schriftart hinzugefügt werden soll.<br/> Der Standardwert ist true|
| [worksheet_scalable](/cells/python-net/de/aspose.cells/htmlsaveoptions/worksheet_scalable) | Gibt an, ob beim Speichern der Datei im HTML-Format das HTML über die Zoomstufe des Arbeitsblatts vergrößert oder verkleinert wird. Der Standardwert ist „false“.|
| [is_export_comments](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_export_comments) | Gibt an, ob beim Speichern der Datei im HTML-Format Kommentare exportiert werden sollen. Der Standardwert ist „false“.|
| [export_comments_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_comments_type) | Stellt die Art des Exportierens von Kommentaren in HTML-Dateien dar.|
| [disable_downlevel_revealed_comments](/cells/python-net/de/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Gibt an, ob beim Exportieren einer Datei in HTML bedingte Kommentare auf Downlevel-Ebene deaktiviert werden sollen. Der Standardwert ist „false“.|
| [is_exp_image_to_temp_dir](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Gibt an, ob Bilddateien in ein temporäres Verzeichnis exportiert werden.<br/> Nur zum Speichern im HTML-Stream.|
| [image_scalable](/cells/python-net/de/aspose.cells/htmlsaveoptions/image_scalable) | Gibt an, ob zur Beschreibung der Bildbreite eine skalierbare Einheit verwendet wird<br/>bei Verwendung einer skalierbaren Einheit zur Beschreibung der Spaltenbreite.<br/> Der Standardwert ist „true“.|
| [width_scalable](/cells/python-net/de/aspose.cells/htmlsaveoptions/width_scalable) | Gibt an, ob die Spaltenbreite in Maßstabseinheit nach HTML exportiert wird.<br/> Der Standardwert ist „false“.|
| [export_single_tab](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_single_tab) | Gibt an, ob die einzelne Registerkarte exportiert wird, wenn die Datei nur ein Arbeitsblatt enthält.<br/> Der Standardwert ist „false“.|
| [export_images_as_base64](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_images_as_base64) | Gibt an, ob Bilder im Base64-Format in HTML, MHTML oder EPUB gespeichert werden.|
| [export_active_worksheet_only](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Gibt an, ob nur das aktive Arbeitsblatt in eine HTML-Datei exportiert wird.<br/>Wenn „true“, wird nur das aktive Arbeitsblatt in die HTML-Datei exportiert.<br/>Wenn „false“, wird die gesamte Arbeitsmappe in eine HTML-Datei exportiert.<br/> Der Standardwert ist „false“.|
| [export_print_area_only](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_print_area_only) |Gibt an, ob nur der Druckbereich in eine HTML-Datei exportiert wird. Der Standardwert ist „false“.|
| [export_area](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_area) | Ruft den zu exportierenden Zellbereich des aktuell aktiven Arbeitsblatts ab oder legt ihn fest.<br/>Wenn Sie dieses Attribut festlegen, wird der Druckbereich des aktuell aktiven Arbeitsblatts weggelassen.<br/> Beim Speichern der Datei im HTML-Format wird nur der angegebene Bereich exportiert.|
| [parse_html_tag_in_cell](/cells/python-net/de/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) | Gibt an, ob das HTML-Tag (z. B. `<div></div>`) in der Zelle als Zellenwert analysiert oder unverändert beibehalten werden soll.<br/> Der Standardwert ist „true“.|
| [html_cross_string_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/html_cross_string_type) | Gibt an, ob eine zellenübergreifende Zeichenfolge beim Speichern einer Excel-Datei im HTML-Format auf dieselbe Weise wie in MS Excel angezeigt wird.<br/>Der Standardwert ist „Default“, sodass es bei zellenübergreifenden Zeichenfolgen kaum einen Unterschied zwischen den von Aspose.Cells und MS Excel erstellten HTML-Dateien gibt.<br/> Beim Erstellen großer HTML-Dateien wäre die Leistung jedoch um ein Vielfaches höher, wenn der Wert auf „Cross“ gesetzt würde, als wenn er auf „Default“ oder „Fit2Cell“ gesetzt würde.|
| [hidden_col_display_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Versteckte Spalte (die Breite dieser Spalte ist 0) in Excel, bevor Sie dies im HTML-Format speichern.<br/>Wenn HtmlHiddenColDisplayType "Remove" ist, wird die ausgeblendete Spalte nicht ausgegeben.<br/> Wenn der Wert „Versteckt“ ist, wird die Spalte ausgegeben, ist aber versteckt. Der Standardwert ist „Versteckt“.|
| [hidden_row_display_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Versteckte Zeile (die Höhe dieser Zeile ist 0) in Excel, bevor Sie diese im HTML-Format speichern.<br/>Wenn HtmlHiddenRowDisplayType „Remove“ ist, wird die ausgeblendete Zeile nicht ausgegeben.<br/>Wenn der Wert „Versteckt“ ist, wird die Zeile ausgegeben, ist aber versteckt. Der Standardwert ist „Versteckt“.|
| [encoding](/cells/python-net/de/aspose.cells/htmlsaveoptions/encoding) | Wenn nicht festgelegt, verwenden Sie Encoding.UTF8 als Standardkodierungstyp.|
| [image_options](/cells/python-net/de/aspose.cells/htmlsaveoptions/image_options) | Holen Sie sich das ImageOrPrintOptions-Objekt vor dem Exportieren|
| [save_as_single_file](/cells/python-net/de/aspose.cells/htmlsaveoptions/save_as_single_file) | Gibt an, ob das HTML als einzelne Datei gespeichert werden soll.<br/> Der Standardwert ist „false“.|
| [show_all_sheets](/cells/python-net/de/aspose.cells/htmlsaveoptions/show_all_sheets) | Gibt an, ob beim Speichern als einzelne HTML-Datei alle Blätter angezeigt werden.|
| [export_page_headers](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_page_headers) | Gibt an, ob Seitenkopfzeilen exportiert werden.|
| [export_page_footers](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_page_footers) | Gibt an, ob Seitenkopfzeilen exportiert werden.|
| [export_hidden_worksheet](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Gibt an, ob der ausgeblendete Arbeitsblattinhalt exportiert wird. Der Standardwert ist „true“.|
| [presentation_preference](/cells/python-net/de/aspose.cells/htmlsaveoptions/presentation_preference) | Gibt an, ob die Präsentation bevorzugt als HTML- oder MHT-Datei erfolgt.<br/>Der Standardwert ist „false“.<br/> Wenn Sie eine schönere Präsentation wünschen, setzen Sie den Wert bitte auf „true“.|
| [cell_css_prefix](/cells/python-net/de/aspose.cells/htmlsaveoptions/cell_css_prefix) | Ruft das Präfix des CSS-Namens ab und legt es fest. Der Standardwert ist "".|
| [table_css_id](/cells/python-net/de/aspose.cells/htmlsaveoptions/table_css_id) | Ruft das Präfix des Typ-CSS-Namens wie tr,col,td usw. ab und legt es fest. Sie sind im Tabellenelement enthalten<br/> welches das spezifische TableCssId-Attribut hat. Der Standardwert ist "".|
| [is_full_path_link](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_full_path_link) |Gibt an, ob der vollständige Pfadlink in sheet00x.htm, filelist.xml und tabstrip.htm verwendet wird.<br/> Der Standardwert ist „false“.|
| [export_worksheet_css_separately](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) | Gibt an, ob das Arbeitsblatt-CSS separat exportiert werden soll. Der Standardwert ist „false“.|
| [export_similar_border_style](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_similar_border_style) | Gibt an, ob der ähnliche Rahmenstil exportiert werden soll, wenn der Rahmenstil von Browsern nicht unterstützt wird.<br/>Wenn Sie die HTML- oder MHT-Datei in Excel importieren möchten, behalten Sie bitte den Standardwert bei.<br/> Der Standardwert ist „false“.|
| [merge_empty_td_forcely](/cells/python-net/de/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Gibt an, ob beim Exportieren der Datei in HTML das Zusammenführen leerer TD-Elemente erzwungen wird.<br/> Die Größe der HTML-Datei wird deutlich reduziert, wenn der Wert auf „true“ gesetzt wird. Der Standardwert ist „false“.<br/> Wenn Sie die HTML-Datei in Excel importieren oder beim Speichern der Datei im HTML-Format perfekte Rasterlinien exportieren möchten,<br/> Bitte behalten Sie den Standardwert bei.|
| [merge_empty_td_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/merge_empty_td_type) | Die Option zum Zusammenführen zusammenhängender leerer Zellen (leere td-Elemente)<br/> Der Standardwert ist MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Gibt an, ob beim Speichern der Datei im HTML-Format die Excel-Koordinaten nicht leerer Zellen exportiert werden sollen. Der Standardwert ist „false“.<br/> Wenn Sie die HTML-Ausgabe in Excel importieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_extra_headings](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_extra_headings) | Gibt an, ob zusätzliche Überschriften exportiert werden, wenn die Textlänge die maximale Anzeigespalte überschreitet.<br/> Der Standardwert ist „false“. Wenn Sie die HTML-Datei in Excel importieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_headings](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_headings) |Gibt an, ob die Zeilen- und Spaltenüberschriften des Blatts beim Speichern in HTML-Dateien exportiert werden.|
| [export_row_column_headings](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_row_column_headings) |Gibt an, ob die Zeilen- und Spaltenüberschriften des Blatts beim Speichern in HTML-Dateien exportiert werden.|
| [export_formula](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_formula) | Gibt an, ob die Formel beim Speichern der Datei im HTML-Format exportiert wird. Der Standardwert ist „true“.<br/> Wenn Sie die HTML-Ausgabe in Excel importieren möchten, behalten Sie bitte den Standardwert bei.|
| [add_tooltip_text](/cells/python-net/de/aspose.cells/htmlsaveoptions/add_tooltip_text) | Gibt an, ob Tooltip-Text hinzugefügt werden soll, wenn die Daten nicht vollständig angezeigt werden können.<br/> Der Standardwert ist „false“.|
| [export_grid_lines](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_grid_lines) | Gibt an, ob die Gitternetzlinien exportiert werden. Der Standardwert ist „false“.|
| [export_bogus_row_data](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Gibt an, ob falsche Daten in der unteren Zeile exportiert werden sollen. Der Standardwert ist „true“. Wenn Sie die HTML- oder MHT-Datei importieren möchten<br/> um Excel zu erreichen, behalten Sie bitte den Standardwert bei.|
| [exclude_unused_styles](/cells/python-net/de/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Gibt an, ob nicht verwendete Stile ausgeschlossen werden.<br/>Bei den generierten HTML-Dateien kann das Ausschließen nicht verwendeter Stile die Dateigröße verringern<br/>ohne die visuellen Effekte zu beeinträchtigen. Der Standardwert dieser Eigenschaft ist also „true“.<br/>Wenn der Benutzer alle Stile in der Arbeitsmappe für das generierte HTML beibehalten muss (wie das Szenario, in dem der Benutzer<br/> muss die Arbeitsmappe später aus dem generierten HTML wiederherstellen), setzen Sie diese Eigenschaft bitte auf „false“.|
| [export_document_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_document_properties) | Gibt an, ob Dokumenteigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie importieren möchten<br/> Wenn Sie die HTML- oder MHT-Datei nach Excel konvertieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_worksheet_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Gibt an, ob Arbeitsblatteigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie importieren möchten<br/> Wenn Sie die HTML- oder MHT-Datei nach Excel konvertieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_workbook_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_workbook_properties) |Gibt an, ob Arbeitsmappeneigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie importieren möchten<br/> Wenn Sie die HTML- oder MHT-Datei nach Excel konvertieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_frame_scripts_and_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Gibt an, ob Frame-Skripte und Dokumenteigenschaften exportiert werden sollen. Der Standardwert ist „true“. Wenn Sie die HTML- oder MHT-Datei importieren möchten<br/> um Excel zu erreichen, behalten Sie bitte den Standardwert bei.|
| [export_data_options](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_data_options) | Gibt die Regel zum Exportieren von HTML-Dateidaten an. Der Standardwert ist „Alle“.|
| [link_target_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/link_target_type) | Gibt den Typ des Zielattributs im Link `<a>` an. Der Standardwert ist HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_ie_compatible) | Gibt an, ob die Ausgabe HTML mit dem IE-Browser kompatibel ist.<br/> Der Standardwert ist „false“.|
| [format_data_ignore_column_width](/cells/python-net/de/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Gibt an, ob beim Überlauf der Spalte alle formatierten Daten der Zelle angezeigt werden sollen.<br/>Wenn „true“, wird die Spaltenbreite ignoriert und die gesamten Daten der Zelle werden exportiert.<br/>Wenn „false“, werden die Daten wie Excel exportiert.<br/> Der Standardwert ist „false“.|
| [calculate_formula](/cells/python-net/de/aspose.cells/htmlsaveoptions/calculate_formula) | Gibt an, ob Formeln vor dem Speichern der HTML-Datei berechnet werden sollen.|
| [is_js_browser_compatible](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Gibt an, ob JavaScript mit Browsern kompatibel ist, die JavaScript nicht unterstützen.<br/> Der Standardwert ist „true“.|
| [is_mobile_compatible](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Gibt an, ob die Ausgabe HTML mit mobilen Geräten kompatibel ist.<br/> Der Standardwert ist „false“.|
| [css_styles](/cells/python-net/de/aspose.cells/htmlsaveoptions/css_styles) | Ruft die zusätzlichen CSS-Stile für den Formatierer ab oder legt sie fest.<br/>Funktioniert nur, wenn [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/de/aspose.cells/htmlsaveoptions#save_as_single_file) True ist.<br/><br/> CssStyles="body { padding: 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/de/aspose.cells/htmlsaveoptions/hide_overflow_wrapped_text) |Gibt an, ob Überlauftext ausgeblendet werden soll, wenn das Zellenformat auf Textumbruch eingestellt ist.<br/> Der Standardwert ist false|
| [is_border_collapsed](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_border_collapsed) | Gibt an, ob die Tabellenränder reduziert sind.<br/> Der Standardwert ist „true“.|
| [encode_entity_as_code](/cells/python-net/de/aspose.cells/htmlsaveoptions/encode_entity_as_code) | Gibt an, ob die HTML-Zeichenentitäten durch Dezimalcode ersetzt werden.<br/>(zB wird „&nbsp;“ durch „&#160;“ ersetzt).<br/> Der Standardwert ist „false“.|
| [office_math_output_mode](/cells/python-net/de/aspose.cells/htmlsaveoptions/office_math_output_mode) | Gibt an, wie OfficeMath-Objekte nach HTML exportiert werden. Der Standardwert ist „Bild“.|
| [cell_name_attribute](/cells/python-net/de/aspose.cells/htmlsaveoptions/cell_name_attribute) | Gibt das Attribut an, das den zu schreibenden CellName angibt.<br/>(Wenn der Wert beispielsweise „id“ ist, lautet die Ausgabe für Zelle „A1“:<td id='A1'>).<br/> Der Standardwert ist null.|
| [disable_css](/cells/python-net/de/aspose.cells/htmlsaveoptions/disable_css) | Gibt an, ob nur Inline-Stile angewendet werden, ohne auf CSS zurückzugreifen.<br/> Der Standardwert ist „false“.|
| [enable_css_custom_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/enable_css_custom_properties) | Optimieren Sie die HTML-Ausgabe mithilfe benutzerdefinierter CSS-Eigenschaften. Beispielsweise müssen die Bilddaten bei mehreren Vorkommen eines Base64-Bildes mithilfe benutzerdefinierter Eigenschaften nur einmal gespeichert werden, wodurch die Leistung des resultierenden HTML verbessert wird.<br/> Der Standardwert ist „false“.|
| [html_version](/cells/python-net/de/aspose.cells/htmlsaveoptions/html_version) | Gibt die Version des Standards HTML an, die beim Speichern des Formats HTML verwendet werden soll.<br/> Der Standardwert ist HtmlVersion.Default.|
| [sheet_set](/cells/python-net/de/aspose.cells/htmlsaveoptions/sheet_set) | Ruft die zu rendernden Blätter ab oder legt sie fest. Standardmäßig werden alle sichtbaren Blätter in der Arbeitsmappe angezeigt: [`SheetSet.visible`](/cells/python-net/de/aspose.cells.rendering/sheetset#visible).|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`HtmlSaveOptions`](/cells/python-net/de/aspose.cells/htmlsaveoptions)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
