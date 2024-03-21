---
title: CellsHelper sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 240
url: /tr/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper sınıfı
Yardımcı işlevler sağlar.



CellsHelper türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [significant_digits](/cells/python-net/tr/aspose.cells/cellshelper/significant_digits) | Önemli basamakların sayısını alır ve ayarlar.<br/> Varsayılan değer 17'dir.|
| [dpi](/cells/python-net/tr/aspose.cells/cellshelper/dpi) | Makinenin DPI'sını alır.|
| [startup_path](/cells/python-net/tr/aspose.cells/cellshelper/startup_path) | Bazı dış formül başvuruları tarafından başvurulan başlangıç yolunu alır veya ayarlar.|
| [alt_start_path](/cells/python-net/tr/aspose.cells/cellshelper/alt_start_path) | Bazı dış formül başvuruları tarafından başvurulan alternatif başlangıç yolunu alır veya ayarlar.|
| [library_path](/cells/python-net/tr/aspose.cells/cellshelper/library_path) | Bazı dış formül başvuruları tarafından başvurulan kitaplık yolunu alır veya ayarlar.|
| [custom_implementation_factory](/cells/python-net/tr/aspose.cells/cellshelper/custom_implementation_factory) | Özel uygulamayla örnekler oluşturmak için fabrikayı alır veya ayarlar.|
| [is_cloud_platform](/cells/python-net/tr/aspose.cells/cellshelper/is_cloud_platform) | Lütfen Azure, AWSLambda vb. gibi bir bulut platformunda çalışırken bu özelliği True olarak ayarlayın.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/tr/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Verilen sayfa adını kontrol eder ve gerektiğinde geçerli bir sayfa adı oluşturur.<br/>Verilen sayfa adı, Excel sayfa adı kurallarına uyuyorsa, onu döndürün.<br/>Aksi halde uzunluk sınırı aşarsa dize kesilecektir<br/>ve geçersiz karakterler '' ile değiştirilecek, ardından yeniden oluşturulan dize değeri döndürülecektir.|
| [create_safe_sheet_name](/cells/python-net/tr/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Verilen sayfa adını kontrol eder ve gerektiğinde geçerli bir sayfa adı oluşturur.<br/>Verilen sayfa adı, Excel sayfa adı kurallarına uyuyorsa, onu döndürün.<br/>Aksi halde uzunluk sınırı aşarsa dize kesilecektir<br/> ve geçersiz karakterler verilen karakterle değiştirilecek, ardından yeniden oluşturulan dize değeri döndürülecek.|
| [get_text_width](/cells/python-net/tr/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | Metnin genişliğini nokta birimi cinsinden alın.|
| [get_version](/cells/python-net/tr/aspose.cells/cellshelper/get_version/#) | Yayın sürümünü edinin.|
| [cell_name_to_index](/cells/python-net/tr/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Adına göre hücre satır ve sütun indekslerini alır.|
| [cell_index_to_name](/cells/python-net/tr/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Satır ve sütun indekslerine göre hücre adını alır.|
| [column_index_to_name](/cells/python-net/tr/aspose.cells/cellshelper/column_index_to_name/#int) | Sütun indeksine göre sütun adını alır.|
| [column_name_to_index](/cells/python-net/tr/aspose.cells/cellshelper/column_name_to_index/#str) | Sütun adına göre sütun indeksini alır.|
| [row_index_to_name](/cells/python-net/tr/aspose.cells/cellshelper/row_index_to_name/#int) | Satır indeksine göre satır adını alır.|
| [row_name_to_index](/cells/python-net/tr/aspose.cells/cellshelper/row_name_to_index/#str) | Satır adına göre satır indeksini alır.|
| [convert_r1c1_formula_to_a1](/cells/python-net/tr/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Hücrenin r1c1 formülünü A1 formülüne dönüştürür.|
| [convert_a1_formula_to_r1c1](/cells/python-net/tr/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | Hücrenin A1 formülünü r1c1 formülüne dönüştürür.|
| [get_date_time_from_double](/cells/python-net/tr/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Double değerini tarih saat değerine dönüştürün.|
| [get_double_from_date_time](/cells/python-net/tr/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | Tarih saatini çift değere dönüştürün.|
| [get_used_colors](/cells/python-net/tr/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | Çalışma kitabındaki tüm kullanılan renkleri alır.|
| [add_add_in_function](/cells/python-net/tr/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | Eklenti işlevi ekleyin.|
| [merge_files](/cells/python-net/tr/aspose.cells/cellshelper/merge_files/#list-str-str) | Bazı büyük xls dosyalarını bir xls dosyasıyla birleştirir.|
| [need_quote_in_formula](/cells/python-net/tr/aspose.cells/cellshelper/need_quote_in_formula/#str) |Sayfa adının tek tırnak içine alınması gerekip gerekmediğini belirtir|
| [init_for_dot_net_core](/cells/python-net/tr/aspose.cells/cellshelper/init_for_dot_net_core/#) | .NetCore programının başlatılmasını yapın.<br/> Tüm .NetCore başlatma işlemleri için öncelikle bu yöntemi çağırmanızı öneririz.<br/>Örneğin:<br/>CellsHelper.InitForDotNetCore();<br/> Çalışma Kitabı wb = yeni Çalışma Kitabı();|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
