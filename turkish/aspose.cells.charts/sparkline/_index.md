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
Kıvılcım çizgisi, bir çalışma sayfası hücresinde verilerin görsel bir temsilini sağlayan küçük bir çizelge veya grafiği temsil eder.



Sparkline türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [data_range](/cells/python-net/tr/aspose.cells.charts/sparkline/data_range) | Kıvılcım çizgisinin veri aralığını temsil eder.|
| [row](/cells/python-net/tr/aspose.cells.charts/sparkline/row) | Kıvılcım çizgisinin satır dizinini alır.|
| [column](/cells/python-net/tr/aspose.cells.charts/sparkline/column) | Kıvılcım çizgisinin sütun dizinini alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/tr/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Kıvılcım çizgisini görüntüye dönüştürür.|
| [`to_image(self, stream, options)`](/cells/python-net/tr/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Kıvılcım çizgisini görüntüye dönüştürür.|



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
idx = sheet.sparkline_groups.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
idx = group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
line = group.sparklines[idx]
print("Saprkline data range: "  + line.data_range + ", row: "  + str(line.row) + ", column: "  + str(line.column))
line.to_image("output.png", ImageOrPrintOptions())

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
