---
title: delete_shape метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 440
url: /ru/aspose.cells.drawing/shapecollection/delete_shape/
is_root: false
---
##  delete_shape(self, shape) {#aspose.cells.drawing.Shape}
Удалить фигуру. Если фигура входит в группу или является комментарием, она не будет удалена.



```python

def delete_shape(self, shape):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| shape | [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape) |  |

###  Пример

```python

# add first shape
firstShape = shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
secondShape = shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# del
shapes.delete_shape(firstShape)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
