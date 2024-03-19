---
title: number_category_type недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 670
url: /ru/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type недвижимость

Представляет тип категории форматирования чисел этой ячейки.

###  Примечания

Когда шаблон форматирования ячейки объединяется с шаблонами условного форматирования,
тогда возвращаемый тип соответствует части, которая используется для текущего значения этой ячейки.
Например, если шаблон форматирования для этой ячейки — «#,##0;(#,##0);»-»;@»,
затем, когда значение ячейки является числовым, а не 0, возвращаемый тип — [`NumberCategoryType.NUMBER`](/cells/python-net/ru/aspose.cells/numbercategorytype#NUMBER);
Если значение ячейки равно 0 или не является числовым значением, возвращаемый тип — [`NumberCategoryType.TEXT`](/cells/python-net/ru/aspose.cells/numbercategorytype#TEXT).
###  Определение:
```python
@property
def number_category_type(self):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
* класс [`NumberCategoryType`](/cells/python-net/ru/aspose.cells/numbercategorytype)
