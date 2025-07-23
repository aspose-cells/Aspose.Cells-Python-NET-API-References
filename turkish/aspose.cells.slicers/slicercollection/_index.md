---
title: SlicerCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 50
url: /tr/aspose.cells.slicers/slicercollection/
is_root: false
---
##  SlicerCollection sınıfı
Belirtilen çalışma sayfasındaki tüm Slicer nesnelerinin koleksiyonunu belirtir.



SlicerCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.slicers/slicercollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-str) | Veri kaynağı olarak PivotTable'ı kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Veri kaynağı olarak PivotTable'ı kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Veri kaynağı olarak PivotTable'ı kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-int) | Veri kaynağı olarak PivotTable'ı kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Veri kaynağı olarak PivotTable'ı kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Veri kaynağı olarak PivotTable'ı kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, table, index, dest_cell_name)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-int-str) | Veri kaynağı olarak ListObjet'i kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, table, list_column, dest_cell_name)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-str) | Veri kaynağı olarak ListObjet'i kullanarak yeni bir Dilimleyici ekleyin|
| [`add(self, table, list_column, row, column)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-int-int) | Veri kaynağı olarak ListObjet'i kullanarak yeni bir Dilimleyici ekleyin|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/get/#str) | Dilimleyicinin adına göre dilimleyiciyi alır.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.slicers/slicercollection/binary_search/#aspose.cells.slicers.slicer) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
tableIndex = sheet.list_objects.add("A1", "C9", True)
table = sheet.list_objects[tableIndex]
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.slicers`](..)
