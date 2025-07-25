---
title: Workbook klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1570
url: /sv/aspose.cells/workbook/
is_root: false
---
##  Workbook klass
Representerar ett rotobjekt för att skapa ett Excel-kalkylblad.



Typen Workbook avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/workbook/__init__/#) | Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook).|
| [`__init__(self, file_format_type)`](/cells/python-net/sv/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) | Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook).|
| [`__init__(self, file)`](/cells/python-net/sv/aspose.cells/workbook/__init__/#str) | Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar en fil.|
| [`__init__(self, stream)`](/cells/python-net/sv/aspose.cells/workbook/__init__/#io.rawiobase) | Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar en ström.|
| [`__init__(self, file, load_options)`](/cells/python-net/sv/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) | Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar en fil.|
| [`__init__(self, stream, load_options)`](/cells/python-net/sv/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) | Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar strömmen.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [settings](/cells/python-net/sv/aspose.cells/workbook/settings) | Representerar arbetsboksinställningarna.|
| [worksheets](/cells/python-net/sv/aspose.cells/workbook/worksheets) | Hämtar samlingen [`WorksheetCollection`](/cells/python-net/sv/aspose.cells/worksheetcollection) i kalkylbladet.|
| [is_licensed](/cells/python-net/sv/aspose.cells/workbook/is_licensed) | Anger om licensen är inställd.|
| [colors](/cells/python-net/sv/aspose.cells/workbook/colors) | Returnerar färger i paletten för kalkylbladet.|
| [count_of_styles_in_pool](/cells/python-net/sv/aspose.cells/workbook/count_of_styles_in_pool) | Hämtar antalet stilar i stilpoolen.|
| [default_style](/cells/python-net/sv/aspose.cells/workbook/default_style) | Hämtar eller ställer in standardobjektet [`Style`](/cells/python-net/sv/aspose.cells/style) i arbetsboken.|
| [is_digitally_signed](/cells/python-net/sv/aspose.cells/workbook/is_digitally_signed) | Anger om detta kalkylblad är digitalt signerat.|
| [is_workbook_protected_with_password](/cells/python-net/sv/aspose.cells/workbook/is_workbook_protected_with_password) | Anger om strukturen eller fönstret är lösenordsskyddat.|
| [vba_project](/cells/python-net/sv/aspose.cells/workbook/vba_project) |Hämtar [`Workbook.vba_project`](/cells/python-net/sv/aspose.cells/workbook#vba_project) i ett kalkylblad.|
| [has_macro](/cells/python-net/sv/aspose.cells/workbook/has_macro) | Anger om detta kalkylblad innehåller makro/VBA.|
| [has_revisions](/cells/python-net/sv/aspose.cells/workbook/has_revisions) | Hämtar om arbetsboken har några spårade ändringar|
| [file_name](/cells/python-net/sv/aspose.cells/workbook/file_name) | Hämtar och anger det aktuella filnamnet.|
| [cells_data_table_factory](/cells/python-net/sv/aspose.cells/workbook/cells_data_table_factory) | Hämtar fabriken för att bygga ICellsDataTable från anpassade objekt|
| [data_sorter](/cells/python-net/sv/aspose.cells/workbook/data_sorter) | Hämtar ett DataSorter-objekt för att sortera data.|
| [theme](/cells/python-net/sv/aspose.cells/workbook/theme) | Hämtar temanamnet.|
| [built_in_document_properties](/cells/python-net/sv/aspose.cells/workbook/built_in_document_properties) | Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket.|
| [custom_document_properties](/cells/python-net/sv/aspose.cells/workbook/custom_document_properties) | Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla anpassade dokumentegenskaper i kalkylarket.|
| [file_format](/cells/python-net/sv/aspose.cells/workbook/file_format) | Hämtar och ställer in filformatet.|
| [has_custom_function](/cells/python-net/sv/aspose.cells/workbook/has_custom_function) | Identifierar om det finns en anpassad funktion som används i den här arbetsboken,<br/> såsom i cellens formel, i definierade namn...|
| [content_type_properties](/cells/python-net/sv/aspose.cells/workbook/content_type_properties) | Hämtar listan över [`ContentTypeProperty`](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty)-objekt i arbetsboken.|
| [custom_xml_parts](/cells/python-net/sv/aspose.cells/workbook/custom_xml_parts) | Representerar en anpassad XML-datalagringsdel (anpassade XML-data i ett paket).|
| [data_mashup](/cells/python-net/sv/aspose.cells/workbook/data_mashup) | Hämtar mashup-data.|
| [ribbon_xml](/cells/python-net/sv/aspose.cells/workbook/ribbon_xml) | Hämtar och ställer in XML-filen som definierar Ribbon-gränssnittet.|
| [absolute_path](/cells/python-net/sv/aspose.cells/workbook/absolute_path) | Hämtar och anger filens absoluta sökväg.|
| [data_connections](/cells/python-net/sv/aspose.cells/workbook/data_connections) |Hämtar ExternalConnection-samlingen.|
| [data_model](/cells/python-net/sv/aspose.cells/workbook/data_model) | Hämtar datamodellen i arbetsboken.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/sv/aspose.cells/workbook/save/#str-aspose.cells.saveformat) | Sparar arbetsboken på disken.|
| [`save(self, file_name)`](/cells/python-net/sv/aspose.cells/workbook/save/#str) | Spara arbetsboken på disken.|
| [`save(self, file_name, save_options)`](/cells/python-net/sv/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) | Sparar arbetsboken på disken.|
| [`save(self, stream, save_format)`](/cells/python-net/sv/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) | Sparar arbetsboken i strömmen.|
| [`save(self, stream, save_options)`](/cells/python-net/sv/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) | Sparar arbetsboken i strömmen.|
| [`create_style(self)`](/cells/python-net/sv/aspose.cells/workbook/create_style/#) | Skapar en ny stil.|
| [`create_style(self, clone_default_style)`](/cells/python-net/sv/aspose.cells/workbook/create_style/#bool) | Skapar en ny stil.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-str) | Ersätter en cells värde med en ny sträng.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-int) | Ersätter en cells värde med ett nytt heltal.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-float) | Ersätter en cells värde med en ny double.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-list-bool) | Ersätter en cells värde med en ny strängmatris.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-list-bool) | Ersätter cellernas värden med en heltalsmatris.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-list-bool) | Ersätter cellernas värden med en dubbel array.|
| [`replace(self, bool_value, new_value)`](/cells/python-net/sv/aspose.cells/workbook/replace/#bool-any) | Ersätter cellernas värden med nya data.|
| [`replace(self, int_value, new_value)`](/cells/python-net/sv/aspose.cells/workbook/replace/#int-any) | Ersätter cellernas värden med nya data.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/sv/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) | Ersätter en cells värde med en ny sträng.|
| [`copy(self, source, copy_options)`](/cells/python-net/sv/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) | Kopierar ett annat arbetsboksobjekt.|
| [`copy(self, source)`](/cells/python-net/sv/aspose.cells/workbook/copy/#aspose.cells.workbook) | Kopierar data från ett källobjekt i en arbetsbok.|
| [`calculate_formula(self)`](/cells/python-net/sv/aspose.cells/workbook/calculate_formula/#) | Beräknar resultatet av formler.|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/sv/aspose.cells/workbook/calculate_formula/#bool) | Beräknar resultatet av formler.|
| [`calculate_formula(self, options)`](/cells/python-net/sv/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) | Beräkning av formler i den här arbetsboken.|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/sv/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Uppdaterar dynamiska matrisformler (övergår till ett nytt område av angränsande celler enligt aktuell data)<br/> Andra formler i arbetsboken kommer inte att beräknas rekursivt även om de användes av dynamiska matrisformler.|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/sv/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |Uppdaterar dynamiska matrisformler (övergår till ett nytt område av angränsande celler enligt aktuell data)|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/sv/aspose.cells/workbook/import_xml/#str-str-int-int) | Importerar/uppdaterar en XML-datafil till arbetsboken.|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/sv/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) | Importerar/uppdaterar en XML-datafil till arbetsboken.|
| [`export_xml(self, map_name, path)`](/cells/python-net/sv/aspose.cells/workbook/export_xml/#str-str) | Exportera XML-data länkade med den angivna XML-mappningen.|
| [`export_xml(self, map_name, stream)`](/cells/python-net/sv/aspose.cells/workbook/export_xml/#str-io.rawiobase) | Exportera XML-data.|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/sv/aspose.cells/workbook/parse_formulas/#bool) | Tolkar alla formler som inte har tolkats när de laddades från en mallfil eller sattes till en cell.|
| [`start_access_cache(self, opts)`](/cells/python-net/sv/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) | Startar sessionen som använder cacheminnen för att komma åt data.|
| [`close_access_cache(self, opts)`](/cells/python-net/sv/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) | Stänger sessionen som använder cacheminnen för att komma åt data.|
| [`remove_unused_styles(self)`](/cells/python-net/sv/aspose.cells/workbook/remove_unused_styles/#) | Ta bort alla oanvända stilar.|
| [`create_builtin_style(self, type)`](/cells/python-net/sv/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) | Skapar inbyggd stil efter given typ.|
| [`create_cells_color(self)`](/cells/python-net/sv/aspose.cells/workbook/create_cells_color/#) | Skapar ett [`CellsColor`](/cells/python-net/sv/aspose.cells/cellscolor)-objekt.|
| [`combine(self, second_workbook)`](/cells/python-net/sv/aspose.cells/workbook/combine/#aspose.cells.workbook) | Kombinerar ett annat arbetsboksobjekt.|
| [`get_style_in_pool(self, index)`](/cells/python-net/sv/aspose.cells/workbook/get_style_in_pool/#int) | Hämtar stilen i stilpoolen.<br/>Alla stilar i arbetsboken samlas i en pool.<br/> Det finns bara ett enkelt referensindex i cellerna.|
| [`get_fonts(self)`](/cells/python-net/sv/aspose.cells/workbook/get_fonts/#) | Hämtar alla teckensnitt i stilpoolen.|
| [`get_named_style(self, name)`](/cells/python-net/sv/aspose.cells/workbook/get_named_style/#str) | Hämtar den namngivna stilen i stilpoolen.|
| [`merge_named_styles(self, source)`](/cells/python-net/sv/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) | Sammanfogar namngivna stilar från den andra Excel-filen.|
| [`change_palette(self, color, index)`](/cells/python-net/sv/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) | Ändrar paletten för kalkylbladet i det angivna indexet.|
| [`is_color_in_palette(self, color)`](/cells/python-net/sv/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) | Kontrollerar om en färg finns i paletten för kalkylbladet.|
| [`get_matching_color(self, raw_color)`](/cells/python-net/sv/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |Hitta den färg som bäst matchar i den aktuella paletten.|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/sv/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) | Ställ in krypteringsalternativ.|
| [`protect(self, protection_type, password)`](/cells/python-net/sv/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) | Skyddar en arbetsbok.|
| [`protect_shared_workbook(self, password)`](/cells/python-net/sv/aspose.cells/workbook/protect_shared_workbook/#str) | Skyddar en delad arbetsbok.|
| [`unprotect(self, password)`](/cells/python-net/sv/aspose.cells/workbook/unprotect/#str) | Avskyddar en arbetsbok.|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/sv/aspose.cells/workbook/unprotect_shared_workbook/#str) | Avskyddar en delad arbetsbok.|
| [`remove_macro(self)`](/cells/python-net/sv/aspose.cells/workbook/remove_macro/#) | Tar bort VBA/makro från detta kalkylblad.|
| [`remove_digital_signature(self)`](/cells/python-net/sv/aspose.cells/workbook/remove_digital_signature/#) | Tar bort digital signatur från detta kalkylblad.|
| [`accept_all_revisions(self)`](/cells/python-net/sv/aspose.cells/workbook/accept_all_revisions/#) | Accepterar alla spårade ändringar i arbetsboken.|
| [`remove_external_links(self)`](/cells/python-net/sv/aspose.cells/workbook/remove_external_links/#) | Tar bort alla externa länkar i arbetsboken.|
| [`get_theme_color(self, type)`](/cells/python-net/sv/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) | Hämtar temafärg.|
| [`set_theme_color(self, type, color)`](/cells/python-net/sv/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) | Ställer in temafärgen|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/sv/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) | Anpassa temat.|
| [`copy_theme(self, source)`](/cells/python-net/sv/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) | Kopierar temat från en annan arbetsbok.|
| [`has_exernal_links(self)`](/cells/python-net/sv/aspose.cells/workbook/has_exernal_links/#) | Anger om den här arbetsboken innehåller externa länkar till andra datakällor.|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/sv/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) | Uppdaterar definitionen av anpassade funktioner.|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/sv/aspose.cells/workbook/update_linked_data_source/#list) | Om den här arbetsboken innehåller externa länkar till andra datakällor,<br/> Aspose.Cells kommer att försöka hämta den senaste informationen från angivna källor.|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/sv/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Ställer in digital signatur till en kalkylbladsfil (Excel 2007 och senare).|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/sv/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Lägger till digital signatur i en OOXML-kalkylbladsfil (Excel 2007 och senare).|
| [`get_digital_signature(self)`](/cells/python-net/sv/aspose.cells/workbook/get_digital_signature/#) |Hämtar digital signatur från fil.|
| [`remove_personal_information(self)`](/cells/python-net/sv/aspose.cells/workbook/remove_personal_information/#) | Tar bort personlig information.|
| [`close(self)`](/cells/python-net/sv/aspose.cells/workbook/close/#) | Dispose() hoppas över av wrapper sedan protokollet Python|



###  Anmärkningar

Klassen Workbook betecknar ett Excel-kalkylblad. Varje kalkylblad kan innehålla flera kalkylblad.
Klassens grundläggande funktion är att öppna och spara Excel-filer.
Klassen har några avancerade funktioner som att kopiera data från andra arbetsböcker, kombinera två arbetsböcker, konvertera Excel till PDF, rendera Excel till bild och skydda Excel-kalkylbladet.

###  Exempel

Följande exempel laddar en Workbook från en Excel-fil med namnet designer.xls och gör de horisontella och vertikala rullningslisterna osynliga.
 Sedan ersätter den två strängvärden med ett heltal respektive ett strängvärde i kalkylbladet och sparar slutligen arbetsboken som en Excel xlsx-fil.

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

###  Se även
* modul [`aspose.cells`](..)
* klass [`CellsColor`](/cells/python-net/sv/aspose.cells/cellscolor)
* klass [`ContentTypeProperty`](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty)
* klass [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)
* klass [`Style`](/cells/python-net/sv/aspose.cells/style)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
* klass [`WorksheetCollection`](/cells/python-net/sv/aspose.cells/worksheetcollection)
