---
title: EbookSaveOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions klass
Representerar alternativen för att spara e-boksfiler.



**Arv:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)



Typen EbookSaveOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/__init__/#) | Skapar alternativ för att spara e-boksfiler.|
| [`__init__(self, save_format)`](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/__init__/#aspose.cells.saveformat) | Skapar alternativ för att spara e-boksfiler.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/save_format) | Hämtar filformatet för att spara.|
| [clear_data](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/clear_data) | Gör arbetsboken tom efter att du har sparat filen.|
| [cached_file_folder](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | Mappen för tillfälliga filer som kan användas som datacache.|
| [validate_merged_areas](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | Anger om sammanslagna celler ska valideras innan filen sparas.|
| [merge_areas](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/merge_areas) | Anger om områdena för villkorlig formatering och validering ska sammanfogas innan filen sparas.|
| [create_directory](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/create_directory) | Om "true" är inställt och katalogen inte finns, skapas katalogen automatiskt innan filen sparas.|
| [sort_names](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/sort_names) |Anger om definierade namn ska sorteras innan filen sparas.|
| [sort_external_names](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/sort_external_names) | Anger om externt definierade namn ska sorteras innan filen sparas.|
| [refresh_chart_cache](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | Anger om uppdatering av diagramcachedata ska ske|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/check_excel_restriction) | Om begränsning av Excel-filen ska kontrolleras när användaren ändrar celler relaterade objekt.<br/>Till exempel tillåter inte Excel inmatning av strängvärden som är längre än 32K.<br/> När du anger ett värde som är längre än 32K kommer det att avkortas.|
| [update_smart_art](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/update_smart_art) | Anger om inställningen för smart konst uppdateras.<br/> Standardvärdet är falskt.|
| [encrypt_document_properties](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/encrypt_document_properties) | Anger om dokumentegenskaper ska krypteras när det sparas som en .xls-fil.<br/> Standardvärdet är sant.|
| [ignore_invisible_shapes](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | Ange om de formerna som inte syns ska exporteras|
| [page_title](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/page_title) | Titeln på html-sidan.<br/> Endast för att spara till html-strömmen.|
| [attached_files_directory](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | Katalogen där de bifogade filerna kommer att sparas.<br/> Endast för att spara till html-strömmen.|
| [attached_files_url_prefix](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | Ange URL-prefixet för bifogade filer, till exempel bilden, i HTML-filen.<br/> Endast för att spara till html-strömmen.|
| [default_font_name](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/default_font_name) | Ange standardtypsnittsnamnet för export av html. Standardtypsnittet används när stiltypsnittet inte finns.<br/>Om den här egenskapen är null, kommer Aspose.Cells att använda ett universellt teckensnitt som har samma familj som det ursprungliga teckensnittet.<br/> Standardvärdet är null.|
| [add_generic_font](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/add_generic_font) |Anger om ett generiskt teckensnitt ska läggas till i CSS-teckensnittsfamiljen.<br/> Standardvärdet är sant|
| [worksheet_scalable](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | Anger om man zoomar in eller ut i html-koden via kalkylbladets zoomnivå när filen sparas till html, standardvärdet är falskt.|
| [is_export_comments](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_export_comments) | Anger att om kommentarer exporteras när filen sparas till html är standardvärdet falskt.|
| [export_comments_type](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_comments_type) | Representerar typen av export av kommentarer till html-filer.|
| [disable_downlevel_revealed_comments](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | Anger att om villkorliga kommentarer som avslöjats på nednivå inaktiveras vid export av fil till html, är standardvärdet falskt.|
| [is_exp_image_to_temp_dir](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | Anger om bildfiler ska exporteras till en tillfällig katalog.<br/> Endast för att spara till html-strömmen.|
| [image_scalable](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/image_scalable) | Anger om en skalbar enhet används för att beskriva bildens bredd<br/>när man använder en skalbar enhet för att beskriva kolumnbredden.<br/> Standardvärdet är sant.|
| [width_scalable](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/width_scalable) | Anger om kolumnbredden i skalenhet ska exporteras till html.<br/> Standardvärdet är falskt.|
| [export_single_tab](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_single_tab) | Anger om den enskilda fliken exporteras när filen bara har ett kalkylblad.<br/> Standardvärdet är falskt.|
| [export_images_as_base64](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | Anger om bilder sparas i Base64-format till HTML, MHTML eller EPUB.|
| [export_active_worksheet_only](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | Anger om endast det aktiva kalkylbladet exporteras till en html-fil.<br/>Om värdet är sant exporteras endast det aktiva kalkylbladet till en html-fil.<br/>Om värdet är falskt exporteras hela arbetsboken till en html-fil.<br/> Standardvärdet är falskt.|
| [export_print_area_only](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_print_area_only) |Anger om endast utskriftsområdet exporteras till en html-fil. Standardvärdet är falskt.|
| [export_area](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_area) | Hämtar eller anger det exporterande cellområdet för det aktuella aktiva kalkylbladet.<br/>Om du anger det här attributet kommer utskriftsområdet för det aktuella aktiva arbetsbladet att utelämnas.<br/> Endast det angivna området exporteras när filen sparas till html.|
| [parse_html_tag_in_cell](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) | Anger om html-taggen (t.ex. `<div></div>`) i cellen ska tolkas som cellvärde eller bevaras som den är.<br/> Standardvärdet är sant.|
| [html_cross_string_type](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | Anger om en sträng mellan celler kommer att visas på samma sätt som i MS Excel när en Excel-fil sparas i html-format.<br/>Som standard är värdet Standard, så för strängar som sträcker sig över flera celler är det liten skillnad mellan html-filerna som skapas av Aspose.Cells och MS Excel.<br/> Men prestandan för att skapa stora html-filer, om värdet ställs in på Cross, skulle vara flera gånger snabbare än att ställa in det på Default eller Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Dold kolumn (bredden på denna kolumn är 0) i Excel, innan den sparas i HTML-format,<br/>Om HtmlHiddenColDisplayType är "Remove" kommer den dolda kolumnen inte att matas ut.<br/> Om värdet är "Dold" skulle kolumnen matas ut, men var dold. Standardvärdet är "Dold".|
| [hidden_row_display_type](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Dold rad (höjden på denna rad är 0) i Excel, innan den sparas i HTML-format,<br/>Om HtmlHiddenRowDisplayType är "Remove", kommer den dolda raden inte att matas ut.<br/>Om värdet är "Dold" skulle raden matas ut, men var dold. Standardvärdet är "Dold".|
| [encoding](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/encoding) | Om inte angivet, använd Encoding.UTF8 som standardkodningstyp.|
| [image_options](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/image_options) | Hämta ImageOrPrintOptions-objektet innan export|
| [save_as_single_file](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | Anger om html-filen ska sparas som en enda fil.<br/> Standardvärdet är falskt.|
| [show_all_sheets](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | Anger om alla ark ska visas när de sparas som en enda html-fil.|
| [export_page_headers](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_page_headers) | Anger om sidhuvuden ska exporteras.|
| [export_page_footers](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_page_footers) | Anger om sidhuvuden ska exporteras.|
| [export_hidden_worksheet](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | Anger om det dolda kalkylbladets innehåll exporteras. Standardvärdet är sant.|
| [presentation_preference](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/presentation_preference) | Anger om html- eller mht-fil är presentationspreferens.<br/>Standardvärdet är falskt.<br/> Om du vill få en vackrare presentation, vänligen sätt värdet till sant.|
| [cell_css_prefix](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | Hämtar och ställer in prefixet för CSS-namnet, standardvärdet är "".|
| [table_css_id](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/table_css_id) | Hämtar och ställer in prefixet för typen CSS-namn, såsom tr, col, td och så vidare, de finns i tabellelementet.<br/> som har det specifika TableCssId-attributet. Standardvärdet är "".|
| [is_full_path_link](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_full_path_link) |Anger om en fullständig sökvägslänk används i sheet00x.htm, filelist.xml och tabstrip.htm.<br/> Standardvärdet är falskt.|
| [export_worksheet_css_separately](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) | Anger om kalkylbladet i CSS-format ska exporteras separat. Standardvärdet är falskt.|
| [export_similar_border_style](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | Anger om en liknande kantlinje ska exporteras när den inte stöds av webbläsare.<br/>Om du vill importera html- eller mht-filen till Excel, vänligen behåll standardvärdet.<br/> Standardvärdet är falskt.|
| [merge_empty_td_forcely](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | Anger om tomma TD-element ska sammanfogas med tvång vid export av fil till html.<br/> Storleken på html-filen kommer att minskas avsevärt efter att värdet är satt till sant. Standardvärdet är falskt.<br/> Om du vill importera HTML-filen till Excel eller exportera perfekta rutnät när du sparar filen till HTML,<br/> vänligen behåll standardvärdet.|
| [merge_empty_td_type](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | Möjligheten att sammanfoga sammanhängande tomma celler (tomma td-element)<br/> Standardvärdet är MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | Anger om Excel-koordinater för icke-tomma celler ska exporteras när filen sparas till html. Standardvärdet är falskt.<br/> Om du vill importera utdata-HTML-filen till Excel, vänligen behåll standardvärdet.|
| [export_extra_headings](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | Anger om extra rubriker ska exporteras när textlängden är längre än den maximala visningskolumnen.<br/> Standardvärdet är falskt. Om du vill importera HTML-filen till Excel, vänligen behåll standardvärdet.|
| [export_headings](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_headings) |Anger om arkets rad- och kolumnrubriker exporteras när det sparas till HTML-filer.|
| [export_row_column_headings](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |Anger om arkets rad- och kolumnrubriker exporteras när det sparas till HTML-filer.|
| [export_formula](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_formula) | Anger om formeln exporteras när filen sparas till html. Standardvärdet är sant.<br/> Om du vill importera utdata-HTML-filen till Excel, vänligen behåll standardvärdet.|
| [add_tooltip_text](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | Anger om verktygstips ska läggas till när informationen inte kan visas helt.<br/> Standardvärdet är falskt.|
| [export_grid_lines](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | Anger om rutnätet ska exporteras. Standardvärdet är falskt.|
| [export_bogus_row_data](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | Anger om falsk data från den nedre raden exporteras. Standardvärdet är sant. Om du vill importera html- eller mht-filen<br/> För att Excel ska fungera, vänligen behåll standardvärdet.|
| [exclude_unused_styles](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | Anger om oanvända stilar ska exkluderas.<br/>För de genererade html-filerna kan exkludering av oanvända stilar göra filstorleken mindre<br/>utan att påverka de visuella effekterna. Standardvärdet för den här egenskapen är alltså sant.<br/>Om användaren behöver behålla alla stilar i arbetsboken för den genererade html-koden (t.ex. i det scenario som användaren<br/> behöver återställa arbetsboken från den genererade html-filen senare), vänligen ange den här egenskapen som falsk.|
| [export_document_properties](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_document_properties) | Anger om dokumentegenskaper ska exporteras. Standardvärdet är sant. Om du vill importera<br/> html- eller mht-filen till Excel, vänligen behåll standardvärdet.|
| [export_worksheet_properties](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | Anger om kalkylbladsegenskaper ska exporteras. Standardvärdet är sant. Om du vill importera<br/> html- eller mht-filen till Excel, vänligen behåll standardvärdet.|
| [export_workbook_properties](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |Anger om arbetsboksegenskaper ska exporteras. Standardvärdet är sant. Om du vill importera<br/> html- eller mht-filen till Excel, vänligen behåll standardvärdet.|
| [export_frame_scripts_and_properties](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | Anger om ramskript och dokumentegenskaper ska exporteras. Standardvärdet är sant. Om du vill importera html- eller mht-filen<br/> För att Excel ska fungera, vänligen behåll standardvärdet.|
| [export_data_options](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/export_data_options) | Anger regeln för export av html-fildata. Standardvärdet är Alla.|
| [link_target_type](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/link_target_type) | Anger typen av målattribut i länken `<a>`. Standardvärdet är HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | Anger om utdata HTML är kompatibel med webbläsaren IE.<br/> Standardvärdet är falskt|
| [format_data_ignore_column_width](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | Anger om all formaterad data för cellen ska visas när kolumnen överfylls.<br/>Om värdet är sant ignoreras kolumnbredden och all celldata exporteras.<br/>Om värdet är falskt exporteras data på samma sätt som Excel.<br/> Standardvärdet är falskt.|
| [calculate_formula](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/calculate_formula) | Anger om formler ska beräknas innan HTML-filen sparas.|
| [is_js_browser_compatible](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | Anger om JavaScript är kompatibelt med webbläsare som inte stöder JavaScript.<br/> Standardvärdet är sant.|
| [is_mobile_compatible](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | Anger om utgången HTML är kompatibel med mobila enheter.<br/> Standardvärdet är falskt.|
| [css_styles](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/css_styles) | Hämtar eller ställer in ytterligare CSS-stilar för formateraren.<br/>Fungerar bara när [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/sv/aspose.cells/htmlsaveoptions#save_as_single_file) är True.<br/><br/> CssStyles="kropp { utfyllnad: 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/hide_overflow_wrapped_text) |Anger om överfyllnadstext ska döljas när cellformatet är inställt på att radbryta text.<br/> Standardvärdet är falskt|
| [is_border_collapsed](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/is_border_collapsed) | Anger om tabellkanterna är dolda.<br/> Standardvärdet är sant.|
| [encode_entity_as_code](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/encode_entity_as_code) | Anger om HTML-teckenenheterna ersätts med decimalkod.<br/>(t.ex. ersätts "&nbsp;" med "&#160;").<br/> Standardvärdet är falskt.|
| [office_math_output_mode](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/office_math_output_mode) | Anger hur man exporterar OfficeMath-objekt till HTML, standardvärdet är Bild.|
| [cell_name_attribute](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/cell_name_attribute) | Anger attributet som anger vilket cellnamn som ska skrivas.<br/>(t.ex. om värdet är "id", så blir utdata för cell "A1":<td id='A1'>).<br/> Standardvärdet är null.|
| [disable_css](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/disable_css) | Anger om endast inline-stilar tillämpas, utan att förlita sig på CSS.<br/> Standardvärdet är falskt.|
| [enable_css_custom_properties](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/enable_css_custom_properties) | Optimera utdata från HTML genom att använda anpassade CSS-egenskaper. Till exempel, i ett scenario där en base64-bild förekommer flera gånger, behöver bilddata bara sparas en gång med den anpassade egenskapen, så att prestandan för den resulterande HTML-koden kan förbättras.<br/> Standardvärdet är falskt.|
| [html_version](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/html_version) | Anger versionen av standarden HTML som ska användas när formatet HTML sparas.<br/> Standardvärdet är HtmlVersion.Default.|
| [sheet_set](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions/sheet_set) | Hämtar eller ställer in vilka ark som ska renderas. Standardvärdet är alla synliga ark i arbetsboken: [`SheetSet.visible`](/cells/python-net/sv/aspose.cells.rendering/sheetset#visible).|



###  Se även
* modul [`aspose.cells.saving`](..)
* klass [`EbookSaveOptions`](/cells/python-net/sv/aspose.cells.saving/ebooksaveoptions)
* klass [`HtmlSaveOptions`](/cells/python-net/sv/aspose.cells/htmlsaveoptions)
* klass [`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)
