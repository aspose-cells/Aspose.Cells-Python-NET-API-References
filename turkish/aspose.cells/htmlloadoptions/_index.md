---
title: HtmlLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 770
url: /tr/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions sınıfı
Bir html dosyasını içe aktarırken seçenekleri temsil eder.



**Miras:** [HtmlLoadOptions](/cells/python-net/aspose.cells/htmlloadoptions) → 
[AbstractTextLoadOptions](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)



HtmlLoadOptions türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [HtmlLoadOptions()](/cells/python-net/tr/aspose.cells/htmlloadoptions/__init__/#) | Dosyayı yükleme seçeneklerini oluşturur.|
| [HtmlLoadOptions(load_format)](/cells/python-net/tr/aspose.cells/htmlloadoptions/__init__/#LoadFormat) | Dosyayı yükleme seçeneklerini oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_format) | Yükleme biçimini alır.|
| [password](/cells/python-net/tr/aspose.cells/htmlloadoptions/password) | Çalışma kitabının parolasını alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Dosyayı okurken formülün ayrıştırılıp ayrıştırılmadığını gösterir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken özet önbelleğe alınan kayıtların ayrıştırılıp ayrıştırılmayacağını gösterir.<br/> Varsayılan değer yanlıştır.|
| [language_code](/cells/python-net/tr/aspose.cells/htmlloadoptions/language_code) | Dosyayı kaydeden CountryCode'a dayalı olarak Çalışma Kitabı sürümünün kullanıcı arabirimi dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/htmlloadoptions/region) | Dosyanın yüklendiği andaki CountryCode'a göre sistem bölgesel ayarlarını alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/htmlloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/htmlloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/htmlloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [interrupt_monitor](/cells/python-net/tr/aspose.cells/htmlloadoptions/interrupt_monitor) | Kesme monitörünü alır ve ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/htmlloadoptions/ignore_not_printed) | Dosya doğrudan yazdırılıyorsa yazdırılmayan verileri yok sayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/htmlloadoptions/check_data_valid) |Verilerin şablon dosyasında geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/htmlloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.<br/>Örneğin, excel 32K'dan daha uzun bir dizi değeri girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik doğruysa, bir İstisna alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya formatları için tam dizi değerinin çıktısını alabilirsiniz.<br/>Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,<br/> çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi halde oluşturulan excel dosyasında beklenmeyen bir hata olabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/keep_unparsed_data) | Şablon dosyasından yüklendiğinde Çalışma Kitabı için ayrıştırılmamış verilerin bellekte tutulup tutulmadığı. Varsayılan doğrudur.|
| [load_filter](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_filter) | Verilerin nasıl yükleneceğini gösteren filtre.|
| [light_cells_data_handler](/cells/python-net/tr/aspose.cells/htmlloadoptions/light_cells_data_handler) | Şablon dosyasını okurken hücre verilerini işlemek için veri işleyici.|
| [memory_setting](/cells/python-net/tr/aspose.cells/htmlloadoptions/memory_setting) | Bellek kullanım seçeneklerini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells/htmlloadoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/htmlloadoptions/auto_fitter_options) | Otomatik fitre seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/htmlloadoptions/auto_filter) | Dosyaları yüklerken verilerin otomatik olarak filtrelenip filtrelenmediğini gösterir.|
| [font_configs](/cells/python-net/tr/aspose.cells/htmlloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Yalnızca yüklemek için bu [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)'i kullanan [Workbook](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [encoding](/cells/python-net/tr/aspose.cells/htmlloadoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar. Yalnızca csv dosyası için geçerlidir.|
| [load_style_strategy](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_style_strategy) |Dize değerini sayıya veya tarih saatine dönüştürürken ayrıştırılmış değerler için stil uygulama stratejisini belirtir.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/convert_numeric_data) | Metin dosyasındaki dizenin sayısal verilere dönüştürülüp dönüştürülmediğini gösteren bir değer alır veya ayarlar.|
| [convert_date_time_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/convert_date_time_data) | Metin dosyasındaki dizenin tarih verilerine dönüştürülüp dönüştürülmediğini gösteren bir değer alır veya ayarlar.|
| [keep_precision](/cells/python-net/tr/aspose.cells/htmlloadoptions/keep_precision) | Uzunluk 15 ise bir dize değerinin ayrıştırılıp ayrıştırılmayacağını gösterir.|
| [attached_files_directory](/cells/python-net/tr/aspose.cells/htmlloadoptions/attached_files_directory) | Eklenen dosyaların kaydedileceği dizin.|
| [load_formulas](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_formulas) | Orijinal html dosyası formül içeriyorsa, formüllerin içe aktarılıp aktarılmayacağını belirtir|
| [support_div_tag](/cells/python-net/tr/aspose.cells/htmlloadoptions/support_div_tag) | düzenini destekleyip desteklemediğini gösterir.<div> html dosyası içerdiğinde etiketleyin<div> etiketler. Varsayılan değer yanlıştır.|
| [delete_redundant_spaces](/cells/python-net/tr/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Metin, kullanarak satırları kaydırdığında gereksiz boşlukların silinip silinmeyeceğini gösterir.<br> tag.Varsayılan değer yanlıştır.|
| [auto_fit_cols_and_rows](/cells/python-net/tr/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Sütunların ve satırların otomatik sığdırılıp sığdırılmayacağını belirtir. Varsayılan değer yanlıştır.|
| [convert_formulas_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/convert_formulas_data) | true ise, dize değeri '=' karakteriyle başladığında dizeyi formüle dönüştürün, varsayılan değer yanlıştır.|
| [stream_provider](/cells/python-net/tr/aspose.cells/htmlloadoptions/stream_provider) | Nesneleri içe aktarmak için StreamProviderImportHtmlFile öğesini alır veya ayarlar.|
| [prog_id](/cells/python-net/tr/aspose.cells/htmlloadoptions/prog_id) | Dosyayı oluşturmanın program kimliğini alır.<br/> Yalnızca MHT dosyaları için.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/tr/aspose.cells/htmlloadoptions/set_paper_size/#PaperSizeType) | Varsayılan yazıcı ayarından varsayılan yazdırma kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [aspose.cells](..)
* sınıf [AbstractTextLoadOptions](/cells/python-net/tr/aspose.cells/abstracttextloadoptions)
* sınıf [HtmlLoadOptions](/cells/python-net/tr/aspose.cells/htmlloadoptions)
* sınıf [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [Workbook](/cells/python-net/tr/aspose.cells/workbook)
