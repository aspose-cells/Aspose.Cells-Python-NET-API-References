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
| [capacity](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [copy_to](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.SparklineGroup-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.SparklineGroup-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [add](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.SparklineType-str-bool-aspose.cells.CellArea) | Koleksiyona [`SparklineGroup`](/cells/python-net/tr/aspose.cells.charts/sparklinegroup) numaralı öğeyi ekler.|
| [clear_sparklines](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.CellArea) | Hücrelerden oluşan bir alanın içindeki mini grafikleri temizler.|
| [clear_sparkline_groups](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.CellArea) | Bir hücre alanıyla örtüşen mini grafik gruplarını temizler.|
| [binary_search](/cells/python-net/tr/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.SparklineGroup) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



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
idx = sheet.sparkline_group_collection.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_group_collection[idx]
group.sparkline_collection.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`SparklineGroup`](/cells/python-net/tr/aspose.cells.charts/sparklinegroup)
