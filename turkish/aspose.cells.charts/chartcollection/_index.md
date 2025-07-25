---
title: ChartCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection sınıfı
[`Chart`](/cells/python-net/tr/aspose.cells.charts/chart) nesneden oluşan bir koleksiyonu kapsüller.



ChartCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.charts/chartcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Önceden ayarlanmış şablona sahip bir grafik ekler.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [`get(self, index)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/get/#int) | API for Python'i .Net yoluyla ekleyin. Bu[int index] desteklenmediğinden|
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/get/#str) | API for Python'i .Net yoluyla ekleyin. Bu [dize Grafik] desteklenmediğinden|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`Chart`](/cells/python-net/tr/aspose.cells.charts/chart)
