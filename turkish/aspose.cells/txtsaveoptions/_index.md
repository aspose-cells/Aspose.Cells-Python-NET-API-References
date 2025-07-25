---
title: TxtSaveOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1500
url: /tr/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions sınıfı
CSV/sekmeyle ayrılmış/diğer metin biçimleri için kaydetme seçeneklerini temsil eder.



**Miras:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)



TxtSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/txtsaveoptions/__init__/#) | Metin dosyası kaydetme seçenekleri oluşturur.|
| [`__init__(self, save_format)`](/cells/python-net/tr/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | Metin dosyası kaydetme seçenekleri oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells/txtsaveoptions/save_format) | Kaydetme dosyasının formatını alır.|
| [clear_data](/cells/python-net/tr/aspose.cells/txtsaveoptions/clear_data) | Dosyayı kaydettikten sonra çalışma kitabını boş hale getirin.|
| [cached_file_folder](/cells/python-net/tr/aspose.cells/txtsaveoptions/cached_file_folder) | Veri önbelleği olarak kullanılabilecek geçici dosyalar için klasör.|
| [validate_merged_areas](/cells/python-net/tr/aspose.cells/txtsaveoptions/validate_merged_areas) | Dosyayı kaydetmeden önce birleştirilmiş hücrelerin doğrulanıp doğrulanmayacağını belirtir.|
| [merge_areas](/cells/python-net/tr/aspose.cells/txtsaveoptions/merge_areas) | Dosyayı kaydetmeden önce koşullu biçimlendirme ve doğrulama alanlarının birleştirilip birleştirilmeyeceğini belirtir.|
| [create_directory](/cells/python-net/tr/aspose.cells/txtsaveoptions/create_directory) | Eğer doğruysa ve dizin mevcut değilse, dosya kaydedilmeden önce dizin otomatik olarak oluşturulacaktır.|
| [sort_names](/cells/python-net/tr/aspose.cells/txtsaveoptions/sort_names) |Dosyayı kaydetmeden önce tanımlanmış isimlerin sıralanıp sıralanmayacağını belirtir.|
| [sort_external_names](/cells/python-net/tr/aspose.cells/txtsaveoptions/sort_external_names) | Dosyayı kaydetmeden önce harici olarak tanımlanmış adların sıralanıp sıralanmayacağını belirtir.|
| [refresh_chart_cache](/cells/python-net/tr/aspose.cells/txtsaveoptions/refresh_chart_cache) | Grafik önbellek verilerinin yenilenip yenilenmeyeceğini belirtir|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells/txtsaveoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/> 32K'dan uzun bir değer girdiğinizde, bu değer kesilecektir.|
| [update_smart_art](/cells/python-net/tr/aspose.cells/txtsaveoptions/update_smart_art) | Akıllı sanat ayarının güncellenip güncellenmediğini gösterir.<br/> Varsayılan değer false'tur.|
| [encrypt_document_properties](/cells/python-net/tr/aspose.cells/txtsaveoptions/encrypt_document_properties) | .xls dosyası olarak kaydederken belge özelliklerinin şifrelenip şifrelenmeyeceğini belirtir.<br/> Varsayılan değer doğrudur.|
| [separator](/cells/python-net/tr/aspose.cells/txtsaveoptions/separator) | Metin dosyasının char ayırıcısını alır ve ayarlar.|
| [separator_string](/cells/python-net/tr/aspose.cells/txtsaveoptions/separator_string) | Ayırıcı olarak bir dize değeri alır ve ayarlar.|
| [encoding](/cells/python-net/tr/aspose.cells/txtsaveoptions/encoding) | Varsayılan kodlamayı alır ve ayarlar.|
| [always_quoted](/cells/python-net/tr/aspose.cells/txtsaveoptions/always_quoted) | Her alan için her zaman '"' eklenip eklenmeyeceğini belirtir.<br/>Eğer doğruysa tüm değerler tırnak içine alınacaktır;<br/>Eğer yanlışsa, değerler yalnızca ihtiyaç duyulduğunda tırnak işareti içine alınacaktır (örneğin,<br/>değerler '"', '\n' veya ayırıcı karakter gibi özel karakterler içerdiğinde).<br/> Varsayılan değer false'tur.|
| [quote_type](/cells/python-net/tr/aspose.cells/txtsaveoptions/quote_type) |Dışa aktarılan metin dosyasındaki değerlerin nasıl alıntılanacağını alır veya ayarlar.|
| [format_strategy](/cells/python-net/tr/aspose.cells/txtsaveoptions/format_strategy) | Hücre değerini dize olarak dışa aktarırken biçim stratejisini alır ve ayarlar.|
| [trim_leading_blank_row_and_column](/cells/python-net/tr/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Öndeki boş satır ve sütunların, MS Excel'in yaptığı gibi kırpılıp kırpılmayacağını belirtir.<br/> Varsayılan değer doğrudur.|
| [trim_tailing_blank_cells](/cells/python-net/tr/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Bir satırdaki boş hücrelerin kırpılıp kırpılmayacağını belirtir. Varsayılan değer false'tur.|
| [keep_separators_for_blank_row](/cells/python-net/tr/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Boş satırlar için ayırıcıların çıktı olarak verilip verilmeyeceğini belirtir.<br/> Varsayılan değer false olduğundan varsayılan olarak boş satırın içeriği boş olacaktır.|
| [export_area](/cells/python-net/tr/aspose.cells/txtsaveoptions/export_area) | Dışa aktarılacak hücre aralığı.|
| [export_quote_prefix](/cells/python-net/tr/aspose.cells/txtsaveoptions/export_quote_prefix) | Tek tırnak işaretinin bir hücrenin değerinin bir parçası olarak dışa aktarılıp aktarılmayacağını belirtir<br/> [`Style.quote_prefix`](/cells/python-net/tr/aspose.cells/style#quote_prefix) bunun için doğruysa. Varsayılanı yanlıştır.|
| [export_all_sheets](/cells/python-net/tr/aspose.cells/txtsaveoptions/export_all_sheets) | Tüm sayfaların metin dosyasına aktarılıp aktarılmayacağını belirtir.<br/> Eğer yanlışsa, tıpkı MS Excel'de olduğu gibi sadece aktif sayfayı dışa aktarın.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)
* sınıf [`TxtSaveOptions`](/cells/python-net/tr/aspose.cells/txtsaveoptions)
