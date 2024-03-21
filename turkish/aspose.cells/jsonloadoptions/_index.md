---
title: JsonLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1000
url: /tr/aspose.cells/jsonloadoptions/
is_root: false
---
##  JsonLoadOptions sınıfı
Json dosyalarını yükleme seçeneklerini temsil eder



**Miras:** [`JsonLoadOptions`](/cells/python-net/aspose.cells/jsonloadoptions) → 
[`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)



JsonLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/jsonloadoptions/__init__/#) | Dosyayı yükleme seçenekleri oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/jsonloadoptions/load_format) | Yük formatını alır.|
| [password](/cells/python-net/tr/aspose.cells/jsonloadoptions/password) | Çalışma kitabının parolasını alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/jsonloadoptions/parsing_formula_on_open) | Dosya okunurken formülün ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/jsonloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken pivot önbelleğe alınan kayıtların ayrıştırılıp ayrıştırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [language_code](/cells/python-net/tr/aspose.cells/jsonloadoptions/language_code) | Dosyayı kaydeden CountryCode'a göre Çalışma Kitabı sürümünün kullanıcı arayüzü dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/jsonloadoptions/region) |Dosyanın yüklendiği andaki Ülke Koduna göre sistem bölgesel ayarlarını alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/jsonloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/jsonloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/jsonloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [interrupt_monitor](/cells/python-net/tr/aspose.cells/jsonloadoptions/interrupt_monitor) | Kesinti monitörünü alır ve ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/jsonloadoptions/ignore_not_printed) | Dosya doğrudan yazdırılıyorsa yazdırılmayan verileri dikkate almayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/jsonloadoptions/check_data_valid) | Şablon dosyasındaki verilerin geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/jsonloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.<br/>Örneğin Excel, 32K'dan uzun dize değerinin girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan daha uzun bir değer girdiğinizde, bu özellik doğruysa bir Exception alırsınız.<br/>Bu özellik false ise, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya formatları için dize değerinin tamamının çıktısını alabilirsiniz.<br/>Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,<br/> çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi takdirde oluşturulan excel dosyasında beklenmeyen hatalar oluşabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/jsonloadoptions/keep_unparsed_data) | Şablon dosyasından yüklendiğinde Çalışma Kitabının ayrıştırılmamış verilerinin bellekte tutulup tutulmayacağı. Varsayılan doğrudur.|
| [load_filter](/cells/python-net/tr/aspose.cells/jsonloadoptions/load_filter) | Verilerin nasıl yükleneceğini gösteren filtre.|
| [light_cells_data_handler](/cells/python-net/tr/aspose.cells/jsonloadoptions/light_cells_data_handler) | Şablon dosyasını okurken hücre verilerini işlemek için veri işleyici.|
| [memory_setting](/cells/python-net/tr/aspose.cells/jsonloadoptions/memory_setting) | Bellek kullanım seçeneklerini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells/jsonloadoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/jsonloadoptions/auto_fitter_options) | Otomatik montaj seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/jsonloadoptions/auto_filter) | Dosyalar yüklenirken verilerin otomatik olarak filtrelenip filtrelenmeyeceğini belirtir.|
| [font_configs](/cells/python-net/tr/aspose.cells/jsonloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Yalnızca yüklemek için bu [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)'i kullanan [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [ignore_useless_shapes](/cells/python-net/tr/aspose.cells/jsonloadoptions/ignore_useless_shapes) | Yararsız şekillerin göz ardı edilip edilmeyeceğini belirtir.|
| [preserve_padding_spaces_in_formula](/cells/python-net/tr/aspose.cells/jsonloadoptions/preserve_padding_spaces_in_formula) | Formül belirteçleri arasında doldurulan boşlukların ve satır sonlarının korunup korunmayacağını belirtir<br/>formülleri alırken ve ayarlarken.<br/> Varsayılan değer false'tur.|
| [start_cell](/cells/python-net/tr/aspose.cells/jsonloadoptions/start_cell) | Başlangıç hücresini alır ve ayarlar.|
| [layout_options](/cells/python-net/tr/aspose.cells/jsonloadoptions/layout_options) | Json'u içe aktarma seçenekleri.|
| [multiple_worksheets](/cells/python-net/tr/aspose.cells/jsonloadoptions/multiple_worksheets) | Tüm alt düğümler dizi düğümleri olduğunda, JsonObject nesnesinin her özniteliğinin tek bir çalışma sayfası olarak içe aktarılıp aktarılmayacağını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_paper_size](/cells/python-net/tr/aspose.cells/jsonloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Varsayılan yazıcının ayarından varsayılan yazdırma kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`JsonLoadOptions`](/cells/python-net/tr/aspose.cells/jsonloadoptions)
* sınıf [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
