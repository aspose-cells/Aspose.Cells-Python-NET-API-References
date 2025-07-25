---
title: Sparkline类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells.charts/sparkline/
is_root: false
---
## Sparkline类
迷你图表示工作表单元格中的微型图表或图形，可以直观地表示数据。



Sparkline 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [data_range](/cells/python-net/zh/aspose.cells.charts/sparkline/data_range) |表示迷你图的数据范围。|
| [row](/cells/python-net/zh/aspose.cells.charts/sparkline/row) |获取迷你图的行索引。|
| [column](/cells/python-net/zh/aspose.cells.charts/sparkline/column) |获取迷你图的列索引。|


### 方法
|方法|描述|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/zh/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) |将迷你图转换为图像。|
| [`to_image(self, stream, options)`](/cells/python-net/zh/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) |将迷你图转换为图像。|



### 例子

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

### 也可以看看
* 模块[`aspose.cells.charts`](..)
