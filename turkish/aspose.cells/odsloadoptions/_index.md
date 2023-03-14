---
title: OdsLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1100
url: /tr/aspose.cells/odsloadoptions/
is_root: false
---
##  OdsLoadOptions sınıfı
ods dosyası yükleme seçeneklerini temsil eder.



**Miras:** [OdsLoadOptions](/cells/python-net/aspose.cells/odsloadoptions) → 
[LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)



OdsLoadOptions türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [OdsLoadOptions()](/cells/python-net/tr/aspose.cells/odsloadoptions/__init__/#) | ods dosyası yükleme seçeneklerini temsil eder.|
| [OdsLoadOptions(type)](/cells/python-net/tr/aspose.cells/odsloadoptions/__init__/#LoadFormat) | ods dosyası yükleme seçeneklerini temsil eder.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/odsloadoptions/load_format) | Yükleme biçimini alır.|
| [password](/cells/python-net/tr/aspose.cells/odsloadoptions/password) | Çalışma kitabının parolasını alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/odsloadoptions/parsing_formula_on_open) | Dosyayı okurken formülün ayrıştırılıp ayrıştırılmadığını gösterir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken özet önbelleğe alınan kayıtların ayrıştırılıp ayrıştırılmayacağını gösterir.<br/> Varsayılan değer yanlıştır.|
| [language_code](/cells/python-net/tr/aspose.cells/odsloadoptions/language_code) | Dosyayı kaydeden CountryCode'a dayalı olarak Çalışma Kitabı sürümünün kullanıcı arabirimi dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/odsloadoptions/region) | Dosyanın yüklendiği andaki CountryCode'a göre sistem bölgesel ayarlarını alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/odsloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/odsloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/odsloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [interrupt_monitor](/cells/python-net/tr/aspose.cells/odsloadoptions/interrupt_monitor) | Kesme monitörünü alır ve ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/odsloadoptions/ignore_not_printed) | Dosya doğrudan yazdırılıyorsa yazdırılmayan verileri yok sayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/odsloadoptions/check_data_valid) |Verilerin şablon dosyasında geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/odsloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.<br/>Örneğin, excel 32K'dan daha uzun bir dizi değeri girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik doğruysa, bir İstisna alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya formatları için tam dizi değerinin çıktısını alabilirsiniz.<br/>Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,<br/> çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi halde oluşturulan excel dosyasında beklenmeyen bir hata olabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/odsloadoptions/keep_unparsed_data) | Şablon dosyasından yüklendiğinde Çalışma Kitabı için ayrıştırılmamış verilerin bellekte tutulup tutulmadığı. Varsayılan doğrudur.|
| [load_filter](/cells/python-net/tr/aspose.cells/odsloadoptions/load_filter) | Verilerin nasıl yükleneceğini gösteren filtre.|
| [light_cells_data_handler](/cells/python-net/tr/aspose.cells/odsloadoptions/light_cells_data_handler) | Şablon dosyasını okurken hücre verilerini işlemek için veri işleyici.|
| [memory_setting](/cells/python-net/tr/aspose.cells/odsloadoptions/memory_setting) | Bellek kullanım seçeneklerini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells/odsloadoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/odsloadoptions/auto_fitter_options) | Otomatik fitre seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/odsloadoptions/auto_filter) | Dosyaları yüklerken verilerin otomatik olarak filtrelenip filtrelenmediğini gösterir.|
| [font_configs](/cells/python-net/tr/aspose.cells/odsloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Yalnızca yüklemek için bu [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)'i kullanan [Workbook](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/tr/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Köprüye Excel'in varsayılan stilinin uygulanıp uygulanmadığını gösterir.|
| [refresh_pivot_tables](/cells/python-net/tr/aspose.cells/odsloadoptions/refresh_pivot_tables) | Dosya yüklenirken pivot tabloların yenilenip yenilenmeyeceğini belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/tr/aspose.cells/odsloadoptions/set_paper_size/#PaperSizeType) | Varsayılan yazıcı ayarından varsayılan yazdırma kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [aspose.cells](..)
* sınıf [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [OdsLoadOptions](/cells/python-net/tr/aspose.cells/odsloadoptions)
* sınıf [Workbook](/cells/python-net/tr/aspose.cells/workbook)
