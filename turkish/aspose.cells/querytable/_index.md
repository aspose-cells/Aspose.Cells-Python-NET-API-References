---
title: QueryTable sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1230
url: /tr/aspose.cells/querytable/
is_root: false
---
##  QueryTable sınıfı
QueryTable bilgisini temsil eder.



QueryTable türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [connection_id](/cells/python-net/tr/aspose.cells/querytable/connection_id) |Sorgu tablosunun bağlantı kimliğini alır.|
| [external_connection](/cells/python-net/tr/aspose.cells/querytable/external_connection) | İlgili dış bağlantıyı alır.|
| [name](/cells/python-net/tr/aspose.cells/querytable/name) | Querytable'ın adını alır.|
| [result_range](/cells/python-net/tr/aspose.cells/querytable/result_range) | Sonucun aralığını alır.|
| [preserve_formatting](/cells/python-net/tr/aspose.cells/querytable/preserve_formatting) | Nesnenin PreserveFormatting'ini döndürür veya ayarlar.|
| [adjust_column_width](/cells/python-net/tr/aspose.cells/querytable/adjust_column_width) | Nesnenin AdjustColumnWidth değerini döndürür veya ayarlar.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Getting the first query table in the worksheet
qt = worksheet.query_tables[0]
# Getting display address of the query table.
address = qt.result_range.address

```

###  Ayrıca bakınız
* modül [aspose.cells](..)
