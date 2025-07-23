---
title: is_locked недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 650
url: /ru/aspose.cells.drawing/radiobutton/is_locked/
is_root: false
---
##  is_locked недвижимость

 True означает, что объект не может быть изменен, если лист защищен.
Обратите внимание, что это значение имеет смысл только в том случае, если рабочий лист или объекты на нем защищены.

###  Пример

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  Определение:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`RadioButton`](/cells/python-net/ru/aspose.cells.drawing/radiobutton)
