---
title: TimelineCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.timelines/timelinecollection/
is_root: false
---
##  TimelineCollection sınıfı
Belirtilen çalışma sayfasındaki tüm Zaman Çizelgesi nesnelerinin koleksiyonunu belirtir.
MS Excel nedeniyle Excel 2003 Zaman Çizelgesi'ni desteklemez.



TimelineCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin|
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-str) | PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-int) | PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-int) | PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/get/#str) | Zaman çizelgesinin adına göre Zaman Çizelgesini alır.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection/binary_search/#aspose.cells.timelines.timeline) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import CellsFactory, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from datetime import datetime

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
# Create date style
dateStyle = CellsFactory().create_style()
dateStyle.custom = "m/d/yyyy"
cells.get(0, 1).value = "date"
cells.get(1, 1).value = datetime(2021, 2, 5)
cells.get(2, 1).value = datetime(2022, 3, 8)
cells.get(3, 1).value = datetime(2023, 4, 10)
cells.get(4, 1).value = datetime(2024, 5, 16)
# Set date style
cells.get(1, 1).set_style(dateStyle)
cells.get(2, 1).set_style(dateStyle)
cells.get(3, 1).set_style(dateStyle)
cells.get(4, 1).set_style(dateStyle)
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
pivots = sheet.pivot_tables
# Add a PivotTable
pivotIndex = pivots.add("=Sheet1!A1:C5", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "date")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Refresh PivotTable data
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.timelines`](..)
