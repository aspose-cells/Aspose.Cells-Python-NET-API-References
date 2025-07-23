---
title: number_category_type недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 700
url: /ru/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type недвижимость

Представляет тип категории числового форматирования этой ячейки.

###  Примечания

Когда шаблон форматирования ячейки комбинируется с шаблонами условного форматирования,
то возвращаемый тип соответствует той части, которая используется для текущего значения этой ячейки.
Например, если шаблон форматирования для этой ячейки — «#,##0;(#,##0);»-«;@»,
тогда когда значение ячейки числовое и не равно 0, возвращаемый тип — [`NumberCategoryType.NUMBER`](/cells/python-net/ru/aspose.cells/numbercategorytype#NUMBER);
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
