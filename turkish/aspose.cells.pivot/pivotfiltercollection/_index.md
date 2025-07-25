---
title: PivotFilterCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells.pivot/pivotfiltercollection/
is_root: false
---
##  PivotFilterCollection sınıfı
Tüm PivotFilter nesnelerinin bir koleksiyonunu temsil eder



PivotFilterCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`add(self, field_index, type)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/add/#int-aspose.cells.pivot.pivotfiltertype) | Belirli türe bir PivotFilter Nesnesi ekler|
| [`add_top_10_filter(self, base_field_index, value_field_index, type, is_top, item_count)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/add_top_10_filter/#int-int-aspose.cells.pivot.pivotfiltertype-bool-int) | Veri pivot alanının değerlerine göre filtreler.|
| [`add_value_filter(self, base_field_index, value_field_index, type, value1, value2)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/add_value_filter/#int-int-aspose.cells.pivot.pivotfiltertype-float-float) | Veri pivot alanının değerlerine göre filtreler.|
| [`add_label_filter(self, base_field_index, type, label1, label2)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/add_label_filter/#int-aspose.cells.pivot.pivotfiltertype-str-str) | Satır veya sütun pivot alanının başlıklarına göre filtreler.|
| [`add_date_filter(self, base_field_index, type, date_time1, date_time2)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/add_date_filter/#int-aspose.cells.pivot.pivotfiltertype-datetime-datetime) | Satır veya sütun pivot alanının tarih ayarına göre filtreler.|
| [`clear_filter(self, field_index)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/clear_filter/#int) | Belirli PivotField'dan PivotFilter'ı temizleyin|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.pivot/pivotfiltercollection/binary_search/#aspose.cells.pivot.pivotfilter) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](..)
