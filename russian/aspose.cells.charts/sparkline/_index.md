---
title: Sparkline класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 260
url: /ru/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline класс
Спарклайн представляет собой крошечную диаграмму или графику в ячейке рабочего листа, которая обеспечивает визуальное представление данных.



Тип Sparkline предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [data_range](/cells/python-net/ru/aspose.cells.charts/sparkline/data_range) | Представляет диапазон данных спарклайна.|
| [row](/cells/python-net/ru/aspose.cells.charts/sparkline/row) | Получает индекс строки спарклайна.|
| [column](/cells/python-net/ru/aspose.cells.charts/sparkline/column) | Получает индекс столбца спарклайна.|


###  Методы
| Метод| Описание|
| :- | :- |
| [to_image(file_name, options)](/cells/python-net/ru/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.ImageOrPrintOptions) | Преобразует спарклайн в изображение.|
| [to_image(stream, options)](/cells/python-net/ru/aspose.cells.charts/sparkline/to_image/#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions) | Преобразует спарклайн в изображение.|



###  Пример

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

###  Смотрите также
* модуль [aspose.cells.charts](..)
