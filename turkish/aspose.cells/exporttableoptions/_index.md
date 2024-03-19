---
title: ExportTableOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 580
url: /tr/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions sınıfı
Tüm dışarı aktarma tablosu seçeneklerini temsil eder.



ExportTableOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/exporttableoptions/__init__/#) | ExportTableOptions'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [export_column_name](/cells/python-net/tr/aspose.cells/exporttableoptions/export_column_name) | İlk satırdaki verilerin DataTable'ın sütun adına aktarılıp aktarılmadığını gösterir.<br/> Varsayılan değer false'tur.|
| [skip_error_value](/cells/python-net/tr/aspose.cells/exporttableoptions/skip_error_value) | Sütun için geçersiz değerin atlanıp atlanmayacağını belirtir.<br/> Örneğin, sütun türü ondalık ise değer ondalıktan büyüktür.MaxValue<br/>ve bu özellik doğrudur, bir daha istisna atmayacağız.<br/> Varsayılan değer false'tur.|
| [plot_visible_cells](/cells/python-net/tr/aspose.cells/exporttableoptions/plot_visible_cells) | Yalnızca görünür hücreleri dışa aktarır.|
| [plot_visible_rows](/cells/python-net/tr/aspose.cells/exporttableoptions/plot_visible_rows) | Yalnızca görünür satırları dışa aktarır.|
| [plot_visible_columns](/cells/python-net/tr/aspose.cells/exporttableoptions/plot_visible_columns) | Yalnızca görünür sütunları dışa aktarır.|
| [export_as_string](/cells/python-net/tr/aspose.cells/exporttableoptions/export_as_string) | Hücrelerin dize değerini DataTable'a aktarır.|
| [export_as_html_string](/cells/python-net/tr/aspose.cells/exporttableoptions/export_as_html_string) | Hücrelerin html dize değerini DataTable'a aktarır.|
| [format_strategy](/cells/python-net/tr/aspose.cells/exporttableoptions/format_strategy) | Değeri dize değeri olarak dışa aktarırken biçim stratejisini alır ve ayarlar.|
| [check_mixed_value_type](/cells/python-net/tr/aspose.cells/exporttableoptions/check_mixed_value_type) | Yanlış, Aspose.Cells, performans için DataColumn'un türünü ilk satırın değer türüne göre ayarlayacaktır.<br/> Doğru, Aspose.Cells, DataColumn'un türünü ayarlamadan önce sütundaki değer türünün karıştırılıp karıştırılmadığını kontrol edecektir.<br/>Ve değer türü karışıktır, DataColumn'un türü string olacaktır.|
| [allow_db_null](/cells/python-net/tr/aspose.cells/exporttableoptions/allow_db_null) | Bu değer, bu tabloda DBNull'lara izin verilip verilmediğini gösterir.|
| [is_vertical](/cells/python-net/tr/aspose.cells/exporttableoptions/is_vertical) | Çalışma Kitabı dosyasındaki bir satır DataTable'daki bir satırı temsil ediyorsa doğrudur. Çalışma Kitabı dosyasındaki bir sütun DataTable'daki bir satırı temsil ediyorsa false.|
| [indexes](/cells/python-net/tr/aspose.cells/exporttableoptions/indexes) | Dışa aktarılması gereken sütunların/satırların dizinleri.|
| [rename_strategy](/cells/python-net/tr/aspose.cells/exporttableoptions/rename_strategy) | Sütunların yinelenen adlarına yönelik strateji.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/tr/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) | Dışa aktarılacak mevcut hücrenin değerini önceden işleyin.|



###  Notlar

Dışa aktarmayla ilgili hata değerlerinin göz ardı edilmesi gibi bazı özel gereksinimler varsa kullanıcı bu sınıfı genişletebilir
hedefe ulaşmak için ilgili API'lerin üzerine yazmak.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
