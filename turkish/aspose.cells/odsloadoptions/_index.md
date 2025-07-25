---
title: OdsLoadOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1030
url: /tr/aspose.cells/odsloadoptions/
is_root: false
---
##  OdsLoadOptions sınıfı
ODS dosyasının yüklenme seçeneklerini temsil eder.



**Miras:** [`OdsLoadOptions`](/cells/python-net/aspose.cells/odsloadoptions) → 
[`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)



OdsLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/odsloadoptions/__init__/#) | ODS dosyasının yüklenme seçeneklerini temsil eder.|
| [`__init__(self, type)`](/cells/python-net/tr/aspose.cells/odsloadoptions/__init__/#aspose.cells.loadformat) | ODS dosyasının yüklenme seçeneklerini temsil eder.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [load_format](/cells/python-net/tr/aspose.cells/odsloadoptions/load_format) | Yükleme formatını alır.|
| [password](/cells/python-net/tr/aspose.cells/odsloadoptions/password) | Çalışma kitabının şifresini alır ve ayarlar.|
| [parsing_formula_on_open](/cells/python-net/tr/aspose.cells/odsloadoptions/parsing_formula_on_open) | Dosya okunurken formülün ayrıştırılıp ayrıştırılmayacağını belirtir.|
| [parsing_pivot_cached_records](/cells/python-net/tr/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Dosya yüklenirken pivot önbelleğe alınmış kayıtların ayrıştırılıp ayrıştırılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [language_code](/cells/python-net/tr/aspose.cells/odsloadoptions/language_code) | Dosyayı kaydeden CountryCode'a bağlı olarak Çalışma Kitabı sürümünün kullanıcı arayüzü dilini alır veya ayarlar.|
| [region](/cells/python-net/tr/aspose.cells/odsloadoptions/region) | Yüklenecek Çalışma Kitabı için kullanılacak bölgesel ayarları alır veya ayarlar.|
| [default_style_settings](/cells/python-net/tr/aspose.cells/odsloadoptions/default_style_settings) | Çalışma kitabının stillerini başlatmak için varsayılan stil ayarlarını alır|
| [standard_font](/cells/python-net/tr/aspose.cells/odsloadoptions/standard_font) | Varsayılan standart yazı tipi adını ayarlar|
| [standard_font_size](/cells/python-net/tr/aspose.cells/odsloadoptions/standard_font_size) | Varsayılan standart yazı tipi boyutunu ayarlar.|
| [ignore_not_printed](/cells/python-net/tr/aspose.cells/odsloadoptions/ignore_not_printed) | Dosyayı doğrudan yazdırıyorsanız yazdırılmayan verileri yoksayın|
| [check_data_valid](/cells/python-net/tr/aspose.cells/odsloadoptions/check_data_valid) | Şablon dosyasındaki verilerin geçerli olup olmadığını kontrol edin.|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/odsloadoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/>Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik true ise bir Exception alırsınız.<br/>Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra<br/>CSV gibi diğer dosya biçimleri için tam dize değerini çıktı olarak alabilirsiniz.<br/>Ancak, Excel dosya biçimi için geçersiz olan bu tür bir değer ayarladıysanız,<br/>Çalışma kitabını daha sonra Excel dosya formatında kaydetmemelisiniz. Aksi takdirde, oluşturulan Excel dosyasında beklenmedik hatalar oluşabilir.|
| [keep_unparsed_data](/cells/python-net/tr/aspose.cells/odsloadoptions/keep_unparsed_data) | Çalışma kitabı şablon dosyasından yüklendiğinde ayrıştırılmamış verilerin bellekte tutulup tutulmayacağı. Varsayılan değer true'dur.|
| [load_filter](/cells/python-net/tr/aspose.cells/odsloadoptions/load_filter) | Verilerin nasıl yükleneceğini belirten filtre.|
| [memory_setting](/cells/python-net/tr/aspose.cells/odsloadoptions/memory_setting) | Yüklenen çalışma kitabı için bellek modunu alır veya ayarlar.|
| [auto_fitter_options](/cells/python-net/tr/aspose.cells/odsloadoptions/auto_fitter_options) | Otomatik uyumlama seçeneklerini alır ve ayarlar|
| [auto_filter](/cells/python-net/tr/aspose.cells/odsloadoptions/auto_filter) | Dosyalar yüklenirken verilerin otomatik olarak filtrelenip filtrelenmeyeceğini belirtir.|
| [font_configs](/cells/python-net/tr/aspose.cells/odsloadoptions/font_configs) | Bireysel yazı tipi yapılandırmalarını alır ve ayarlar.<br/> Sadece bu [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)'i yüklemek için kullanan [`Workbook`](/cells/python-net/tr/aspose.cells/workbook) için çalışır.|
| [ignore_useless_shapes](/cells/python-net/tr/aspose.cells/odsloadoptions/ignore_useless_shapes) | Yararsız şekillerin göz ardı edilip edilmeyeceğini belirtir.|
| [preserve_padding_spaces_in_formula](/cells/python-net/tr/aspose.cells/odsloadoptions/preserve_padding_spaces_in_formula) | Formül belirteçleri arasında doldurulan boşlukların ve satır sonlarının korunup korunmayacağını belirtir<br/>Formülleri alırken ve ayarlarken.<br/> Varsayılan değer false'tur.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/tr/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Excel'in varsayılan stilinin köprüye uygulanıp uygulanmayacağını belirtir.|
| [refresh_pivot_tables](/cells/python-net/tr/aspose.cells/odsloadoptions/refresh_pivot_tables) | Dosya yüklenirken pivot tabloların yenilenip yenilenmeyeceğini belirtir.|
| [is_classic_pivot_table](/cells/python-net/tr/aspose.cells/odsloadoptions/is_classic_pivot_table) | Pivot tablonun klasik olup olmadığını gösterir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/tr/aspose.cells/odsloadoptions/set_paper_size/#aspose.cells.papersizetype) | Varsayılan yazıcı ayarından varsayılan baskı kağıdı boyutunu ayarlar.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions)
* sınıf [`OdsLoadOptions`](/cells/python-net/tr/aspose.cells/odsloadoptions)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
