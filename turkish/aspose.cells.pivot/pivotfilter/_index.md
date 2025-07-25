---
title: PivotFilter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells.pivot/pivotfilter/
is_root: false
---
##  PivotFilter sınıfı
PivotFilter Koleksiyonunda PivotFilter'i temsil eder.



PivotFilter türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [use_whole_day](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/use_whole_day) | Filtreleme kriterinde tüm günlerin kullanılıp kullanılmadığını belirtir.|
| [auto_filter](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/auto_filter) | Pivot filtrenin otomatik filtresini alır.|
| [filter_type](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/filter_type) | Pivot filtresinin otomatik filtre türünü alır.|
| [field_index](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/field_index) | Bu pivot filtrenin uygulandığı kaynak alanının indeksini alır.|
| [filter_category](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/filter_category) | Bu filtrenin kategorisini alır.|
| [value1](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/value1) | Etiket pivot filtresinin string value1 değerini alır.|
| [value2](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/value2) | Etiket pivot filtresinin string value2'sini alır.|
| [measure_fld_index](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/measure_fld_index) | Pivot filtrenin ölçüm alanı indeksini alır.|
| [value_field_index](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/value_field_index) | Değer bölgesindeki değer alanının indeksini alır.|
| [measure_cube_field_index](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/measure_cube_field_index) | Ölçü küpü alanının dizinini belirtir.<br/>Bu özellik yalnızca OLAP pivotlarındaki filtreler tarafından kullanılır ve bir değer filtresinin hangi ölçüye uygulanacağını belirtir.|
| [member_property_field_index](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/member_property_field_index) | Pivot filtresinin üye özellik alanı indeksini alır.|
| [name](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/name) | Pivot filtresinin adını alır.|
| [evaluation_order](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/evaluation_order) | Pivot filtrenin Değerlendirme Sırasını alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_top_10_value(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/get_top_10_value/#) | Filtrenin en iyi 10 ayarını alır.|
| [`get_labels(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/get_labels/#) | Başlık filtresinin etiketlerini alır.|
| [`get_number_values(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/get_number_values/#) | Sayı filtresinin değerlerini alır.|
| [`get_date_time_values(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotfilter/get_date_time_values/#) | Sayı filtresinin değerlerini alır.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType

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
# Add top 10 filter
pivot.base_fields[0].filter_top10(0, PivotFilterType.COUNT, False, 2)
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](..)
