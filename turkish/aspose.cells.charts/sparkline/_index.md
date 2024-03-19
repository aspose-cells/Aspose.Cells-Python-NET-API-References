---
title: Sparkline sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 270
url: /tr/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline sınıfı
Mini grafik, bir çalışma sayfası hücresindeki verilerin görsel temsilini sağlayan küçük bir grafiği veya grafiği temsil eder.



Sparkline türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [data_range](/cells/python-net/tr/aspose.cells.charts/sparkline/data_range) | Mini grafik veri aralığını temsil eder.|
| [row](/cells/python-net/tr/aspose.cells.charts/sparkline/row) | Sparkline'ın satır indeksini alır.|
| [column](/cells/python-net/tr/aspose.cells.charts/sparkline/column) | Mini grafik sütununun indeksini alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [to_image](/cells/python-net/tr/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.ImageOrPrintOptions) | Mini grafikleri görsele dönüştürür.|
| [to_image](/cells/python-net/tr/aspose.cells.charts/sparkline/to_image/#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions) | Mini grafikleri görsele dönüştürür.|



###  Örnek

```python
from aspose.cells import CellArea, Workbook
from aspose.cells.charts import SparklineType
from aspose.cells.rendering import ImageOrPrintOptions

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
idx = sheet.sparkline_group_collection.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_group_collection[idx]
idx = group.sparkline_collection.add(sheet.name + "!A1:D1", 0, 4)
line = group.sparkline_collection[idx]
print("Saprkline data range: "  + line.data_range + ", row: "  + str(line.row) + ", column: "  + str(line.column))
line.to_image("output.png", ImageOrPrintOptions())

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
