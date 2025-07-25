---
title: copy_comments_in_range метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 400
url: /ru/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
Скопировать все комментарии в диапазоне.



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection) | Источник формирует.|
| ca | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Исходный диапазон.|
| dest_row | int | Начальная строка диапазона назначения.|
| dest_column | int | Начальный столбец диапазона назначения.|

###  Пример

```python
from aspose.cells import CellArea

comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex = comments.add(0, 0)
comment = comments[commentIndex]
comment.note = "First note."
comment.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment = comments.get("B2")
comment.note = "Second note."
area1 = CellArea()
area1.start_column = 1
area1.start_row = 1
area1.end_column = 5
area1.end_row = 4
# copy
shapes.copy_comments_in_range(shapes, area1, 5, 1)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
