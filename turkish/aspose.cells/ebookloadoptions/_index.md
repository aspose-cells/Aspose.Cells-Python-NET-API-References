---
title: EbookLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 540
url: /tr/aspose.cells/ebookloadoptions/
is_root: false
---
##  EbookLoadOptions sınıfı
Bir e-kitap dosyasını içe aktarırken seçenekleri temsil eder.



**Miras:** [`EbookLoadOptions`](/cells/python-net/aspose.cells/ebookloadoptions) → 
[`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)



EbookLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/ebookloadoptions/__init__/#) | E-kitap dosyasını yükleme seçenekleri oluşturur.|
| [__init__](/cells/python-net/tr/aspose.cells/ebookloadoptions/__init__/#aspose.cells.LoadFormat) | E-kitap dosyasını yükleme seçenekleri oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/ebookloadoptions/load_format) | Yük formatını alır.|
| [password](/cells/python-net/tr/aspose.cells/ebookloadoptions/password) | Çalışma kitabının parolasını alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/ebookloadoptions/parsing_formula_on_open) | Dosya okunurken formülün ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/ebookloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken pivot önbelleğe alınan kayıtların ayrıştırılıp ayrıştırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [language_code](/cells/python-net/tr/aspose.cells/ebookloadoptions/language_code) | Dosyayı kaydeden CountryCode'a göre Çalışma Kitabı sürümünün kullanıcı arayüzü dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/ebookloadoptions/region) |Dosyanın yüklendiği andaki Ülke Koduna göre sistem bölgesel ayarlarını alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/ebookloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/ebookloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/ebookloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [interrupt_monitor](/cells/python-net/tr/aspose.cells/ebookloadoptions/interrupt_monitor) | Kesinti monitörünü alır ve ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/ebookloadoptions/ignore_not_printed) | Dosya doğrudan yazdırılıyorsa yazdırılmayan verileri dikkate almayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/ebookloadoptions/check_data_valid) | Şablon dosyasındaki verilerin geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/ebookloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.<br/>Örneğin Excel, 32K'dan uzun dize değerinin girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan daha uzun bir değer girdiğinizde, bu özellik doğruysa bir Exception alırsınız.<br/>Bu özellik false ise, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya formatları için dize değerinin tamamının çıktısını alabilirsiniz.<br/>Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,<br/> çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi takdirde oluşturulan excel dosyasında beklenmeyen hatalar oluşabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/ebookloadoptions/keep_unparsed_data) | Şablon dosyasından yüklendiğinde Çalışma Kitabının ayrıştırılmamış verilerinin bellekte tutulup tutulmayacağı. Varsayılan doğrudur.|
| [load_filter](/cells/python-net/tr/aspose.cells/ebookloadoptions/load_filter) | Verilerin nasıl yükleneceğini gösteren filtre.|
| [light_cells_data_handler](/cells/python-net/tr/aspose.cells/ebookloadoptions/light_cells_data_handler) | Şablon dosyasını okurken hücre verilerini işlemek için veri işleyici.|
| [memory_setting](/cells/python-net/tr/aspose.cells/ebookloadoptions/memory_setting) | Bellek kullanım seçeneklerini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells/ebookloadoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/ebookloadoptions/auto_fitter_options) | Otomatik montaj seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/ebookloadoptions/auto_filter) | Dosyalar yüklenirken verilerin otomatik olarak filtrelenip filtrelenmeyeceğini belirtir.|
| [font_configs](/cells/python-net/tr/aspose.cells/ebookloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Yalnızca yüklemek için bu [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)'i kullanan [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [ignore_useless_shapes](/cells/python-net/tr/aspose.cells/ebookloadoptions/ignore_useless_shapes) | Yararsız şekillerin göz ardı edilip edilmeyeceğini belirtir.|
| [preserve_padding_spaces_in_formula](/cells/python-net/tr/aspose.cells/ebookloadoptions/preserve_padding_spaces_in_formula) | Formül belirteçleri arasında doldurulan boşlukların ve satır sonlarının korunup korunmayacağını belirtir<br/>formülleri alırken ve ayarlarken.<br/> Varsayılan değer false'tur.|
| [encoding](/cells/python-net/tr/aspose.cells/ebookloadoptions/encoding) |Varsayılan kodlamayı alır ve ayarlar. Yalnızca csv dosyası için geçerlidir.|
| [load_style_strategy](/cells/python-net/tr/aspose.cells/ebookloadoptions/load_style_strategy) | Dize değerini sayıya veya tarihsaat değerine dönüştürürken ayrıştırılan değerlere stil uygulama stratejisini belirtir.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/ebookloadoptions/convert_numeric_data) | Metin dosyasındaki dizenin sayısal verilere dönüştürülüp dönüştürülmediğini gösteren bir değer alır veya ayarlar.|
| [convert_date_time_data](/cells/python-net/tr/aspose.cells/ebookloadoptions/convert_date_time_data) | Metin dosyasındaki dizenin tarih verilerine dönüştürülüp dönüştürülmediğini gösteren bir değer alır veya ayarlar.|
| [keep_precision](/cells/python-net/tr/aspose.cells/ebookloadoptions/keep_precision) | Uzunluk 15 ise bir dize değerinin ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [attached_files_directory](/cells/python-net/tr/aspose.cells/ebookloadoptions/attached_files_directory) | Ekli dosyaların kaydedileceği dizin.|
| [load_formulas](/cells/python-net/tr/aspose.cells/ebookloadoptions/load_formulas) | Orijinal html dosyası formüller içeriyorsa formüllerin içe aktarılıp aktarılmayacağını belirtir|
| [support_div_tag](/cells/python-net/tr/aspose.cells/ebookloadoptions/support_div_tag) |Html dosyası içerdiğinde `<div>` etiketinin düzeninin desteklenip desteklenmediğini belirtir.<br/> Varsayılan değer false'tur.|
| [delete_redundant_spaces](/cells/python-net/tr/aspose.cells/ebookloadoptions/delete_redundant_spaces) | Metin `<br>` etiketini kullanarak satırları kaydırdığında gereksiz boşlukların silinip silinmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [auto_fit_cols_and_rows](/cells/python-net/tr/aspose.cells/ebookloadoptions/auto_fit_cols_and_rows) | Sütunların ve satırların otomatik olarak sığdırılıp sığdırılmayacağını belirtir. Varsayılan değer false'tur.|
| [convert_formulas_data](/cells/python-net/tr/aspose.cells/ebookloadoptions/convert_formulas_data) | doğruysa, dize değeri '=' karakteriyle başladığında dizeyi formüle dönüştürün, varsayılan değer false'tur.|
| [has_formula](/cells/python-net/tr/aspose.cells/ebookloadoptions/has_formula) | Metnin "=" ile başlıyorsa formül olup olmadığını belirtir.|
| [stream_provider](/cells/python-net/tr/aspose.cells/ebookloadoptions/stream_provider) | Nesneleri içeri aktarmak için StreamProviderImportHtmlFile öğesini alır veya ayarlar.|
| [prog_id](/cells/python-net/tr/aspose.cells/ebookloadoptions/prog_id) | Dosyayı oluşturmanın program kimliğini alır.<br/> Yalnızca MHT dosyaları için.|
| [table_load_options](/cells/python-net/tr/aspose.cells/ebookloadoptions/table_load_options) | HtmlTableLoadOptionCollection örneğini alın|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_paper_size](/cells/python-net/tr/aspose.cells/ebookloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Varsayılan yazıcının ayarından varsayılan yazdırma kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`AbstractTextLoadOptions`](/cells/python-net/tr/aspose.cells/abstracttextloadoptions)
* sınıf [`EbookLoadOptions`](/cells/python-net/tr/aspose.cells/ebookloadoptions)
* sınıf [`HtmlLoadOptions`](/cells/python-net/tr/aspose.cells/htmlloadoptions)
* sınıf [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
