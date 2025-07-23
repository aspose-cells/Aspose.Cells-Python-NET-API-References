---
title: ListColumn sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn sınıfı
Tablodaki bir sütunu temsil eder.



ListColumn türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [name](/cells/python-net/tr/aspose.cells.tables/listcolumn/name) | Sütunun adını alır ve ayarlar.|
| [totals_calculation](/cells/python-net/tr/aspose.cells.tables/listcolumn/totals_calculation) | Liste sütununun Toplamlar satırındaki hesaplama türünü alır ve ayarlar.|
| [range](/cells/python-net/tr/aspose.cells.tables/listcolumn/range) | Bu liste sütununun aralığını alır.|
| [is_array_formula](/cells/python-net/tr/aspose.cells.tables/listcolumn/is_array_formula) | Formülün dizi formülü olup olmadığını belirtir.|
| [formula](/cells/python-net/tr/aspose.cells.tables/listcolumn/formula) | Liste sütununun formülünü alır ve ayarlar.|
| [totals_row_label](/cells/python-net/tr/aspose.cells.tables/listcolumn/totals_row_label) | Toplam satırının görüntü etiketlerini alır ve ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | Bu liste sütununun toplamlar satırının formülünü alır.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | Bu liste sütununun toplamlar satırının formülünü alır.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | Bu liste sütununun formülünü alır.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | Bu liste sütunu için formülü ayarlar.|
| [`get_data_style(self)`](/cells/python-net/tr/aspose.cells.tables/listcolumn/get_data_style/#) | Tablonun bu sütunundaki verilerin stilini alır.|
| [`set_data_style(self, style)`](/cells/python-net/tr/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | Tablonun bu sütunundaki verilerin stilini ayarlar.|



###  Örnek

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(4):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
listColumn = table.list_columns[4]
listColumn.totals_calculation = TotalsCalculation.SUM
listColumn.formula = "=[A]"
workbook.save(r"Book1.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.tables`](..)
