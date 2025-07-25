---
title: SqlScriptSaveOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells.saving/sqlscriptsaveoptions/
is_root: false
---
##  SqlScriptSaveOptions sınıfı
Sql kaydetme seçeneklerini temsil eder.



**Miras:** [`SqlScriptSaveOptions`](/cells/python-net/aspose.cells.saving/sqlscriptsaveoptions) → 
[`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)



SqlScriptSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/__init__/#) | Sql dosyasını kaydetmeye yönelik seçenekler oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [save_format](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/save_format) | Kaydetme dosyasının formatını alır.|
| [clear_data](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/clear_data) | Dosyayı kaydettikten sonra çalışma kitabını boş hale getirin.|
| [cached_file_folder](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/cached_file_folder) | Veri önbelleği olarak kullanılabilecek geçici dosyalar için klasör.|
| [validate_merged_areas](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/validate_merged_areas) | Dosyayı kaydetmeden önce birleştirilmiş hücrelerin doğrulanıp doğrulanmayacağını belirtir.|
| [merge_areas](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/merge_areas) | Dosyayı kaydetmeden önce koşullu biçimlendirme ve doğrulama alanlarının birleştirilip birleştirilmeyeceğini belirtir.|
| [create_directory](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/create_directory) | Eğer doğruysa ve dizin mevcut değilse, dosya kaydedilmeden önce dizin otomatik olarak oluşturulacaktır.|
| [sort_names](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/sort_names) |Dosyayı kaydetmeden önce tanımlanmış isimlerin sıralanıp sıralanmayacağını belirtir.|
| [sort_external_names](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/sort_external_names) | Dosyayı kaydetmeden önce harici olarak tanımlanmış adların sıralanıp sıralanmayacağını belirtir.|
| [refresh_chart_cache](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/refresh_chart_cache) | Grafik önbellek verilerinin yenilenip yenilenmeyeceğini belirtir|
| [check_excel_restriction](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/check_excel_restriction) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.<br/>Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.<br/> 32K'dan uzun bir değer girdiğinizde, bu değer kesilecektir.|
| [update_smart_art](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/update_smart_art) | Akıllı sanat ayarının güncellenip güncellenmediğini gösterir.<br/> Varsayılan değer false'tur.|
| [encrypt_document_properties](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/encrypt_document_properties) | .xls dosyası olarak kaydederken belge özelliklerinin şifrelenip şifrelenmeyeceğini belirtir.<br/> Varsayılan değer doğrudur.|
| [check_if_table_exists](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/check_if_table_exists) | Oluşturmadan önce tablo adının mevcut olup olmadığını kontrol edin|
| [column_type_map](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/column_type_map) | Farklı veritabanları için sütun türünün haritasını alır ve ayarlar.|
| [check_all_data_for_column_type](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/check_all_data_for_column_type) | Sütunların veri türünü bulmak için tüm verileri kontrol edin.|
| [add_blank_line_between_rows](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/add_blank_line_between_rows) | Her verinin arasına boş bir satır ekleyin.|
| [separator](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/separator) | Sql betiğinin karakter ayırıcısını alır ve ayarlar.|
| [operator_type](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/operator_type) | Sql'in operatör tipini alır ve ayarlar.|
| [primary_key](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/primary_key) | Veri tablosunun birincil anahtarının hangi sütun olduğunu gösterir.|
| [create_table](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/create_table) | Sql'in dışa aktarılmasını mı yoksa tablonun oluşturulmasını mı belirtir.|
| [id_name](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/id_name) | id sütununun adını alır ve ayarlar.|
| [start_id](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/start_id) | Başlangıç kimliğini alır ve ayarlar.|
| [table_name](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/table_name) | Tablo adını alır ve ayarlar.|
| [export_as_string](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/export_as_string) | Tüm verilerin dize değeri olarak dışa aktarılıp aktarılmayacağını belirtir.|
| [sheet_indexes](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/sheet_indexes) |Dışa aktarılan sayfaların dizinlerini temsil eder.|
| [export_area](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/export_area) | Dışa aktarma aralığını alır veya ayarlar.|
| [has_header_row](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions/has_header_row) | Aralığın başlık satırı içerip içermediğini belirtir.|



###  Ayrıca bakınız
* modül [`aspose.cells.saving`](..)
* sınıf [`SaveOptions`](/cells/python-net/tr/aspose.cells/saveoptions)
* sınıf [`SqlScriptSaveOptions`](/cells/python-net/tr/aspose.cells.saving/sqlscriptsaveoptions)
