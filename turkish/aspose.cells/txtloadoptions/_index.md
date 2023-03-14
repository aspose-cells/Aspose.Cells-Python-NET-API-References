---
title: TxtLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1510
url: /tr/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions sınıfı
Metin dosyası yükleme seçeneklerini temsil eder.



**Miras:** [TxtLoadOptions](/cells/python-net/aspose.cells/txtloadoptions) → 
[AbstractTextLoadOptions](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)



TxtLoadOptions türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [TxtLoadOptions()](/cells/python-net/tr/aspose.cells/txtloadoptions/__init__/#) | Metin dosyası yükleme seçeneklerini oluşturur.|
| [TxtLoadOptions(load_format)](/cells/python-net/tr/aspose.cells/txtloadoptions/__init__/#LoadFormat) | Metin dosyası yükleme seçeneklerini oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/txtloadoptions/load_format) | Yükleme biçimini alır.|
| [password](/cells/python-net/tr/aspose.cells/txtloadoptions/password) | Çalışma kitabının parolasını alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/txtloadoptions/parsing_formula_on_open) | Dosyayı okurken formülün ayrıştırılıp ayrıştırılmadığını gösterir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken özet önbelleğe alınan kayıtların ayrıştırılıp ayrıştırılmayacağını gösterir.<br/> Varsayılan değer yanlıştır.|
| [language_code](/cells/python-net/tr/aspose.cells/txtloadoptions/language_code) | Dosyayı kaydeden CountryCode'a dayalı olarak Çalışma Kitabı sürümünün kullanıcı arabirimi dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/txtloadoptions/region) | Dosyanın yüklendiği andaki CountryCode'a göre sistem bölgesel ayarlarını alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/txtloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/txtloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/txtloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [interrupt_monitor](/cells/python-net/tr/aspose.cells/txtloadoptions/interrupt_monitor) | Kesme monitörünü alır ve ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/txtloadoptions/ignore_not_printed) | Dosya doğrudan yazdırılıyorsa yazdırılmayan verileri yok sayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/txtloadoptions/check_data_valid) |Verilerin şablon dosyasında geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/txtloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.<br/>Örneğin, excel 32K'dan daha uzun bir dizi değeri girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik doğruysa, bir İstisna alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya formatları için tam dizi değerinin çıktısını alabilirsiniz.<br/>Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,<br/> çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi halde oluşturulan excel dosyasında beklenmeyen bir hata olabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/txtloadoptions/keep_unparsed_data) | Şablon dosyasından yüklendiğinde Çalışma Kitabı için ayrıştırılmamış verilerin bellekte tutulup tutulmadığı. Varsayılan doğrudur.|
| [load_filter](/cells/python-net/tr/aspose.cells/txtloadoptions/load_filter) | Verilerin nasıl yükleneceğini gösteren filtre.|
| [light_cells_data_handler](/cells/python-net/tr/aspose.cells/txtloadoptions/light_cells_data_handler) | Şablon dosyasını okurken hücre verilerini işlemek için veri işleyici.|
| [memory_setting](/cells/python-net/tr/aspose.cells/txtloadoptions/memory_setting) | Bellek kullanım seçeneklerini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells/txtloadoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/txtloadoptions/auto_fitter_options) | Otomatik fitre seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/txtloadoptions/auto_filter) | Dosyaları yüklerken verilerin otomatik olarak filtrelenip filtrelenmediğini gösterir.|
| [font_configs](/cells/python-net/tr/aspose.cells/txtloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Yalnızca yüklemek için bu [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)'i kullanan [Workbook](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [encoding](/cells/python-net/tr/aspose.cells/txtloadoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar. Yalnızca csv dosyası için geçerlidir.|
| [load_style_strategy](/cells/python-net/tr/aspose.cells/txtloadoptions/load_style_strategy) |Dize değerini sayıya veya tarih saatine dönüştürürken ayrıştırılmış değerler için stil uygulama stratejisini belirtir.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/txtloadoptions/convert_numeric_data) | Metin dosyasındaki dizenin sayısal verilere dönüştürülüp dönüştürülmediğini gösteren bir değer alır veya ayarlar.|
| [convert_date_time_data](/cells/python-net/tr/aspose.cells/txtloadoptions/convert_date_time_data) | Metin dosyasındaki dizenin tarih verilerine dönüştürülüp dönüştürülmediğini gösteren bir değer alır veya ayarlar.|
| [keep_precision](/cells/python-net/tr/aspose.cells/txtloadoptions/keep_precision) | Uzunluk 15 ise bir dize değerinin ayrıştırılıp ayrıştırılmayacağını gösterir.|
| [separator](/cells/python-net/tr/aspose.cells/txtloadoptions/separator) | Metin dosyasının karakter ayırıcısını alır ve ayarlar.|
| [separator_string](/cells/python-net/tr/aspose.cells/txtloadoptions/separator_string) | Ayırıcı olarak bir dize değeri alır ve ayarlar.|
| [is_multi_encoded](/cells/python-net/tr/aspose.cells/txtloadoptions/is_multi_encoded) | Doğru, dosyanın birkaç kodlama içerdiği anlamına gelir.|
| [preferred_parsers](/cells/python-net/tr/aspose.cells/txtloadoptions/preferred_parsers) |Metin dosyasını yüklemek için tercih edilen değer ayrıştırıcılarını alır ve ayarlar.|
| [has_formula](/cells/python-net/tr/aspose.cells/txtloadoptions/has_formula) | Metnin "=" ile başlaması halinde formül olup olmadığını gösterir.|
| [has_text_qualifier](/cells/python-net/tr/aspose.cells/txtloadoptions/has_text_qualifier) | Hücre değeri için metin niteleyici olup olmadığı. Varsayılan doğrudur.|
| [text_qualifier](/cells/python-net/tr/aspose.cells/txtloadoptions/text_qualifier) | Hücre değerleri için metin niteleyicisini belirtir. Varsayılan niteleyici '''' şeklindedir.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/tr/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Ardışık sınırlayıcıların tek olarak ele alınması gerekip gerekmediği.|
| [treat_quote_prefix_as_value](/cells/python-net/tr/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Baştaki tek tırnak işaretinin bir hücrenin değerinin parçası olarak alınması gerekip gerekmediğini gösterir.<br/>Varsayılan doğrudur. Yanlışsa, baştaki tek tırnak, karşılık gelen hücrenin değerinden kaldırılacaktır.<br/> ve [Style.quote_prefix](/cells/python-net/tr/aspose.cells/style#quote_prefix), hücre için doğru olarak ayarlanacaktır.|
| [extend_to_next_sheet](/cells/python-net/tr/aspose.cells/txtloadoptions/extend_to_next_sheet) | Veri satırları veya sütunları sınırı aştığında verileri bir sonraki sayfaya genişletip genişletmeyeceği.<br/>Bu özellik doğruysa, ekstra veriler mevcut sayfanın arkasındaki bir sonraki sayfaya genişletilir (geçerli sayfa sonuncuysa,<br/>geçerli çalışma kitabına yeni sayfa eklenecektir).<br/>Bu özellik false ise, limiti aşan veri yoksayılır.<br/> Varsayılan yanlıştır;|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/tr/aspose.cells/txtloadoptions/set_paper_size/#PaperSizeType) | Varsayılan yazıcı ayarından varsayılan yazdırma kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [aspose.cells](..)
* sınıf [AbstractTextLoadOptions](/cells/python-net/tr/aspose.cells/abstracttextloadoptions)
* sınıf [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [TxtLoadOptions](/cells/python-net/tr/aspose.cells/txtloadoptions)
* sınıf [Workbook](/cells/python-net/tr/aspose.cells/workbook)
