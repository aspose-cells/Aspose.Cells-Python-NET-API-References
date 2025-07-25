---
title: AutoFilter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter sınıfı
Belirtilen çalışma sayfası için otomatik filtrelemeyi temsil eder.



AutoFilter türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [sorter](/cells/python-net/tr/aspose.cells/autofilter/sorter) | Veri sıralayıcısını alır.|
| [range](/cells/python-net/tr/aspose.cells/autofilter/range) | Belirtilen Otomatik Filtrenin uygulanacağı aralığı temsil eder.|
| [show_filter_button](/cells/python-net/tr/aspose.cells/autofilter/show_filter_button) | Bu sütun için Otomatik Filtre düğmesinin görünür olup olmadığını belirtir.|
| [filter_columns](/cells/python-net/tr/aspose.cells/autofilter/filter_columns) | Filtre sütunlarının koleksiyonunu alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/tr/aspose.cells/autofilter/get_cell_area/#) | Bu Otomatik Filtrenin uygulandığı [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea)'i alır.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/tr/aspose.cells/autofilter/get_cell_area/#bool) | Belirtilen Otomatik Filtrenin uygulandığı [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea)'i alır.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/tr/aspose.cells/autofilter/remove_filter/#int-str) | Bir filtre sütunu için filtreyi kaldırır.|
| [`remove_filter(self, field_index)`](/cells/python-net/tr/aspose.cells/autofilter/remove_filter/#int) | Belirli filtreyi kaldırın.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/tr/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Özel bir kritere göre listeyi filtreler.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/tr/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Özel ölçütlere göre bir listeyi filtreler.|
| [`refresh(self)`](/cells/python-net/tr/aspose.cells/autofilter/refresh/#) | Satırları gizlemek veya göstermek için otomatik filtreleri yenileyin.|
| [`refresh(self, hide_rows)`](/cells/python-net/tr/aspose.cells/autofilter/refresh/#bool) | Tüm gizli satırların indekslerini alır.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/tr/aspose.cells/autofilter/set_range/#int-int-int) | Belirtilen Otomatik Filtrenin uygulanacağı aralığı ayarlar.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/tr/aspose.cells/autofilter/add_filter/#int-str) | Bir filtre sütunu için filtre ekler.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/tr/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Tarih filtresi ekler.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/tr/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Tarih filtresini kaldırır.|
| [`filter(self, field_index, criteria)`](/cells/python-net/tr/aspose.cells/autofilter/filter/#int-str) | Belirtilen kriterlere göre listeyi filtreler.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/tr/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Listedeki ilk 10 öğeyi filtrele|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/tr/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Dinamik filtre ekler.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/tr/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Yazı tipi rengi filtresi ekler.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/tr/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Dolgu rengi filtresi ekler.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/tr/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Bir simge filtresi ekler.|
| [`match_blanks(self, field_index)`](/cells/python-net/tr/aspose.cells/autofilter/match_blanks/#int) | Listedeki tüm boş hücreleri eşleştir.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/tr/aspose.cells/autofilter/match_non_blanks/#int) | Listedeki boş olmayan tüm hücreleri eşleştir.|
| [`show_all(self)`](/cells/python-net/tr/aspose.cells/autofilter/show_all/#) | Tüm satırları göster.|



###  Örnek

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea)
