---
title: convert_formula_reference_style метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 120
url: /ru/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column) {#str-bool-int-int}
Преобразует стиль ссылки формулы.


###  Возврат

Преобразованная формула.


```python

def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула, которую необходимо преобразовать.|
| to_r1c1 | bool | В какой стиль ссылки преобразовать формулу.<br/>Если исходная формула имеет формат ссылки A1,<br/>то это значение должно быть истинным, поэтому формула будет преобразована из стиля ссылки A1 в стиль ссылки R1C1;<br/>Если исходная формула имеет стиль ссылки R1C1,<br/> то это значение должно быть false, поэтому формула будет преобразована из стиля ссылок R1C1 в стиль ссылок A1;|
| base_cell_row | int | Индекс строки базовой ячейки.|
| base_cell_column | int | Индекс столбца базовой ячейки.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
