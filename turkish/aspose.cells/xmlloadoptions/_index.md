---
title: XmlLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1690
url: /tr/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions sınıfı
Xml yükleme seçeneklerini temsil eder.



**Miras:** [XmlLoadOptions](/cells/python-net/aspose.cells/xmlloadoptions) → 
[LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)



XmlLoadOptions türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [XmlLoadOptions()](/cells/python-net/tr/aspose.cells/xmlloadoptions/__init__/#) | Xml dosyasını yükleme seçeneklerini temsil eder.|
| [XmlLoadOptions(type)](/cells/python-net/tr/aspose.cells/xmlloadoptions/__init__/#LoadFormat) | Xml dosyasını yükleme seçeneklerini temsil eder.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/xmlloadoptions/load_format) | Yükleme biçimini alır.|
| [password](/cells/python-net/tr/aspose.cells/xmlloadoptions/password) | Çalışma kitabının parolasını alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Dosyayı okurken formülün ayrıştırılıp ayrıştırılmadığını gösterir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken özet önbelleğe alınan kayıtların ayrıştırılıp ayrıştırılmayacağını gösterir.<br/> Varsayılan değer yanlıştır.|
| [language_code](/cells/python-net/tr/aspose.cells/xmlloadoptions/language_code) | Dosyayı kaydeden CountryCode'a dayalı olarak Çalışma Kitabı sürümünün kullanıcı arabirimi dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/xmlloadoptions/region) | Dosyanın yüklendiği andaki CountryCode'a göre sistem bölgesel ayarlarını alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/xmlloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/xmlloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/xmlloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [interrupt_monitor](/cells/python-net/tr/aspose.cells/xmlloadoptions/interrupt_monitor) | Kesme monitörünü alır ve ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/xmlloadoptions/ignore_not_printed) | Dosya doğrudan yazdırılıyorsa yazdırılmayan verileri yok sayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/xmlloadoptions/check_data_valid) |Verilerin şablon dosyasında geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/xmlloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.<br/>Örneğin, excel 32K'dan daha uzun bir dizi değeri girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik doğruysa, bir İstisna alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya formatları için tam dizi değerinin çıktısını alabilirsiniz.<br/>Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,<br/> çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi halde oluşturulan excel dosyasında beklenmeyen bir hata olabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/xmlloadoptions/keep_unparsed_data) | Şablon dosyasından yüklendiğinde Çalışma Kitabı için ayrıştırılmamış verilerin bellekte tutulup tutulmadığı. Varsayılan doğrudur.|
| [load_filter](/cells/python-net/tr/aspose.cells/xmlloadoptions/load_filter) | Verilerin nasıl yükleneceğini gösteren filtre.|
| [light_cells_data_handler](/cells/python-net/tr/aspose.cells/xmlloadoptions/light_cells_data_handler) | Şablon dosyasını okurken hücre verilerini işlemek için veri işleyici.|
| [memory_setting](/cells/python-net/tr/aspose.cells/xmlloadoptions/memory_setting) | Bellek kullanım seçeneklerini alır veya ayarlar.|
| [warning_callback](/cells/python-net/tr/aspose.cells/xmlloadoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/xmlloadoptions/auto_fitter_options) | Otomatik fitre seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/xmlloadoptions/auto_filter) | Dosyaları yüklerken verilerin otomatik olarak filtrelenip filtrelenmediğini gösterir.|
| [font_configs](/cells/python-net/tr/aspose.cells/xmlloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Yalnızca yüklemek için bu [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)'i kullanan [Workbook](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [start_cell](/cells/python-net/tr/aspose.cells/xmlloadoptions/start_cell) | Başlangıç hücresini alır ve ayarlar.|
| [is_xml_map](/cells/python-net/tr/aspose.cells/xmlloadoptions/is_xml_map) |xml'nin Excel'e eşlenip eşlenmediğini gösterir.<br/> Varsayılan değer yanlıştır.|
| [contains_multiple_worksheets](/cells/python-net/tr/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Xml'nin birden çok çalışma sayfası olarak içe aktarılıp aktarılmadığını gösterir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/tr/aspose.cells/xmlloadoptions/set_paper_size/#PaperSizeType) | Varsayılan yazıcı ayarından varsayılan yazdırma kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [aspose.cells](..)
* sınıf [LoadOptions](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [Workbook](/cells/python-net/tr/aspose.cells/workbook)
* sınıf [XmlLoadOptions](/cells/python-net/tr/aspose.cells/xmlloadoptions)
