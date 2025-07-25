---
title: AbstractTextLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/abstracttextloadoptions/
is_root: false
---
##  AbstractTextLoadOptions sınıfı
Metin değerlerini yüklemek için genel seçenekler



**Miras:** [`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)



AbstractTextLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/load_format) | Yükleme formatını alır.|
| [password](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/password) | Çalışma kitabının şifresini alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/parsing_formula_on_open) | Dosya okunurken formülün ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken pivot önbelleğe alınmış kayıtların ayrıştırılıp ayrıştırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [language_code](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/language_code) | Dosyayı kaydeden CountryCode'a bağlı olarak Çalışma Kitabı sürümünün kullanıcı arayüzü dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/region) | Yüklenecek Çalışma Kitabı için kullanılacak bölgesel ayarları alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/ignore_not_printed) | Dosyayı doğrudan yazdırıyorsanız yazdırılmayan verileri yoksayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/check_data_valid) | Şablon dosyasındaki verilerin geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik true ise bir Exception alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya biçimleri için tam dize değerini çıktı olarak alabilirsiniz.<br/>Ancak, Excel dosya biçimi için geçersiz olan bu tür bir değer ayarladıysanız,<br/>Çalışma kitabını daha sonra Excel dosya formatında kaydetmemelisiniz. Aksi takdirde, oluşturulan Excel dosyasında beklenmedik hatalar oluşabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/keep_unparsed_data) | Çalışma kitabı şablon dosyasından yüklendiğinde ayrıştırılmamış verilerin bellekte tutulup tutulmayacağı. Varsayılan değer true'dur.|
| [load_filter](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/load_filter) | Verilerin nasıl yükleneceğini belirten filtre.|
| [memory_setting](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/memory_setting) | Yüklenen çalışma kitabı için bellek modunu alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/auto_fitter_options) | Otomatik uyumlama seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/auto_filter) | Dosyalar yüklenirken verilerin otomatik olarak filtrelenip filtrelenmeyeceğini belirtir.|
| [font_configs](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Sadece bu [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)'i yüklemek için kullanan [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [ignore_useless_shapes](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/ignore_useless_shapes) | Yararsız şekillerin göz ardı edilip edilmeyeceğini belirtir.|
| [preserve_padding_spaces_in_formula](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/preserve_padding_spaces_in_formula) | Formül belirteçleri arasında doldurulan boşlukların ve satır sonlarının korunup korunmayacağını belirtir<br/>Formülleri alırken ve ayarlarken.<br/> Varsayılan değer false'tur.|
| [encoding](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar. Sadece csv dosyaları için geçerlidir.|
| [load_style_strategy](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/load_style_strategy) | Dize değerini sayıya veya tarih/saat değerine dönüştürürken ayrıştırılmış değerlere uygulanacak stil stratejisini belirtir.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/convert_numeric_data) |Metin dosyasındaki dizenin sayısal veriye dönüştürülüp dönüştürülmeyeceğini gösteren bir değeri alır veya ayarlar.|
| [convert_date_time_data](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/convert_date_time_data) | Metin dosyasındaki dizenin tarih verisine dönüştürülüp dönüştürülmediğini gösteren bir değeri alır veya ayarlar.|
| [keep_precision](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/keep_precision) | Uzunluğu 15 olan bir dize değerinin ayrıştırılıp ayrıştırılmayacağını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/tr/aspose.cells/abstracttextloadoptions/set_paper_size/#aspose.cells.papersizetype) | Varsayılan yazıcı ayarından varsayılan baskı kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`AbstractTextLoadOptions`](/cells/python-net/tr/aspose.cells/abstracttextloadoptions)
* sınıf [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
