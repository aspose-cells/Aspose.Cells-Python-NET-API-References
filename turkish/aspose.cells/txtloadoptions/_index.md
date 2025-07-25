---
title: TxtLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1490
url: /tr/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions sınıfı
Metin dosyasını yükleme seçeneklerini temsil eder.



**Miras:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)



TxtLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/txtloadoptions/__init__/#) | Metin dosyasının yüklenmesi için seçenekler oluşturur.|
| [`__init__(self, load_format)`](/cells/python-net/tr/aspose.cells/txtloadoptions/__init__/#aspose.cells.loadformat) | Metin dosyasının yüklenmesi için seçenekler oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/txtloadoptions/load_format) | Yükleme formatını alır.|
| [password](/cells/python-net/tr/aspose.cells/txtloadoptions/password) | Çalışma kitabının şifresini alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/txtloadoptions/parsing_formula_on_open) | Dosya okunurken formülün ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken pivot önbelleğe alınmış kayıtların ayrıştırılıp ayrıştırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [language_code](/cells/python-net/tr/aspose.cells/txtloadoptions/language_code) | Dosyayı kaydeden CountryCode'a bağlı olarak Çalışma Kitabı sürümünün kullanıcı arayüzü dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/txtloadoptions/region) | Yüklenecek Çalışma Kitabı için kullanılacak bölgesel ayarları alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/txtloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/txtloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/txtloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/txtloadoptions/ignore_not_printed) | Dosyayı doğrudan yazdırıyorsanız yazdırılmayan verileri yoksayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/txtloadoptions/check_data_valid) | Şablon dosyasındaki verilerin geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/txtloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik true ise bir Exception alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya biçimleri için tam dize değerini çıktı olarak alabilirsiniz.<br/>Ancak, Excel dosya biçimi için geçersiz olan bu tür bir değer ayarladıysanız,<br/>Çalışma kitabını daha sonra Excel dosya formatında kaydetmemelisiniz. Aksi takdirde, oluşturulan Excel dosyasında beklenmedik hatalar oluşabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/txtloadoptions/keep_unparsed_data) | Çalışma kitabı şablon dosyasından yüklendiğinde ayrıştırılmamış verilerin bellekte tutulup tutulmayacağı. Varsayılan değer true'dur.|
| [load_filter](/cells/python-net/tr/aspose.cells/txtloadoptions/load_filter) | Verilerin nasıl yükleneceğini belirten filtre.|
| [memory_setting](/cells/python-net/tr/aspose.cells/txtloadoptions/memory_setting) | Yüklenen çalışma kitabı için bellek modunu alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/txtloadoptions/auto_fitter_options) | Otomatik uyumlama seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/txtloadoptions/auto_filter) | Dosyalar yüklenirken verilerin otomatik olarak filtrelenip filtrelenmeyeceğini belirtir.|
| [font_configs](/cells/python-net/tr/aspose.cells/txtloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Sadece bu [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)'i yüklemek için kullanan [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [ignore_useless_shapes](/cells/python-net/tr/aspose.cells/txtloadoptions/ignore_useless_shapes) | Yararsız şekillerin göz ardı edilip edilmeyeceğini belirtir.|
| [preserve_padding_spaces_in_formula](/cells/python-net/tr/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Formül belirteçleri arasında doldurulan boşlukların ve satır sonlarının korunup korunmayacağını belirtir<br/>Formülleri alırken ve ayarlarken.<br/> Varsayılan değer false'tur.|
| [encoding](/cells/python-net/tr/aspose.cells/txtloadoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar. Sadece csv dosyaları için geçerlidir.|
| [load_style_strategy](/cells/python-net/tr/aspose.cells/txtloadoptions/load_style_strategy) | Dize değerini sayıya veya tarih/saat değerine dönüştürürken ayrıştırılmış değerlere uygulanacak stil stratejisini belirtir.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/txtloadoptions/convert_numeric_data) |Metin dosyasındaki dizenin sayısal veriye dönüştürülüp dönüştürülmeyeceğini gösteren bir değeri alır veya ayarlar.|
| [convert_date_time_data](/cells/python-net/tr/aspose.cells/txtloadoptions/convert_date_time_data) | Metin dosyasındaki dizenin tarih verisine dönüştürülüp dönüştürülmediğini gösteren bir değeri alır veya ayarlar.|
| [keep_precision](/cells/python-net/tr/aspose.cells/txtloadoptions/keep_precision) | Uzunluğu 15 olan bir dize değerinin ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [separator](/cells/python-net/tr/aspose.cells/txtloadoptions/separator) | Metin dosyasının karakter ayırıcısını alır ve ayarlar.|
| [separator_string](/cells/python-net/tr/aspose.cells/txtloadoptions/separator_string) | Ayırıcı olarak bir dize değeri alır ve ayarlar.|
| [is_multi_encoded](/cells/python-net/tr/aspose.cells/txtloadoptions/is_multi_encoded) | True, dosyanın birden fazla kodlama içerdiği anlamına gelir.|
| [preferred_parsers](/cells/python-net/tr/aspose.cells/txtloadoptions/preferred_parsers) | Metin dosyasını yüklemek için tercih edilen değer ayrıştırıcılarını alır ve ayarlar.|
| [has_formula](/cells/python-net/tr/aspose.cells/txtloadoptions/has_formula) | "=" ile başlıyorsa metnin formül olup olmadığını belirtir.|
| [has_text_qualifier](/cells/python-net/tr/aspose.cells/txtloadoptions/has_text_qualifier) | Hücre değeri için metin niteleyicisi var mı? Varsayılan değer true'dur.|
| [text_qualifier](/cells/python-net/tr/aspose.cells/txtloadoptions/text_qualifier) | Hücre değerleri için metin niteleyicisini belirtir. Varsayılan niteleyici '"'dir.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/tr/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Ardışık ayraçların tek bir ayraç olarak ele alınması gerekip gerekmediği.|
| [treat_quote_prefix_as_value](/cells/python-net/tr/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Öndeki tek tırnak işaretinin bir hücrenin değerinin bir parçası olarak alınıp alınmayacağını belirtir.<br/>Varsayılan değer doğrudur. Yanlış ise, ilgili hücrenin değerinden öndeki tek tırnak işareti kaldırılır.<br/> ve [`Style.quote_prefix`](/cells/python-net/tr/aspose.cells/style#quote_prefix) hücre için true olarak ayarlanacaktır.|
| [extend_to_next_sheet](/cells/python-net/tr/aspose.cells/txtloadoptions/extend_to_next_sheet) | Veri satırları veya sütunları sınırı aştığında verileri bir sonraki sayfaya genişletir.<br/> Varsayılan değer false'tur.|
| [header_rows_count](/cells/python-net/tr/aspose.cells/txtloadoptions/header_rows_count) |Genişletilmiş sayfalar için tekrarlanacak başlık satırlarının sayısı.|
| [header_columns_count](/cells/python-net/tr/aspose.cells/txtloadoptions/header_columns_count) | Genişletilmiş sayfalar için tekrarlanacak başlık sütunlarının sayısı.|
| [max_row_count](/cells/python-net/tr/aspose.cells/txtloadoptions/max_row_count) | Bir sayfa için içe aktarılacak maksimum satır sayısı.|
| [max_column_count](/cells/python-net/tr/aspose.cells/txtloadoptions/max_column_count) | Bir sayfa için içe aktarılacak maksimum sütun sayısı.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/tr/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.papersizetype) | Varsayılan yazıcı ayarından varsayılan baskı kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`AbstractTextLoadOptions`](/cells/python-net/tr/aspose.cells/abstracttextloadoptions)
* sınıf [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [`TxtLoadOptions`](/cells/python-net/tr/aspose.cells/txtloadoptions)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
