---
title: ungroup метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 500
url: /ru/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
Разгруппировывает элементы фигуры.



```python

def ungroup(self, group):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/ru/aspose.cells.drawing/groupshape) | Форма группы.|
###  Примечания

Если групповая фигура сгруппирована с другой групповой фигурой, ничего не произойдет.
###  Пример


```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# group
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)
# ungroup
shapes.ungroup(groupShape)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
