---
title: create_safe_sheet_name метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 90
url: /ru/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, name_proposal){#str}
Проверяет указанное имя листа и при необходимости создает допустимое.
Если заданное имя листа соответствует правилам именования листов Excel, то вернуть его.
В противном случае строка будет обрезана, если длина превысит лимит.
и недопустимые символы будут заменены на « », а затем вернется восстановленное строковое значение.


###  Возврат




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| name_proposal | str | имя листа, которое будет использоваться|


##  create_safe_sheet_name(, name_proposal, replace_char){#str-char}
Проверяет указанное имя листа и при необходимости создает допустимое.
Если заданное имя листа соответствует правилам именования листов Excel, то вернуть его.
В противном случае строка будет обрезана, если длина превысит лимит.
и недопустимые символы будут заменены заданным символом, а затем вернется восстановленное строковое значение.


###  Возврат




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| name_proposal | str | имя листа, которое будет использоваться|
| replace_char | char | символ, который будет использоваться для замены недопустимых символов в заданном имени листа|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CellsHelper`](/cells/python-net/ru/aspose.cells/cellshelper)
