---
title: GlobalizationSettings sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 740
url: /tr/aspose.cells/globalizationsettings/
is_root: false
---
##  GlobalizationSettings sınıfı
Küreselleşme ayarlarını temsil eder.



GlobalizationSettings türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/__init__/#) | GlobalizationSettings'in yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [chart_settings](/cells/python-net/tr/aspose.cells/globalizationsettings/chart_settings) | Chart için küreselleştirme ayarlarını alır veya ayarlar.|
| [pivot_settings](/cells/python-net/tr/aspose.cells/globalizationsettings/pivot_settings) | Pivot tablonun küreselleştirme ayarlarını alır veya ayarlar.|
| [list_separator](/cells/python-net/tr/aspose.cells/globalizationsettings/list_separator) | Liste için ayırıcıyı, fonksiyon parametrelerini, ...vb. alır.|
| [row_separator_of_formula_array](/cells/python-net/tr/aspose.cells/globalizationsettings/row_separator_of_formula_array) | Formüldeki dizi verilerindeki satırlar için ayırıcıyı alır.|
| [column_separator_of_formula_array](/cells/python-net/tr/aspose.cells/globalizationsettings/column_separator_of_formula_array) |Formüldeki dizinin satır verilerindeki öğeler için ayırıcıyı alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_pivot_total_name/#) | PivotTable'daki "Toplam" etiketinin adını alır.<br/> PivotTable'ın veri alanında iki veya daha fazla PivotField olması durumunda bu yöntemi geçersiz kılmanız gerekir.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_pivot_grand_total_name/#) | PivotTable'daki "Genel Toplam" etiketinin adını alır.|
| [`get_multiple_items_name(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_multiple_items_name/#) | PivotTable'daki "(Birden Çok Öğe)" etiketinin adını alır.|
| [`get_all_name(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_all_name/#) | PivotTable'daki "(Tümü)" etiketinin adını alır.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_protection_name_of_pivot_table/#) | PivotTable'daki koruma adını alır.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_column_labels_of_pivot_table/#) | PivotTable'daki "Sütun Etiketleri" etiketinin adını alır.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_row_labels_name_of_pivot_table/#) | PivotTable'daki "Satır Etiketleri" etiketinin adını alır.|
| [`get_empty_data_name(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_empty_data_name/#) | PivotTable'daki "(boş)" etiketinin adını alır.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_data_field_header_name_of_pivot_table/#) | PivotTable'daki değer alanı başlığının adını alır.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | PivotTable'daki [`PivotFieldSubtotalType`](/cells/python-net/tr/aspose.cells.pivot/pivotfieldsubtotaltype) tipinin adını alır.|
| [`get_total_name(self, function_type)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Fonksiyonun toplam adını alır.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Fonksiyonun büyük toplam adını alır.|
| [`get_default_sheet_name(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_default_sheet_name/#) |Çalışma sayfasını otomatik olarak eklemek için varsayılan sayfa adını alır.<br/> Varsayılan "Sayfa"dır.|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_table_row_type_of_headers/#) | Tablo başlığından oluşan tablo satırlarının tür adını alır.<br/> Varsayılan "Başlıklar"dır, dolayısıyla formülde "#Başlıklar" tablo başlığını temsil eder.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_table_row_type_of_data/#) | Başvurulan tablonun veri bölgesinden oluşan tablo satırlarının tür adını alır.<br/> Varsayılan "Veri"dir, dolayısıyla formülde "#Veri" tablonun veri bölgesini temsil eder.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_table_row_type_of_all/#) | Başvurulan tablodaki tüm satırlardan oluşan tablo satırlarının tür adını alır.<br/> Varsayılan "Tümü"dür, dolayısıyla formülde "#Tümü" referans alınan tablodaki tüm satırları temsil eder.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_table_row_type_of_totals/#) | Başvurulan tablonun toplam satırından oluşan tablo satırlarının tür adını alır.<br/> Varsayılan "Toplamlar"dır, dolayısıyla formülde "#Toplamlar" referans alınan tablonun toplam satırını temsil eder.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_table_row_type_of_current/#) | Başvurulan tablodaki geçerli satırı içeren tablo satırlarının tür adını alır.<br/>Varsayılan "Bu Satır"dır, dolayısıyla formülde "#Bu Satır" referans verilen tabloda geçerli satırı temsil eder.|
| [`get_error_value_string(self, err)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_error_value_string/#str) | Hücrenin hata değeri için görüntüleme dizesi değerini alır|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_boolean_value_string/#bool) | Hücrenin Boolean değeri için görüntüleme dizesi değerini alır|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_local_function_name/#str) | Verilen standart fonksiyon adına göre yerel bağımlı fonksiyon adını alır.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_standard_function_name/#str) | Verilen yerel bağımlı fonksiyon adına göre standart fonksiyon adını alır.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_local_built_in_name/#str) | Verilen standart metne göre yerleşik Ad için yerel bağımlı metni alır.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_standard_built_in_name/#str) | Verilen yerel bağımlı metne göre yerleşik Adın standart metnini alır.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_standard_header_footer_font_style_name/#str) | Verilen yerel yazı tipi adına göre Başlık/Altbilgi için standart İngilizce yazı tipi adı (Normal, Kalın, İtalik) alınır.|
| [`get_comment_title_name(self, type)`](/cells/python-net/tr/aspose.cells/globalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Yorum başlığı türüne göre yerel ayarlara bağlı yorum başlığı adını alır.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/tr/aspose.cells/globalizationsettings/compare/#str-str-bool) | İki dize değerini belirli sıralama kurallarına göre karşılaştırır.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`PivotFieldSubtotalType`](/cells/python-net/tr/aspose.cells.pivot/pivotfieldsubtotaltype)
