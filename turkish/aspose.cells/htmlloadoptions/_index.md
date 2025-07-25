---
title: HtmlLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 780
url: /tr/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions sınıfı
Bir html dosyasını içe aktarırken seçenekleri temsil eder.



**Miras:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)



HtmlLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/htmlloadoptions/__init__/#) | Dosyayı yükleme seçeneklerini oluşturur.|
| [`__init__(self, load_format)`](/cells/python-net/tr/aspose.cells/htmlloadoptions/__init__/#aspose.cells.loadformat) | Dosyayı yükleme seçeneklerini oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_format) | Yükleme formatını alır.|
| [password](/cells/python-net/tr/aspose.cells/htmlloadoptions/password) | Çalışma kitabının şifresini alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Dosya okunurken formülün ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken pivot önbelleğe alınmış kayıtların ayrıştırılıp ayrıştırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [language_code](/cells/python-net/tr/aspose.cells/htmlloadoptions/language_code) | Dosyayı kaydeden CountryCode'a bağlı olarak Çalışma Kitabı sürümünün kullanıcı arayüzü dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/htmlloadoptions/region) | Yüklenecek Çalışma Kitabı için kullanılacak bölgesel ayarları alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/htmlloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/htmlloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/htmlloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/htmlloadoptions/ignore_not_printed) | Dosyayı doğrudan yazdırıyorsanız yazdırılmayan verileri yoksayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/htmlloadoptions/check_data_valid) | Şablon dosyasındaki verilerin geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/htmlloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik true ise bir Exception alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya biçimleri için tam dize değerini çıktı olarak alabilirsiniz.<br/>Ancak, Excel dosya biçimi için geçersiz olan bu tür bir değer ayarladıysanız,<br/>Çalışma kitabını daha sonra Excel dosya formatında kaydetmemelisiniz. Aksi takdirde, oluşturulan Excel dosyasında beklenmedik hatalar oluşabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/keep_unparsed_data) | Çalışma kitabı şablon dosyasından yüklendiğinde ayrıştırılmamış verilerin bellekte tutulup tutulmayacağı. Varsayılan değer true'dur.|
| [load_filter](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_filter) | Verilerin nasıl yükleneceğini belirten filtre.|
| [memory_setting](/cells/python-net/tr/aspose.cells/htmlloadoptions/memory_setting) | Yüklenen çalışma kitabı için bellek modunu alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/htmlloadoptions/auto_fitter_options) | Otomatik uyumlama seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/htmlloadoptions/auto_filter) | Dosyalar yüklenirken verilerin otomatik olarak filtrelenip filtrelenmeyeceğini belirtir.|
| [font_configs](/cells/python-net/tr/aspose.cells/htmlloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Sadece bu [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)'i yüklemek için kullanan [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [ignore_useless_shapes](/cells/python-net/tr/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Yararsız şekillerin göz ardı edilip edilmeyeceğini belirtir.|
| [preserve_padding_spaces_in_formula](/cells/python-net/tr/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Formül belirteçleri arasında doldurulan boşlukların ve satır sonlarının korunup korunmayacağını belirtir<br/>Formülleri alırken ve ayarlarken.<br/> Varsayılan değer false'tur.|
| [encoding](/cells/python-net/tr/aspose.cells/htmlloadoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar. Sadece csv dosyaları için geçerlidir.|
| [load_style_strategy](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_style_strategy) | Dize değerini sayıya veya tarih/saat değerine dönüştürürken ayrıştırılmış değerlere uygulanacak stil stratejisini belirtir.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/convert_numeric_data) |Metin dosyasındaki dizenin sayısal veriye dönüştürülüp dönüştürülmeyeceğini gösteren bir değeri alır veya ayarlar.|
| [convert_date_time_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/convert_date_time_data) | Metin dosyasındaki dizenin tarih verisine dönüştürülüp dönüştürülmediğini gösteren bir değeri alır veya ayarlar.|
| [keep_precision](/cells/python-net/tr/aspose.cells/htmlloadoptions/keep_precision) | Uzunluğu 15 olan bir dize değerinin ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [attached_files_directory](/cells/python-net/tr/aspose.cells/htmlloadoptions/attached_files_directory) | Eklenen dosyaların kaydedileceği dizin.|
| [load_formulas](/cells/python-net/tr/aspose.cells/htmlloadoptions/load_formulas) | Orijinal HTML dosyası formüller içeriyorsa formüllerin içe aktarılıp aktarılmayacağını belirtir|
| [support_div_tag](/cells/python-net/tr/aspose.cells/htmlloadoptions/support_div_tag) | HTML dosyası `<div>` etiketini içerdiğinde, bu etiketin düzeninin desteklenip desteklenmediğini belirtir.<br/> Varsayılan değer false'tur.|
| [delete_redundant_spaces](/cells/python-net/tr/aspose.cells/htmlloadoptions/delete_redundant_spaces) | `<br>` etiketi kullanılarak metin satırları sarıldığında gereksiz boşlukların silinip silinmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [auto_fit_cols_and_rows](/cells/python-net/tr/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Sütun ve satırların otomatik olarak sığdırılıp sığdırılmayacağını belirtir. Varsayılan değer false'tur.|
| [convert_formulas_data](/cells/python-net/tr/aspose.cells/htmlloadoptions/convert_formulas_data) |Eğer doğruysa, dize değeri '=' karakteriyle başladığında dizeyi formüle dönüştür, varsayılan değer false'tur.|
| [has_formula](/cells/python-net/tr/aspose.cells/htmlloadoptions/has_formula) | "=" ile başlıyorsa metnin formül olup olmadığını belirtir.|
| [prog_id](/cells/python-net/tr/aspose.cells/htmlloadoptions/prog_id) | Dosyayı oluşturan programın kimliğini alır.<br/> Sadece MHT dosyaları için.|
| [table_load_options](/cells/python-net/tr/aspose.cells/htmlloadoptions/table_load_options) | HtmlTableLoadOptionCollection örneğini alın|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/tr/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Varsayılan yazıcı ayarından varsayılan baskı kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`AbstractTextLoadOptions`](/cells/python-net/tr/aspose.cells/abstracttextloadoptions)
* sınıf [`HtmlLoadOptions`](/cells/python-net/tr/aspose.cells/htmlloadoptions)
* sınıf [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
