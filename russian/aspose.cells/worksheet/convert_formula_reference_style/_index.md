---
title: convert_formula_reference_style метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 120
url: /ru/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style {#str-bool-int-int}
Преобразует стиль ссылки формулы.


###  Возврат

Преобразованная формула.


```python
def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула, которую нужно преобразовать.|
| to_r1c1 | bool | В какой стиль ссылки преобразовать формулу.<br/>Если исходная формула имеет ссылочный стиль A1,<br/>тогда это значение должно быть истинным, поэтому формула будет преобразована из ссылочного стиля A1 в R1C1;<br/>Если исходная формула имеет ссылочный стиль R1C1,<br/> тогда это значение должно быть ложным, поэтому формула будет преобразована из стиля ссылки R1C1 в стиль ссылки A1;|
| base_cell_row | int | Индекс строки базовой ячейки.|
| base_cell_column | int | Индекс столбца базовой ячейки.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
