---
title: Sparkline класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 270
url: /ru/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline класс
Спарклайн представляет собой небольшую диаграмму или график в ячейке рабочего листа, который обеспечивает визуальное представление данных.



Тип Sparkline предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [data_range](/cells/python-net/ru/aspose.cells.charts/sparkline/data_range) | Представляет диапазон данных спарклайна.|
| [row](/cells/python-net/ru/aspose.cells.charts/sparkline/row) | Получает индекс строки спарклайна.|
| [column](/cells/python-net/ru/aspose.cells.charts/sparkline/column) | Получает индекс столбца спарклайна.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/ru/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Преобразует спарклайн в изображение.|
| [`to_image(self, stream, options)`](/cells/python-net/ru/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Преобразует спарклайн в изображение.|



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
idx = sheet.sparkline_groups.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
idx = group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
line = group.sparklines[idx]
print("Saprkline data range: "  + line.data_range + ", row: "  + str(line.row) + ", column: "  + str(line.column))
line.to_image("output.png", ImageOrPrintOptions())

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
