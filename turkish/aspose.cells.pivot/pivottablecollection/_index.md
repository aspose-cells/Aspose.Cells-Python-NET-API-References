---
title: PivotTableCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 250
url: /tr/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection sınıfı
Belirtilen çalışma sayfasındaki tüm PivotTable nesnelerinin koleksiyonunu temsil eder.



PivotTableCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | Yeni bir PivotTable ekler.|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | Yeni bir PivotTable ekler.|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | Yeni bir PivotTable ekler.|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | Yeni bir PivotTable ekler.|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) | Yeni bir PivotTable ekler.|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) | Yeni bir PivotTable ekler.|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) | Başka bir PivotTable'a dayalı yeni bir PivotTable ekler.|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Başka bir PivotTable'a dayalı yeni bir PivotTable ekler.|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) | Veri kaynağı olarak birden fazla birleştirme aralığına sahip yeni bir PivotTable Nesnesi koleksiyona ekler.|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) | Veri kaynağı olarak birden fazla birleştirme aralığına sahip yeni bir PivotTable Nesnesi koleksiyona ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/get/#str) | PivotTable raporunu pivottable adına göre alır.|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) | Belirtilen PivotTable'ı siler ve PivotTable verilerini siler|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) | Belirtilen PivotTable'ı siler|
| [`remove_by_index(self, index)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) | Belirtilen dizindeki PivotTable'ı siler ve PivotTable verilerini siler|
| [`remove_at(self, index, keep_data)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | Belirtilen dizindeki PivotTable'ı siler|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

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
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](..)
