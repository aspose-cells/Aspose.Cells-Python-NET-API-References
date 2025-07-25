---
title: get_value метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/referredarea/get_value/
is_root: false
---
##  get_value(self, row_offset, col_offset) {#int-int}
Получает значение ячейки с заданным смещением от верхнего левого угла этой области.


###  Возврат

"#РЕФ!" если эта область недействительна;
«#Н/Д», если указано смещение за пределы этой области;
В противном случае верните значение ячейки в заданной позиции.


```python

def get_value(self, row_offset, col_offset):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_offset | int | смещение строки от начальной строки этой области|
| col_offset | int | смещение столбца от начальной строки этой области|


##  get_value(self, row_offset, col_offset, calculate_formulas) {#int-int-bool}
Получает значение ячейки с заданным смещением от верхнего левого угла этой области.


###  Возврат

"#РЕФ!" если эта область недействительна;
«#Н/Д», если указано смещение за пределы этой области;
В противном случае верните значение ячейки в заданной позиции.


```python

def get_value(self, row_offset, col_offset, calculate_formulas):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_offset | int | смещение строки от начальной строки этой области|
| col_offset | int | смещение столбца от начальной строки этой области|
| calculate_formulas | bool | Вычислить ли его рекурсивно, если указанная ссылка является формулой|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`ReferredArea`](/cells/python-net/ru/aspose.cells/referredarea)
