---
title: CellsHelper sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 210
url: /tr/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper sınıfı
Yardımcı işlevler sağlar.



CellsHelper türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [significant_digits](/cells/python-net/tr/aspose.cells/cellshelper/significant_digits) | Anlamlı basamak sayısını alır ve ayarlar.<br/> Varsayılan değer 17'dir.|
| [dpi](/cells/python-net/tr/aspose.cells/cellshelper/dpi) | Makinenin DPI değerini alır.|
| [startup_path](/cells/python-net/tr/aspose.cells/cellshelper/startup_path) | Bazı harici formül referansları tarafından başvurulan başlangıç yolunu alır veya ayarlar.|
| [alt_start_path](/cells/python-net/tr/aspose.cells/cellshelper/alt_start_path) | Bazı harici formül referansları tarafından başvurulan alternatif başlatma yolunu alır veya ayarlar.|
| [library_path](/cells/python-net/tr/aspose.cells/cellshelper/library_path) |Bazı harici formül referansları tarafından başvurulan kütüphane yolunu alır veya ayarlar.|
| [custom_implementation_factory](/cells/python-net/tr/aspose.cells/cellshelper/custom_implementation_factory) | Özel uygulama ile örneklerin oluşturulması için fabrikayı alır veya ayarlar.|
| [is_cloud_platform](/cells/python-net/tr/aspose.cells/cellshelper/is_cloud_platform) | Lütfen Azure, AWSLambda vb. gibi bir bulut platformunda çalışırken bu özelliği True olarak ayarlayın.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/tr/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Verilen sayfa adını kontrol eder ve gerektiğinde geçerli bir sayfa oluşturur.<br/>Eğer verilen sayfa adı excel sayfa adı kurallarına uyuyorsa geri döndür.<br/>Aksi takdirde uzunluk sınırı aşarsa dize kesilecektir<br/> ve geçersiz karakterler ' ' ile değiştirilecek, ardından yeniden oluşturulan dize değeri döndürülecektir.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/tr/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Verilen sayfa adını kontrol eder ve gerektiğinde geçerli bir sayfa oluşturur.<br/>Eğer verilen sayfa adı excel sayfa adı kurallarına uyuyorsa geri döndür.<br/>Aksi takdirde uzunluk sınırı aşarsa dize kesilecektir<br/> ve geçersiz karakterler verilen karakterle değiştirilecek, ardından yeniden oluşturulan dize değeri döndürülecektir.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/tr/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | Metnin genişliğini nokta biriminde alın.|
| [`get_version()`](/cells/python-net/tr/aspose.cells/cellshelper/get_version/#) | Sürümü indirin.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/tr/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Hücrenin ismine göre satır ve sütun indekslerini alır.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/tr/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Satır ve sütun indekslerine göre hücre adını alır.|
| [`column_index_to_name(, column)`](/cells/python-net/tr/aspose.cells/cellshelper/column_index_to_name/#int) | Sütun indeksine göre sütun adını alır.|
| [`column_name_to_index(, column_name)`](/cells/python-net/tr/aspose.cells/cellshelper/column_name_to_index/#str) | Sütun adına göre sütun indeksini alır.|
| [`row_index_to_name(, row)`](/cells/python-net/tr/aspose.cells/cellshelper/row_index_to_name/#int) | Satır indeksine göre satır adını alır.|
| [`row_name_to_index(, row_name)`](/cells/python-net/tr/aspose.cells/cellshelper/row_name_to_index/#str) | Satır adına göre satır indeksini alır.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/tr/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Hücrenin r1c1 formülünü A1 formülüne dönüştürür.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/tr/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |Hücrenin A1 formülünü r1c1 formülüne dönüştürür.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/tr/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Çift değeri tarih saat değerine dönüştürün.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/tr/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | Tarih saatini çift değere dönüştür.|
| [`get_used_colors(, workbook)`](/cells/python-net/tr/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | Çalışma kitabında kullanılan tüm renkleri alır.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/tr/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | Eklenti fonksiyonu ekle.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/tr/aspose.cells/cellshelper/merge_files/#list-str-str) | Bazı büyük xls dosyalarını bir xls dosyasına birleştirir.|
| [`get_cache_folder()`](/cells/python-net/tr/aspose.cells/cellshelper/get_cache_folder/#) | Veri önbelleği olarak kullanılabilecek geçici dosyalar için klasörü alır.|
| [`set_cache_folder(, cache)`](/cells/python-net/tr/aspose.cells/cellshelper/set_cache_folder/#str) | Veri önbelleği olarak kullanılabilecek geçici dosyalar için klasörü ayarlar.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/tr/aspose.cells/cellshelper/need_quote_in_formula/#str) | Sayfanın adının tek tırnak içine alınıp alınmayacağını belirtir|
| [`init_for_dot_net_core()`](/cells/python-net/tr/aspose.cells/cellshelper/init_for_dot_net_core/#) | .NetCore programı için başlatma işlemini yapın.<br/> Tüm .NetCore başlatmaları için öncelikle bu metodu çağırmanızı öneririz.<br/>Örneğin:<br/>HücrelerYardımcısı.InitForDotNetCore();<br/> Çalışma Kitabı wb = yeni Çalışma Kitabı();|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
