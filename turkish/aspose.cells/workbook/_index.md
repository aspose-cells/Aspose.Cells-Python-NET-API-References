---
title: Workbook sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1570
url: /tr/aspose.cells/workbook/
is_root: false
---
##  Workbook sınıfı
Excel elektronik tablosu oluşturmak için bir kök nesneyi temsil eder.



Workbook türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/workbook/__init__/#) | [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır.|
| [`__init__(self, file_format_type)`](/cells/python-net/tr/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) | [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır.|
| [`__init__(self, file)`](/cells/python-net/tr/aspose.cells/workbook/__init__/#str) | [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve bir dosya açar.|
| [`__init__(self, stream)`](/cells/python-net/tr/aspose.cells/workbook/__init__/#io.rawiobase) | [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve bir akış açar.|
| [`__init__(self, file, load_options)`](/cells/python-net/tr/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) | [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve bir dosya açar.|
| [`__init__(self, stream, load_options)`](/cells/python-net/tr/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) | [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve akışı açar.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [settings](/cells/python-net/tr/aspose.cells/workbook/settings) | Çalışma kitabı ayarlarını temsil eder.|
| [worksheets](/cells/python-net/tr/aspose.cells/workbook/worksheets) | [`WorksheetCollection`](/cells/python-net/tr/aspose.cells/worksheetcollection) koleksiyonunu elektronik tabloda alır.|
| [is_licensed](/cells/python-net/tr/aspose.cells/workbook/is_licensed) | Lisansın ayarlanıp ayarlanmadığını gösterir.|
| [colors](/cells/python-net/tr/aspose.cells/workbook/colors) | E-tablodaki paletin renklerini döndürür.|
| [count_of_styles_in_pool](/cells/python-net/tr/aspose.cells/workbook/count_of_styles_in_pool) | Stil havuzundaki stil sayısını alır.|
| [default_style](/cells/python-net/tr/aspose.cells/workbook/default_style) | Çalışma kitabının varsayılan [`Style`](/cells/python-net/tr/aspose.cells/style) nesnesini alır veya ayarlar.|
| [is_digitally_signed](/cells/python-net/tr/aspose.cells/workbook/is_digitally_signed) | Bu elektronik tablonun dijital olarak imzalanıp imzalanmadığını gösterir.|
| [is_workbook_protected_with_password](/cells/python-net/tr/aspose.cells/workbook/is_workbook_protected_with_password) | Yapının veya pencerenin parola ile korunup korunmadığını belirtir.|
| [vba_project](/cells/python-net/tr/aspose.cells/workbook/vba_project) |[`Workbook.vba_project`](/cells/python-net/tr/aspose.cells/workbook#vba_project)'i bir elektronik tabloda alır.|
| [has_macro](/cells/python-net/tr/aspose.cells/workbook/has_macro) | Bu elektronik tablonun makro/VBA içerip içermediğini gösterir.|
| [has_revisions](/cells/python-net/tr/aspose.cells/workbook/has_revisions) | Çalışma kitabında izlenen herhangi bir değişiklik olup olmadığını alır|
| [file_name](/cells/python-net/tr/aspose.cells/workbook/file_name) | Geçerli dosya adını alır ve ayarlar.|
| [cells_data_table_factory](/cells/python-net/tr/aspose.cells/workbook/cells_data_table_factory) | ICellsDataTable'ı özel nesnelerden oluşturmak için fabrikayı alır|
| [data_sorter](/cells/python-net/tr/aspose.cells/workbook/data_sorter) | Verileri sıralamak için bir DataSorter nesnesi alır.|
| [theme](/cells/python-net/tr/aspose.cells/workbook/theme) | Tema adını alır.|
| [built_in_document_properties](/cells/python-net/tr/aspose.cells/workbook/built_in_document_properties) | E-tablonun tüm yerleşik belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.|
| [custom_document_properties](/cells/python-net/tr/aspose.cells/workbook/custom_document_properties) | Elektronik tablonun tüm özel belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.|
| [file_format](/cells/python-net/tr/aspose.cells/workbook/file_format) | Dosya biçimini alır ve ayarlar.|
| [has_custom_function](/cells/python-net/tr/aspose.cells/workbook/has_custom_function) | Bu çalışma kitabında özel bir işlevin kullanılıp kullanılmadığını algılar,<br/> hücrenin formülünde, tanımlanmış isimlerde olduğu gibi...|
| [content_type_properties](/cells/python-net/tr/aspose.cells/workbook/content_type_properties) | Çalışma kitabındaki [`ContentTypeProperty`](/cells/python-net/tr/aspose.cells.properties/contenttypeproperty) nesnenin listesini alır.|
| [custom_xml_parts](/cells/python-net/tr/aspose.cells/workbook/custom_xml_parts) | Özel XML Veri Depolama Bölümünü (bir paket içindeki özel XML verileri) temsil eder.|
| [data_mashup](/cells/python-net/tr/aspose.cells/workbook/data_mashup) | Mashup verilerini alır.|
| [ribbon_xml](/cells/python-net/tr/aspose.cells/workbook/ribbon_xml) | Şerit kullanıcı arayüzünü tanımlayan XML dosyasını alır ve ayarlar.|
| [absolute_path](/cells/python-net/tr/aspose.cells/workbook/absolute_path) | Dosyanın mutlak yolunu alır ve ayarlar.|
| [data_connections](/cells/python-net/tr/aspose.cells/workbook/data_connections) |ExternalConnection koleksiyonunu alır.|
| [data_model](/cells/python-net/tr/aspose.cells/workbook/data_model) | Çalışma kitabındaki veri modelini alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/tr/aspose.cells/workbook/save/#str-aspose.cells.saveformat) | Çalışma kitabını diske kaydeder.|
| [`save(self, file_name)`](/cells/python-net/tr/aspose.cells/workbook/save/#str) | Çalışma kitabını diskete kaydedin.|
| [`save(self, file_name, save_options)`](/cells/python-net/tr/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) | Çalışma kitabını diske kaydeder.|
| [`save(self, stream, save_format)`](/cells/python-net/tr/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) | Çalışma kitabını akışa kaydeder.|
| [`save(self, stream, save_options)`](/cells/python-net/tr/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) | Çalışma kitabını akışa kaydeder.|
| [`create_style(self)`](/cells/python-net/tr/aspose.cells/workbook/create_style/#) | Yeni bir stil yaratır.|
| [`create_style(self, clone_default_style)`](/cells/python-net/tr/aspose.cells/workbook/create_style/#bool) | Yeni bir stil yaratır.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-str) | Bir hücrenin değerini yeni bir dizeyle değiştirir.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-int) | Bir hücrenin değerini yeni bir tam sayı ile değiştirir.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-float) | Bir hücrenin değerini yeni bir double ile değiştirir.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-list-bool) | Bir hücrenin değerini yeni bir dize dizisiyle değiştirir.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-list-bool) | Hücrelerin değerlerini bir tamsayı dizisiyle değiştirir.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-list-bool) | Hücrelerin değerlerini double diziyle değiştirir.|
| [`replace(self, bool_value, new_value)`](/cells/python-net/tr/aspose.cells/workbook/replace/#bool-any) | Hücrelerin değerlerini yeni verilerle değiştirir.|
| [`replace(self, int_value, new_value)`](/cells/python-net/tr/aspose.cells/workbook/replace/#int-any) | Hücrelerin değerlerini yeni verilerle değiştirir.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/tr/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) | Bir hücrenin değerini yeni bir dizeyle değiştirir.|
| [`copy(self, source, copy_options)`](/cells/python-net/tr/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) | Başka bir Çalışma Kitabı nesnesini kopyalar.|
| [`copy(self, source)`](/cells/python-net/tr/aspose.cells/workbook/copy/#aspose.cells.workbook) | Kaynak Çalışma Kitabı nesnesinden verileri kopyalar.|
| [`calculate_formula(self)`](/cells/python-net/tr/aspose.cells/workbook/calculate_formula/#) | Formüllerin sonucunu hesaplar.|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/tr/aspose.cells/workbook/calculate_formula/#bool) | Formüllerin sonucunu hesaplar.|
| [`calculate_formula(self, options)`](/cells/python-net/tr/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) | Bu çalışma kitabındaki formülleri hesaplıyoruz.|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/tr/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Dinamik dizi formüllerini yeniler (geçerli verilere göre komşu hücrelerin yeni aralığına taşır)<br/> Çalışma kitabındaki diğer formüller, dinamik dizi formülleri tarafından kullanılsalar bile yinelemeli olarak hesaplanmayacaktır.|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/tr/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |Dinamik dizi formüllerini yeniler (geçerli verilere göre komşu hücrelerin yeni aralığına taşır)|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/tr/aspose.cells/workbook/import_xml/#str-str-int-int) | XML veri dosyasını çalışma kitabına aktarır/günceller.|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/tr/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) | XML veri dosyasını çalışma kitabına aktarır/günceller.|
| [`export_xml(self, map_name, path)`](/cells/python-net/tr/aspose.cells/workbook/export_xml/#str-str) | Belirtilen XML haritasıyla bağlantılı XML verilerini dışa aktarın.|
| [`export_xml(self, map_name, stream)`](/cells/python-net/tr/aspose.cells/workbook/export_xml/#str-io.rawiobase) | XML verilerini dışa aktar.|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/tr/aspose.cells/workbook/parse_formulas/#bool) | Şablon dosyasından yüklendiğinde veya bir hücreye ayarlandığında ayrıştırılmamış tüm formülleri ayrıştırır.|
| [`start_access_cache(self, opts)`](/cells/python-net/tr/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) | Verilere erişmek için önbellekleri kullanan oturumu başlatır.|
| [`close_access_cache(self, opts)`](/cells/python-net/tr/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) | Verilere erişmek için önbellekleri kullanan oturumu kapatır.|
| [`remove_unused_styles(self)`](/cells/python-net/tr/aspose.cells/workbook/remove_unused_styles/#) | Kullanılmayan tüm stilleri kaldırın.|
| [`create_builtin_style(self, type)`](/cells/python-net/tr/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) | Verilen türe göre yerleşik stil oluşturur.|
| [`create_cells_color(self)`](/cells/python-net/tr/aspose.cells/workbook/create_cells_color/#) | [`CellsColor`](/cells/python-net/tr/aspose.cells/cellscolor) nesnesini oluşturur.|
| [`combine(self, second_workbook)`](/cells/python-net/tr/aspose.cells/workbook/combine/#aspose.cells.workbook) | Başka bir Çalışma Kitabı nesnesini birleştirir.|
| [`get_style_in_pool(self, index)`](/cells/python-net/tr/aspose.cells/workbook/get_style_in_pool/#int) | Stil havuzundaki stili alır.<br/>Çalışma kitabındaki tüm stiller bir havuzda toplanacak.<br/> Hücrelerde sadece basit bir referans indeksi bulunmaktadır.|
| [`get_fonts(self)`](/cells/python-net/tr/aspose.cells/workbook/get_fonts/#) | Stil havuzundaki tüm yazı tiplerini alır.|
| [`get_named_style(self, name)`](/cells/python-net/tr/aspose.cells/workbook/get_named_style/#str) | Stil havuzundaki adlandırılmış stili alır.|
| [`merge_named_styles(self, source)`](/cells/python-net/tr/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) | Diğer Excel dosyasındaki adlandırılmış stilleri birleştirir.|
| [`change_palette(self, color, index)`](/cells/python-net/tr/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) | Belirtilen dizindeki elektronik tablonun paletini değiştirir.|
| [`is_color_in_palette(self, color)`](/cells/python-net/tr/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) | Bir rengin elektronik tablonun paletinde olup olmadığını kontrol eder.|
| [`get_matching_color(self, raw_color)`](/cells/python-net/tr/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |Mevcut paletinizde en iyi eşleşen Rengi bulun.|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/tr/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) | Şifreleme Seçeneklerini Ayarla.|
| [`protect(self, protection_type, password)`](/cells/python-net/tr/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) | Bir çalışma kitabını korur.|
| [`protect_shared_workbook(self, password)`](/cells/python-net/tr/aspose.cells/workbook/protect_shared_workbook/#str) | Paylaşılan bir çalışma kitabını korur.|
| [`unprotect(self, password)`](/cells/python-net/tr/aspose.cells/workbook/unprotect/#str) | Çalışma kitabının korumasını kaldırır.|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/tr/aspose.cells/workbook/unprotect_shared_workbook/#str) | Paylaşılan bir çalışma kitabının korumasını kaldırır.|
| [`remove_macro(self)`](/cells/python-net/tr/aspose.cells/workbook/remove_macro/#) | Bu elektronik tablodan VBA/makroyu kaldırır.|
| [`remove_digital_signature(self)`](/cells/python-net/tr/aspose.cells/workbook/remove_digital_signature/#) | Bu elektronik tablodan dijital imzayı kaldırır.|
| [`accept_all_revisions(self)`](/cells/python-net/tr/aspose.cells/workbook/accept_all_revisions/#) | Çalışma kitabında izlenen tüm değişiklikleri kabul eder.|
| [`remove_external_links(self)`](/cells/python-net/tr/aspose.cells/workbook/remove_external_links/#) | Çalışma kitabındaki tüm dış bağlantıları kaldırır.|
| [`get_theme_color(self, type)`](/cells/python-net/tr/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) | Tema rengini alır.|
| [`set_theme_color(self, type, color)`](/cells/python-net/tr/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) | Tema rengini ayarlar|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/tr/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) | Gümrük teması.|
| [`copy_theme(self, source)`](/cells/python-net/tr/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) | Temayı başka bir çalışma kitabından kopyalar.|
| [`has_exernal_links(self)`](/cells/python-net/tr/aspose.cells/workbook/has_exernal_links/#) | Bu çalışma kitabının diğer veri kaynaklarına yönelik harici bağlantılar içerip içermediğini belirtir.|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/tr/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) | Özel fonksiyonların tanımlarını günceller.|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/tr/aspose.cells/workbook/update_linked_data_source/#list) | Bu çalışma kitabı başka veri kaynaklarına yönelik harici bağlantılar içeriyorsa,<br/> Aspose.Cells verilen kaynaklardan en son verileri almaya çalışacaktır.|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/tr/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Dijital imzayı bir elektronik tablo dosyasına (Excel 2007 ve üzeri) ayarlar.|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/tr/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | OOXML elektronik tablo dosyasına (Excel2007 ve sonrası) dijital imza ekler.|
| [`get_digital_signature(self)`](/cells/python-net/tr/aspose.cells/workbook/get_digital_signature/#) |Dosyadan dijital imzayı alır.|
| [`remove_personal_information(self)`](/cells/python-net/tr/aspose.cells/workbook/remove_personal_information/#) | Kişisel bilgileri siler.|
| [`close(self)`](/cells/python-net/tr/aspose.cells/workbook/close/#) | Dispose() Python protokolünden bu yana sarmalayıcı tarafından atlanıyor|



###  Notlar

Workbook sınıfı bir Excel elektronik tablosunu ifade eder. Her elektronik tablo birden fazla çalışma sayfası içerebilir.
Sınıfın temel özelliği yerel excel dosyalarını açıp kaydetmektir.
Sınıfta diğer çalışma kitaplarından veri kopyalama, iki çalışma kitabını birleştirme, Excel'i PDF'e dönüştürme, Excel'i görüntüye dönüştürme ve Excel elektronik tablosunu koruma gibi bazı gelişmiş özellikler bulunmaktadır.

###  Örnek

Aşağıdaki örnek, designer.xls adlı bir Excel dosyasından Workbook'i yükler ve yatay ve dikey kaydırma çubuklarını görünmez hale getirir.
 Daha sonra elektronik tabloda iki dize değerini sırasıyla bir Tamsayı değeri ve bir dize değeri ile değiştirir ve son olarak çalışma kitabını Excel xlsx dosyası olarak kaydeder.

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

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`CellsColor`](/cells/python-net/tr/aspose.cells/cellscolor)
* sınıf [`ContentTypeProperty`](/cells/python-net/tr/aspose.cells.properties/contenttypeproperty)
* sınıf [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty)
* sınıf [`Style`](/cells/python-net/tr/aspose.cells/style)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
* sınıf [`WorksheetCollection`](/cells/python-net/tr/aspose.cells/worksheetcollection)
