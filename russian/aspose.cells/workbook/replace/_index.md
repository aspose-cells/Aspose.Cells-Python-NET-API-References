---
title: replace метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 350
url: /ru/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Заменяет значение ячейки новой строкой.



```python

def replace(self, place_holder, new_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_value | str | Строковое значение для замены|

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Заменяет значение ячейки новым целым числом.



```python

def replace(self, place_holder, new_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_value | int | Целое значение для замены|

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Заменяет значение ячейки новым числом двойной точности.



```python

def replace(self, place_holder, new_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_value | float | Двойное значение для замены|

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Заменяет значения ячеек новыми данными.



```python

def replace(self, bool_value, new_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| bool_value | bool | Булевое значение, которое необходимо заменить.|
| new_value | any | Новое значение. Может быть строкой, целым числом, числом двойной точности или значением типа DateTime.|


##  replace(self, int_value, new_value) {#int-any}
Заменяет значения ячеек новыми данными.



```python

def replace(self, int_value, new_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| int_value | int | Целочисленное значение, которое необходимо заменить.|
| new_value | any | Новое значение. Может быть строкой, целым числом, числом двойной точности или значением типа DateTime.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Заменяет значение ячейки новым строковым массивом.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_values | list | Массив строк для замены|
| is_vertical | bool | True - Вертикально, False - Горизонтально|

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Заменяет значения ячеек целочисленным массивом.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_values | list | Целочисленный массив для замены|
| is_vertical | bool | True - Вертикально, False - Горизонтально|

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Заменяет значения ячеек двойным массивом.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_values | list | Двойной массив для замены|
| is_vertical | bool | True - Вертикально, False - Горизонтально|

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Заменяет значение ячейки новой строкой.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| place_holder | str | Cell заполнитель|
| new_value | str | Строковое значение для замены|
| options | [`ReplaceOptions`](/cells/python-net/ru/aspose.cells/replaceoptions) | Варианты замены|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
