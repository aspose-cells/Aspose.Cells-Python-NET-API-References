---
title: WorksheetCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1610
url: /tr/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection sınıfı
[`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet) nesneden oluşan bir koleksiyonu kapsüller.



WorksheetCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/tr/aspose.cells/worksheetcollection/web_extension_task_panes) | Görev bölmelerinin listesini alır.|
| [web_extensions](/cells/python-net/tr/aspose.cells/worksheetcollection/web_extensions) | Görev bölmelerinin listesini alır.|
| [threaded_comment_authors](/cells/python-net/tr/aspose.cells/worksheetcollection/threaded_comment_authors) | Yorum yapan yazarların listesini alır.|
| [is_refresh_all_connections](/cells/python-net/tr/aspose.cells/worksheetcollection/is_refresh_all_connections) | MS Excel'de dosya açıldığında tüm bağlantıların yenilenip yenilenmeyeceğini belirtir.|
| [names](/cells/python-net/tr/aspose.cells/worksheetcollection/names) | E-tablodaki tüm Name nesnelerinin koleksiyonunu alır.|
| [active_sheet_name](/cells/python-net/tr/aspose.cells/worksheetcollection/active_sheet_name) | Elektronik tablo açıldığında etkin çalışma sayfasının adını temsil eder.|
| [active_sheet_index](/cells/python-net/tr/aspose.cells/worksheetcollection/active_sheet_index) | Elektronik tablo açıldığında etkin çalışma sayfasının dizinini temsil eder.|
| [dxfs](/cells/python-net/tr/aspose.cells/worksheetcollection/dxfs) | Ana diferansiyel biçimlendirme kayıtlarını alır.|
| [xml_maps](/cells/python-net/tr/aspose.cells/worksheetcollection/xml_maps) | Çalışma kitabındaki XML haritalarını alır ve ayarlar.|
| [built_in_document_properties](/cells/python-net/tr/aspose.cells/worksheetcollection/built_in_document_properties) | E-tablonun tüm yerleşik belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.|
| [custom_document_properties](/cells/python-net/tr/aspose.cells/worksheetcollection/custom_document_properties) | Elektronik tablonun tüm özel belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.|
| [ole_size](/cells/python-net/tr/aspose.cells/worksheetcollection/ole_size) | Çalışma kitabı dosyası bir Ole nesnesi olarak kullanıldığında görüntülenen boyutu alır ve ayarlar.|
| [external_links](/cells/python-net/tr/aspose.cells/worksheetcollection/external_links) |Bir çalışma kitabındaki harici bağlantıları temsil eder.|
| [table_styles](/cells/python-net/tr/aspose.cells/worksheetcollection/table_styles) | [`WorksheetCollection.table_styles`](/cells/python-net/tr/aspose.cells/worksheetcollection#table_styles) nesnesini alır.|
| [revision_logs](/cells/python-net/tr/aspose.cells/worksheetcollection/revision_logs) | Revizyon kayıtlarını temsil eder.|
| [sensitivity_labels](/cells/python-net/tr/aspose.cells/worksheetcollection/sensitivity_labels) | Tüm hassasiyet etiketlerini temsil eder.|
| [capacity](/cells/python-net/tr/aspose.cells/worksheetcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|



Belirtilen indeksteki [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet) öğesini alır.
###  Dizinleyici
| İsim| Tanım|
| :- | :- |
| [index] | Elemanın sıfırdan başlayan indeksi.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get(self, index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get/#int) | API for Python'i .Net yoluyla ekleyin. Bu[int index] desteklenmediğinden|
| [`get(self, sheet_name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get/#str) | API for Python'i .Net yoluyla ekleyin. Bu[string sheetName] desteklenmediğinden|
| [`add(self, type)`](/cells/python-net/tr/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Koleksiyona bir çalışma sayfası ekler.|
| [`add(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/add/#) | Koleksiyona bir çalışma sayfası ekler.|
| [`add(self, sheet_name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/add/#str) | Koleksiyona bir çalışma sayfası ekler.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/tr/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Çalışma kitabına eklenti işlevi ekler|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Çalışma kitabına eklenti işlevi ekler|
| [`add_copy(self, sheet_name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/add_copy/#str) | Koleksiyona bir çalışma sayfası ekler ve var olan bir çalışma sayfasından verileri kopyalar.|
| [`add_copy(self, sheet_index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/add_copy/#int) | Koleksiyona bir çalışma sayfası ekler ve var olan bir çalışma sayfasından verileri kopyalar.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/tr/aspose.cells/worksheetcollection/add_copy/#list-list) | Bir grup çalışma kağıdını kopyalayın.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get_range_by_name/#str) | Önceden tanımlanmış ada göre Range nesnesini alır.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Önceden tanımlanmış ad veya tablonun adına göre [`Range`](/cells/python-net/tr/aspose.cells/range)'i alır|
| [`refresh_pivot_tables(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Excel dosyasındaki tüm PivotTable'ları yeniler.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/tr/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Excel dosyasındaki tüm PivotTable'ları yeniler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/worksheetcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/create_range/#str-int) | Aralığın bir adresinden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini oluşturur.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/create_union_range/#str-int) | Aralığın bir adresinden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini oluşturur.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Kod adına göre çalışma sayfasını alır.|
| [`sort_names(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/sort_names/#) | Tanımlanan isimleri sıralar.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/tr/aspose.cells/worksheetcollection/swap_sheet/#int-int) | İki sayfayı değiştirir.|
| [`remove_by_name(self, name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/remove_by_name/#str) | Sayfa adına göre bir sayfayı kaldırın.(CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/tr/aspose.cells/worksheetcollection/remove_by_index/#int) | Sayfa sayfa indeksi kaldır|
| [`remove_at(self, name)`](/cells/python-net/tr/aspose.cells/worksheetcollection/remove_at/#str) | Belirtilen isimdeki öğeyi kaldırır.|
| [`get_named_ranges(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get_named_ranges/#) | E-tabloda önceden tanımlanmış tüm adlandırılmış aralıkları alır.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | E-tabloda önceden tanımlanmış tüm adlandırılmış aralıkları alır.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/tr/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Çalışma Kitabı dosyası bir Ole nesnesi olarak kullanıldığında görüntülenen boyutu ayarlar.|
| [`clear_pivottables(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/clear_pivottables/#) |Pivot tabloları elektronik tablodan temizler.|
| [`refresh_all(self)`](/cells/python-net/tr/aspose.cells/worksheetcollection/refresh_all/#) | Pivot kaynağı ile tüm pivot tabloları ve grafikleri yenile.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
