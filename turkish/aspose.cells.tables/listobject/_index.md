---
title: ListObject sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject sınıfı
Çalışma sayfasındaki bir liste nesnesini temsil eder.
 ListObject nesnesi ListObjects koleksiyonunun bir üyesidir.
ListObjects koleksiyonu, bir çalışma sayfasındaki tüm liste nesnelerini içerir.



ListObject türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [start_row](/cells/python-net/tr/aspose.cells.tables/listobject/start_row) | Aralığın başlangıç satırını alır.|
| [start_column](/cells/python-net/tr/aspose.cells.tables/listobject/start_column) | Aralığın başlangıç sütununu alır.|
| [end_row](/cells/python-net/tr/aspose.cells.tables/listobject/end_row) | Aralığın son satırını alır.|
| [end_column](/cells/python-net/tr/aspose.cells.tables/listobject/end_column) | Aralığın son sütununu alır.|
| [list_columns](/cells/python-net/tr/aspose.cells.tables/listobject/list_columns) | ListObject'in ListColumns'unu alır.|
| [show_header_row](/cells/python-net/tr/aspose.cells.tables/listobject/show_header_row) | Bu ListObject'in başlık satırını gösterip göstermeyeceğini alır ve ayarlar.|
| [show_totals](/cells/python-net/tr/aspose.cells.tables/listobject/show_totals) | Bu ListObject'in toplam satırını gösterip göstermediğini alır ve ayarlar.|
| [data_range](/cells/python-net/tr/aspose.cells.tables/listobject/data_range) | ListObject'in veri aralığını alır.|
| [query_table](/cells/python-net/tr/aspose.cells.tables/listobject/query_table) | Bağlantılı QueryTable'ı alır.|
| [data_source_type](/cells/python-net/tr/aspose.cells.tables/listobject/data_source_type) |Tablonun veri kaynağı türünü alır.|
| [auto_filter](/cells/python-net/tr/aspose.cells.tables/listobject/auto_filter) | Otomatik filtre alır.|
| [display_name](/cells/python-net/tr/aspose.cells.tables/listobject/display_name) | Görüntülenen adı alır ve ayarlar.|
| [comment](/cells/python-net/tr/aspose.cells.tables/listobject/comment) | Tablonun yorumunu alır ve ayarlar.|
| [show_table_style_first_column](/cells/python-net/tr/aspose.cells.tables/listobject/show_table_style_first_column) | Tablodaki ilk sütuna stilin uygulanıp uygulanmayacağını belirtir.|
| [show_table_style_last_column](/cells/python-net/tr/aspose.cells.tables/listobject/show_table_style_last_column) | Tablodaki son sütuna stilin uygulanıp uygulanmayacağını belirtir.|
| [show_table_style_row_stripes](/cells/python-net/tr/aspose.cells.tables/listobject/show_table_style_row_stripes) | Satır şerit biçimlendirmesinin uygulanıp uygulanmadığını belirtir.|
| [show_table_style_column_stripes](/cells/python-net/tr/aspose.cells.tables/listobject/show_table_style_column_stripes) | Sütun şerit biçimlendirmesinin uygulanıp uygulanmadığını belirtir.|
| [table_style_type](/cells/python-net/tr/aspose.cells.tables/listobject/table_style_type) | Alır ve yerleşik tablo stili.|
| [table_style_name](/cells/python-net/tr/aspose.cells.tables/listobject/table_style_name) | Tablo stili adını alır ve ayarlar.|
| [xml_map](/cells/python-net/tr/aspose.cells.tables/listobject/xml_map) | Bu liste için [`ListObject.xml_map`](/cells/python-net/tr/aspose.cells.tables/listobject#xml_map) kullanılır.|
| [alternative_text](/cells/python-net/tr/aspose.cells.tables/listobject/alternative_text) | Alternatif metni alır ve ayarlar.|
| [alternative_description](/cells/python-net/tr/aspose.cells.tables/listobject/alternative_description) | Alternatif açıklamayı alır ve ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/tr/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Değeri hücreye koy.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/tr/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Değeri hücreye koy.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/tr/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Formülü tablodaki hücreye koyun.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/tr/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Formülü tablodaki hücreye koyun.|
| [`convert_to_range(self)`](/cells/python-net/tr/aspose.cells.tables/listobject/convert_to_range/#) | Tabloyu aralığa dönüştür.|
| [`convert_to_range(self, options)`](/cells/python-net/tr/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Tabloyu aralığa dönüştür.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/tr/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Liste nesnesinin aralığını yeniden boyutlandırın.|
| [`update_column_name(self)`](/cells/python-net/tr/aspose.cells.tables/listobject/update_column_name/#) | Çalışma sayfasındaki tüm liste sütunlarının adını günceller.|
| [`filter(self)`](/cells/python-net/tr/aspose.cells.tables/listobject/filter/#) | Tabloyu filtreleyin.|
| [`apply_style_to_range(self)`](/cells/python-net/tr/aspose.cells.tables/listobject/apply_style_to_range/#) | Tablo stilini aralığa uygulayın.|



###  Örnek

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.tables`](..)
