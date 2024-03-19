---
title: HtmlSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 810
url: /de/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions Klasse
Stellt die Optionen zum Speichern einer HTML-Datei dar.



**Nachlass:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ HtmlSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/htmlsaveoptions/__init__/#) | Erstellt Optionen zum Speichern einer HTML-Datei.|
| [__init__](/cells/python-net/de/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.SaveFormat) | Erstellt Optionen zum Speichern der HTM-Datei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/htmlsaveoptions/save_format) | Ruft das Speicherdateiformat ab.|
| [clear_data](/cells/python-net/de/aspose.cells/htmlsaveoptions/clear_data) | Machen Sie die Arbeitsmappe leer, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/htmlsaveoptions/cached_file_folder) | Der zwischengespeicherte Dateiordner wird zum Speichern großer Datenmengen verwendet.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/htmlsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden.|
| [merge_areas](/cells/python-net/de/aspose.cells/htmlsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden.|
| [create_directory](/cells/python-net/de/aspose.cells/htmlsaveoptions/create_directory) | Wenn „true“ und das Verzeichnis nicht existiert, wird das Verzeichnis automatisch erstellt, bevor die Datei gespeichert wird.|
| [sort_names](/cells/python-net/de/aspose.cells/htmlsaveoptions/sort_names) | Gibt an, ob definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/htmlsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Gibt an, ob Diagramm-Cache-Daten aktualisiert werden|
| [warning_callback](/cells/python-net/de/aspose.cells/htmlsaveoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [update_smart_art](/cells/python-net/de/aspose.cells/htmlsaveoptions/update_smart_art) | Gibt an, ob die Smart-Art-Einstellung aktualisiert wird.<br/> Der Standardwert ist false.|
| [ignore_invisible_shapes](/cells/python-net/de/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Geben Sie an, ob diese nicht sichtbaren Formen exportiert werden sollen|
| [page_title](/cells/python-net/de/aspose.cells/htmlsaveoptions/page_title) | Der Titel der HTML-Seite.<br/> Nur zum Speichern im HTML-Stream.|
| [attached_files_directory](/cells/python-net/de/aspose.cells/htmlsaveoptions/attached_files_directory) | Das Verzeichnis, in dem die angehängten Dateien gespeichert werden.<br/> Nur zum Speichern im HTML-Stream.|
| [attached_files_url_prefix](/cells/python-net/de/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Geben Sie das URL-Präfix angehängter Dateien wie z. B. Bilder in der HTML-Datei an.<br/> Nur zum Speichern im HTML-Stream.|
| [default_font_name](/cells/python-net/de/aspose.cells/htmlsaveoptions/default_font_name) | Geben Sie den Namen der Standardschriftart für den HTML-Export an. Die Standardschriftart wird verwendet, wenn die Schriftart des Stils nicht vorhanden ist.<br/>Wenn diese Eigenschaft null ist, verwendet Aspose.Cells eine Universalschriftart, die derselben Familie wie die Originalschriftart entspricht.<br/> Der Standardwert ist null.|
| [worksheet_scalable](/cells/python-net/de/aspose.cells/htmlsaveoptions/worksheet_scalable) | Gibt an, ob beim Speichern der Datei im HTML-Format die HTML-Datei über die Zoomstufe des Arbeitsblatts vergrößert oder verkleinert wird. Der Standardwert ist „false“.|
| [is_export_comments](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_export_comments) |Gibt an, ob Kommentare beim Speichern der Datei im HTML-Format exportiert werden. Der Standardwert ist „false“.|
| [export_comments_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_comments_type) | Stellt die Art des Exportierens von Kommentaren in HTML-Dateien dar.|
| [disable_downlevel_revealed_comments](/cells/python-net/de/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Gibt an, dass der Standardwert „false“ ist, wenn beim Exportieren der Datei in HTML die durch Downlevel aufgedeckten bedingten Kommentare deaktiviert werden.|
| [is_exp_image_to_temp_dir](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Gibt an, ob Bilddateien in das temporäre Verzeichnis exportiert werden.<br/> Nur zum Speichern im HTML-Stream.|
| [image_scalable](/cells/python-net/de/aspose.cells/htmlsaveoptions/image_scalable) | Gibt an, ob eine skalierbare Einheit zur Beschreibung der Bildbreite verwendet wird<br/>wenn eine skalierbare Einheit zur Beschreibung der Spaltenbreite verwendet wird.<br/> Der Standardwert ist wahr.|
| [width_scalable](/cells/python-net/de/aspose.cells/htmlsaveoptions/width_scalable) | Gibt an, ob die Spaltenbreite in Skalierungseinheiten nach HTML exportiert wird.<br/> Der Standardwert ist false.|
| [export_single_tab](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_single_tab) | Gibt an, ob die einzelne Registerkarte exportiert wird, wenn die Datei nur ein Arbeitsblatt enthält.<br/> Der Standardwert ist false.|
| [export_images_as_base64](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_images_as_base64) | Gibt an, ob Bilder im Base64-Format unter HTML, MHTML oder EPUB gespeichert werden.|
| [export_active_worksheet_only](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Gibt an, ob nur das aktive Arbeitsblatt in eine HTML-Datei exportiert wird.<br/>Bei „true“ wird nur das aktive Arbeitsblatt in eine HTML-Datei exportiert;<br/>Bei „false“ wird die gesamte Arbeitsmappe in eine HTML-Datei exportiert.<br/> Der Standardwert ist false.|
| [export_print_area_only](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_print_area_only) | Gibt an, ob nur der Druckbereich in eine HTML-Datei exportiert wird. Der Standardwert ist false.|
| [export_area](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_area) | Ruft die exportierende CellArea des aktuell aktiven Arbeitsblatts ab oder legt diese fest.<br/>Wenn Sie dieses Attribut festlegen, wird der Druckbereich des aktuell aktiven Arbeitsblatts weggelassen.<br/> Beim Speichern der Datei im HTML-Format wird nur der angegebene Bereich exportiert.|
| [parse_html_tag_in_cell](/cells/python-net/de/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) |Gibt an, ob das HTML-Tag (z. B. `<div></div>`) in der Zelle als Zellenwert analysiert oder unverändert beibehalten werden soll.<br/> Der Standardwert ist wahr.|
| [html_cross_string_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/html_cross_string_type) | Gibt an, ob beim Speichern einer Excel-Datei im HTML-Format eine zellenübergreifende Zeichenfolge auf die gleiche Weise wie in MS Excel angezeigt wird.<br/>Standardmäßig ist der Wert „Default“, sodass es bei zellenübergreifenden Zeichenfolgen kaum einen Unterschied zwischen den von Aspose.Cells und MS Excel erstellten HTML-Dateien gibt.<br/> Die Leistung beim Erstellen großer HTML-Dateien ist jedoch um ein Vielfaches höher, wenn der Wert auf „Cross“ gesetzt wird, als wenn man ihn auf „Standard“ oder „Fit2Cell“ setzt.|
| [hidden_col_display_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Versteckte Spalte (die Breite dieser Spalte beträgt 0) in Excel, bevor Sie diese im HTML-Format speichern.<br/>Wenn HtmlHiddenColDisplayType „Remove“ ist, wird die ausgeblendete Spalte nicht ausgegeben.<br/> Wenn der Wert „Ausgeblendet“ ist, würde die Spalte ausgegeben, war aber ausgeblendet, der Standardwert ist „Ausgeblendet“.|
| [hidden_row_display_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Versteckte Zeile (die Höhe dieser Zeile ist 0) in Excel, bevor Sie diese im HTML-Format speichern.<br/>Wenn HtmlHiddenRowDisplayType „Remove“ ist, wird die ausgeblendete Zeile nicht ausgegeben.<br/> Wenn der Wert „Ausgeblendet“ ist, würde die Zeile ausgegeben, war aber ausgeblendet, der Standardwert ist „Ausgeblendet“.|
| [encoding](/cells/python-net/de/aspose.cells/htmlsaveoptions/encoding) | Wenn nicht festgelegt, verwenden Sie Encoding.UTF8 als Standardcodierungstyp.|
| [export_object_listener](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_object_listener) | Ruft den ExportObjectListener zum Exportieren von Objekten ab oder legt diesen fest.|
| [file_path_provider](/cells/python-net/de/aspose.cells/htmlsaveoptions/file_path_provider) |Ruft den IFilePathProvider für den separaten Export von Arbeitsblättern in HTML ab oder legt diesen fest.|
| [stream_provider](/cells/python-net/de/aspose.cells/htmlsaveoptions/stream_provider) | Ruft den IStreamProvider zum Exportieren von Objekten ab oder legt diesen fest.|
| [image_options](/cells/python-net/de/aspose.cells/htmlsaveoptions/image_options) | Rufen Sie das ImageOrPrintOptions-Objekt vor dem Exportieren ab|
| [save_as_single_file](/cells/python-net/de/aspose.cells/htmlsaveoptions/save_as_single_file) | Gibt an, ob der HTML-Code als einzelne Datei gespeichert wird.<br/> Der Standardwert ist false.|
| [show_all_sheets](/cells/python-net/de/aspose.cells/htmlsaveoptions/show_all_sheets) | Gibt an, ob beim Speichern als einzelne HTML-Datei alle Blätter angezeigt werden.|
| [export_page_headers](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_page_headers) | Gibt an, ob Seitenkopfzeilen exportiert werden.|
| [export_page_footers](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_page_footers) | Gibt an, ob Seitenkopfzeilen exportiert werden.|
| [export_hidden_worksheet](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Gibt an, ob der ausgeblendete Arbeitsblattinhalt exportiert wird. Der Standardwert ist „true“.|
| [presentation_preference](/cells/python-net/de/aspose.cells/htmlsaveoptions/presentation_preference) | Gibt an, ob eine HTML- oder MHT-Datei die bevorzugte Präsentation ist.<br/>Der Standardwert ist false.<br/> Wenn Sie eine schönere Darstellung wünschen, setzen Sie bitte den Wert auf „true“.|
| [cell_css_prefix](/cells/python-net/de/aspose.cells/htmlsaveoptions/cell_css_prefix) | Ruft das Präfix des CSS-Namens ab und legt es fest. Der Standardwert ist „“.|
| [table_css_id](/cells/python-net/de/aspose.cells/htmlsaveoptions/table_css_id) | Ruft das Präfix des Typ-CSS-Namens wie tr,col,td usw. ab und legt es fest. Sie sind im Tabellenelement enthalten<br/> welches über das spezifische TableCssId-Attribut verfügt. Der Standardwert ist „“.|
| [is_full_path_link](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_full_path_link) | Gibt an, ob der vollständige Pfadlink in sheet00x.htm, filelist.xml und tabstrip.htm verwendet wird.<br/> Der Standardwert ist false.|
| [export_worksheet_css_separately](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) |Gibt an, ob das Arbeitsblatt-CSS separat exportiert werden soll. Der Standardwert ist „false“.|
| [export_similar_border_style](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_similar_border_style) | Gibt an, ob der ähnliche Rahmenstil exportiert wird, wenn der Rahmenstil von Browsern nicht unterstützt wird.<br/>Wenn Sie die HTML- oder MHT-Datei in Excel importieren möchten, behalten Sie bitte den Standardwert bei.<br/> Der Standardwert ist false.|
| [merge_empty_td_forcely](/cells/python-net/de/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Gibt an, ob das Zusammenführen leerer TD-Elemente beim Exportieren der Datei in HTML erzwungen wird.<br/> Die Größe der HTML-Datei wird erheblich reduziert, nachdem der Wert auf „true“ gesetzt wurde. Der Standardwert ist false.<br/> Wenn Sie die HTML-Datei in Excel importieren oder perfekte Gitterlinien exportieren möchten, wenn Sie die Datei im HTML-Format speichern,<br/> Bitte behalten Sie den Standardwert bei.|
| [merge_empty_td_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/merge_empty_td_type) | Gibt an, ob leere TD-Elemente beim Speichern einer Excel-Datei im HTML-Format auf die gleiche Weise wie MS Excel zusammengeführt werden.<br/> Der Standardwert ist MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Gibt an, ob Excel-Koordinaten nicht leerer Zellen exportiert werden, wenn die Datei im HTML-Format gespeichert wird. Der Standardwert ist false.<br/> Wenn Sie die HTML-Ausgabe in Excel importieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_extra_headings](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_extra_headings) | Gibt an, ob zusätzliche Überschriften exportiert werden, wenn die Textlänge länger als die maximale Anzeigespalte ist.<br/> Der Standardwert ist false. Wenn Sie die HTML-Datei in Excel importieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_headings](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_headings) |Gibt an, ob die Zeilen- und Spaltenüberschriften des Blatts beim Speichern in HTML-Dateien exportiert werden.|
| [export_row_column_headings](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_row_column_headings) |Gibt an, ob die Zeilen- und Spaltenüberschriften des Blatts beim Speichern in HTML-Dateien exportiert werden.|
| [export_formula](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_formula) | Gibt an, ob die Formel beim Speichern der Datei im HTML-Format exportiert wird. Der Standardwert ist wahr.<br/> Wenn Sie die HTML-Ausgabe in Excel importieren möchten, behalten Sie bitte den Standardwert bei.|
| [add_tooltip_text](/cells/python-net/de/aspose.cells/htmlsaveoptions/add_tooltip_text) | Gibt an, ob QuickInfo-Text hinzugefügt wird, wenn die Daten nicht vollständig angezeigt werden können.<br/> Der Standardwert ist false.|
| [export_grid_lines](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_grid_lines) | Gibt an, ob die Gitternetzlinien exportiert werden. Der Standardwert ist „false“.|
| [export_bogus_row_data](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Gibt an, ob falsche Daten in der unteren Zeile exportiert werden. Der Standardwert ist true. Wenn Sie die HTML- oder MHT-Datei importieren möchten<br/> Um Excel zu erstellen, behalten Sie bitte den Standardwert bei.|
| [exclude_unused_styles](/cells/python-net/de/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Gibt an, ob nicht verwendete Stile ausgeschlossen werden.<br/>Bei den generierten HTML-Dateien kann das Ausschließen nicht verwendeter Stile zu einer Verringerung der Dateigröße führen<br/>ohne die visuellen Effekte zu beeinträchtigen. Der Standardwert dieser Eigenschaft ist also true.<br/>Wenn der Benutzer alle Stile in der Arbeitsmappe für den generierten HTML-Code beibehalten muss (z. B. das Szenario, das der Benutzer verwendet).<br/> (muss die Arbeitsmappe später aus dem generierten HTML wiederherstellen) setzen Sie diese Eigenschaft bitte auf „false“.|
| [export_document_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_document_properties) | Gibt an, ob Dokumenteigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie importieren möchten<br/> Wenn Sie die HTML- oder MHT-Datei in Excel kopieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_worksheet_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Gibt an, ob Arbeitsblatteigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie importieren möchten<br/> Wenn Sie die HTML- oder MHT-Datei in Excel kopieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_workbook_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_workbook_properties) |Gibt an, ob Arbeitsmappeneigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie importieren möchten<br/> Wenn Sie die HTML- oder MHT-Datei in Excel kopieren möchten, behalten Sie bitte den Standardwert bei.|
| [export_frame_scripts_and_properties](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Gibt an, ob Rahmenskripte und Dokumenteigenschaften exportiert werden. Der Standardwert ist true. Wenn Sie die HTML- oder MHT-Datei importieren möchten<br/> Um Excel zu erstellen, behalten Sie bitte den Standardwert bei.|
| [export_data_options](/cells/python-net/de/aspose.cells/htmlsaveoptions/export_data_options) | Gibt die Regel zum Exportieren von HTML-Dateidaten an. Der Standardwert ist „Alle“.|
| [link_target_type](/cells/python-net/de/aspose.cells/htmlsaveoptions/link_target_type) | Gibt den Typ des Zielattributs im Link `<a>` an. Der Standardwert ist HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_ie_compatible) | Gibt an, ob die Ausgabe HTML mit dem IE-Browser kompatibel ist.<br/> Der Standardwert ist falsch|
| [format_data_ignore_column_width](/cells/python-net/de/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Gibt an, ob beim Überlaufen der Spalte die gesamten formatierten Daten der Zelle angezeigt werden.<br/>Wenn „true“, ignorieren Sie die Spaltenbreite und die gesamten Daten der Zelle werden exportiert.<br/>Bei „false“ werden die Daten wie in Excel exportiert.<br/> Der Standardwert ist false.|
| [calculate_formula](/cells/python-net/de/aspose.cells/htmlsaveoptions/calculate_formula) | Gibt an, ob Formeln berechnet werden sollen, bevor die HTML-Datei gespeichert wird.|
| [is_js_browser_compatible](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Gibt an, ob JavaScript mit Browsern kompatibel ist, die JavaScript nicht unterstützen.<br/> Der Standardwert ist wahr.|
| [is_mobile_compatible](/cells/python-net/de/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Gibt an, ob die Ausgabe HTML mit Mobilgeräten kompatibel ist.<br/> Der Standardwert ist false.|
| [css_styles](/cells/python-net/de/aspose.cells/htmlsaveoptions/css_styles) | Ruft die zusätzlichen CSS-Stile für den Formatierer ab oder legt diese fest.<br/>Funktioniert nur, wenn [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/de/aspose.cells/htmlsaveoptions#save_as_single_file) True ist.<br/><br/> CssStyles="body { padding: 5px }";|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`HtmlSaveOptions`](/cells/python-net/de/aspose.cells/htmlsaveoptions)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
