---
title: TxtSaveOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1590
url: /tr/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions sınıfı
CSV/sekmeyle ayrılmış/diğer metin biçimi için kaydetme seçeneklerini temsil eder.



**Miras:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)



TxtSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/txtsaveoptions/__init__/#) | Metin dosyası kaydetme seçeneklerini oluşturur.|
| [__init__](/cells/python-net/tr/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) | Metin dosyası kaydetme seçeneklerini oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells/txtsaveoptions/save_format) | Kaydetme dosyası formatını alır.|
| [clear_data](/cells/python-net/tr/aspose.cells/txtsaveoptions/clear_data) | Dosyayı kaydettikten sonra çalışma kitabını boşaltın.|
| [cached_file_folder](/cells/python-net/tr/aspose.cells/txtsaveoptions/cached_file_folder) | Önbelleğe alınmış dosya klasörü bazı büyük verileri depolamak için kullanılır.|
| [validate_merged_areas](/cells/python-net/tr/aspose.cells/txtsaveoptions/validate_merged_areas) | Dosyayı kaydetmeden önce birleştirilmiş hücrelerin doğrulanıp doğrulanmayacağını belirtir.|
| [merge_areas](/cells/python-net/tr/aspose.cells/txtsaveoptions/merge_areas) | Dosyayı kaydetmeden önce koşullu biçimlendirme ve doğrulama alanlarının birleştirilip birleştirilmeyeceğini belirtir.|
| [create_directory](/cells/python-net/tr/aspose.cells/txtsaveoptions/create_directory) | Doğruysa ve dizin mevcut değilse, dosya kaydedilmeden önce dizin otomatik olarak oluşturulacaktır.|
| [sort_names](/cells/python-net/tr/aspose.cells/txtsaveoptions/sort_names) | Dosyayı kaydetmeden önce tanımlı adların sıralanıp sıralanmayacağını belirtir.|
| [sort_external_names](/cells/python-net/tr/aspose.cells/txtsaveoptions/sort_external_names) | Dosyayı kaydetmeden önce harici tanımlı adların sıralanıp sıralanmayacağını belirtir.|
| [refresh_chart_cache](/cells/python-net/tr/aspose.cells/txtsaveoptions/refresh_chart_cache) | Grafik önbellek verilerinin yenilenip yenilenmeyeceğini belirtir|
| [warning_callback](/cells/python-net/tr/aspose.cells/txtsaveoptions/warning_callback) | Uyarı geri aramasını alır veya ayarlar.|
| [update_smart_art](/cells/python-net/tr/aspose.cells/txtsaveoptions/update_smart_art) | Smart art ayarının güncellenip güncellenmeyeceğini belirtir.<br/> Varsayılan değer false'tur.|
| [separator](/cells/python-net/tr/aspose.cells/txtsaveoptions/separator) | Metin dosyasının karakter Ayırıcısını alır ve ayarlar.|
| [separator_string](/cells/python-net/tr/aspose.cells/txtsaveoptions/separator_string) | Ayırıcı olarak bir dize değeri alır ve ayarlar.|
| [encoding](/cells/python-net/tr/aspose.cells/txtsaveoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar.|
| [always_quoted](/cells/python-net/tr/aspose.cells/txtsaveoptions/always_quoted) | Her alan için her zaman '"' eklenip eklenmeyeceğini belirtir.<br/>Doğruysa tüm değerler alıntılanır;<br/>Yanlışsa değerler yalnızca gerektiğinde alıntılanır (örneğin,<br/>değerler '"', '\n' veya ayırıcı karakter gibi özel karakterler içerdiğinde).<br/> Varsayılan yanlıştır.|
| [quote_type](/cells/python-net/tr/aspose.cells/txtsaveoptions/quote_type) | Dışa aktarılan metin dosyasındaki değerlerin nasıl alıntılanacağını alır veya ayarlar.|
| [format_strategy](/cells/python-net/tr/aspose.cells/txtsaveoptions/format_strategy) | Hücre değerini dize olarak dışa aktarırken biçim stratejisini alır ve ayarlar.|
| [light_cells_data_provider](/cells/python-net/tr/aspose.cells/txtsaveoptions/light_cells_data_provider) | Çalışma kitabını ışık modunda kaydetmek için veri sağlayıcı.|
| [trim_leading_blank_row_and_column](/cells/python-net/tr/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | MS Excel'in yaptığı gibi öndeki boş satırların ve sütunların kırpılıp kırpılmayacağını belirtir.<br/> Varsayılan doğrudur.|
| [trim_tailing_blank_cells](/cells/python-net/tr/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Bir satırdaki kuyruktaki boş hücrelerin kırpılıp kırpılmayacağını belirtir. Varsayılan yanlıştır.|
| [keep_separators_for_blank_row](/cells/python-net/tr/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |Boş satır için ayırıcıların çıktısının alınıp alınmayacağını belirtir.<br/> Varsayılan değer false olduğundan boş satırın içeriği varsayılan olarak boş olacaktır.|
| [export_area](/cells/python-net/tr/aspose.cells/txtsaveoptions/export_area) | Dışa aktarılacak hücre aralığı.|
| [export_quote_prefix](/cells/python-net/tr/aspose.cells/txtsaveoptions/export_quote_prefix) | Tek tırnak işaretinin bir hücrenin değerinin bir parçası olarak dışa aktarılıp aktarılmayacağını belirtir<br/> [`Style.quote_prefix`](/cells/python-net/tr/aspose.cells/style#quote_prefix) bunun için doğru olduğunda. Varsayılan yanlıştır.|
| [export_all_sheets](/cells/python-net/tr/aspose.cells/txtsaveoptions/export_all_sheets) | Tüm sayfaların metin dosyasına aktarılıp aktarılmayacağını belirtir.<br/> Yanlışsa, MS Excel'de olduğu gibi yalnızca etkin sayfayı dışa aktarın.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)
* sınıf [`TxtSaveOptions`](/cells/python-net/tr/aspose.cells/txtsaveoptions)
