---
title: ExportTableOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 560
url: /tr/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions sınıfı
Tüm dışa aktarma tablosu seçeneklerini temsil eder.



ExportTableOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/exporttableoptions/__init__/#) | ExportTableOptions'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [export_column_name](/cells/python-net/tr/aspose.cells/exporttableoptions/export_column_name) | DataTable'ın ilk satırındaki verilerin, DataTable'ın sütun adına aktarılıp aktarılmayacağını belirtir.<br/> Varsayılan değer false'tur.|
| [skip_error_value](/cells/python-net/tr/aspose.cells/exporttableoptions/skip_error_value) | Sütun için geçersiz değerin atlanıp atlanmayacağını belirtir.<br/> Örneğin, sütun türü ondalık ise, değer ondalıktan büyüktür.MaxValue<br/>ve bu özellik doğruysa, bir daha istisna fırlatmayacağız.<br/> Varsayılan değer false'tur.|
| [plot_visible_cells](/cells/python-net/tr/aspose.cells/exporttableoptions/plot_visible_cells) | Sadece görünür hücreleri dışa aktarır.|
| [plot_visible_rows](/cells/python-net/tr/aspose.cells/exporttableoptions/plot_visible_rows) | Sadece görünen satırları dışa aktarır.|
| [plot_visible_columns](/cells/python-net/tr/aspose.cells/exporttableoptions/plot_visible_columns) | Sadece görünen sütunları dışa aktarır.|
| [export_as_string](/cells/python-net/tr/aspose.cells/exporttableoptions/export_as_string) | Hücrelerin dize değerini DataTable'a aktarır.|
| [export_as_html_string](/cells/python-net/tr/aspose.cells/exporttableoptions/export_as_html_string) | Hücrelerin html string değerini DataTable'a aktarır.|
| [format_strategy](/cells/python-net/tr/aspose.cells/exporttableoptions/format_strategy) | Değeri dize değeri olarak dışa aktarırken biçim stratejisini alır ve ayarlar.|
| [check_mixed_value_type](/cells/python-net/tr/aspose.cells/exporttableoptions/check_mixed_value_type) | False, Aspose.Cells performans için DataColumn'un türünü ilk satırın değer türüne göre ayarlayacaktır.<br/> Doğru, Aspose.Cells, DataColumn'un türünü ayarlamadan önce sütundaki değer türlerinin karışık olup olmadığını kontrol edecektir<br/> Ve değer türleri karışıktır, DataColumn'un türü string olacaktır.|
| [allow_db_null](/cells/python-net/tr/aspose.cells/exporttableoptions/allow_db_null) |Bu değer, bu tabloda DBNull'lara izin verilip verilmediğini gösterir.|
| [is_vertical](/cells/python-net/tr/aspose.cells/exporttableoptions/is_vertical) | Çalışma Kitabı dosyasındaki bir satır DataTable'daki bir satırı temsil ediyorsa True. Çalışma Kitabı dosyasındaki bir sütun DataTable'daki bir satırı temsil ediyorsa False.|
| [indexes](/cells/python-net/tr/aspose.cells/exporttableoptions/indexes) | Dışarıya aktarılması gereken sütun/satırların indeksleri.|
| [rename_strategy](/cells/python-net/tr/aspose.cells/exporttableoptions/rename_strategy) | Sütun adlarının tekrarlanmasına yönelik strateji.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/tr/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) | Dışa aktarılacak geçerli hücrenin değerini önceden işleyin.|



###  Notlar

Dışa aktarmayla ilgili bazı özel gereksinimler varsa, örneğin hata değerlerini yok saymak gibi, kullanıcı bu sınıfı genişletebilir
Hedefe ulaşmak için karşılık gelen API'leri üzerine yazmak.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
