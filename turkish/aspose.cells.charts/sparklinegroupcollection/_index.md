---
title: SparklineGroupCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 300
url: /tr/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection sınıfı
[`SparklineGroup`](/cells/python-net/tr/aspose.cells.charts/sparklinegroup) nesneden oluşan bir koleksiyonu kapsüller.



SparklineGroupCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, type)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | Koleksiyona [`SparklineGroup`](/cells/python-net/tr/aspose.cells.charts/sparklinegroup) ile [`Sparkline`](/cells/python-net/tr/aspose.cells.charts/sparkline)'i ekler.|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | Koleksiyona [`Sparkline`](/cells/python-net/tr/aspose.cells.charts/sparkline) ile [`SparklineGroup`](/cells/python-net/tr/aspose.cells.charts/sparklinegroup)'i ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | Hücre alanının içindeki kıvılcım çizgilerini temizler.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | Hücre alanlarını kaplayan kıvılcım çizgileri gruplarını temizler.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`Sparkline`](/cells/python-net/tr/aspose.cells.charts/sparkline)
* sınıf [`SparklineGroup`](/cells/python-net/tr/aspose.cells.charts/sparklinegroup)
