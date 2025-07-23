---
title: group метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 460
url: /ru/aspose.cells.drawing/shapecollection/group/
is_root: false
---
##  group(self, group_items) {#list}
Сгруппируйте фигуры.


###  Возврат

Верните форму group.


```python

def group(self, group_items):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| group_items | list | групповые элементы.|
###  Примечания

Фигура в groupItems не должна быть сгруппирована.
Фигура должна быть в этой коллекции Фигур.
###  Пример

```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
