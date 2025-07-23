---
title: get_style_in_pool метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 200
url: /ru/aspose.cells/workbook/get_style_in_pool/
is_root: false
---
##  get_style_in_pool(self, index) {#int}
Получает стиль из пула стилей.
Все стили в рабочей книге будут объединены в пул.
В ячейках имеется только простой справочный индекс.


###  Возврат

Стиль в пуле соответствует указанному индексу, может быть нулевым.


```python

def get_style_in_pool(self, index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int | Индекс.|
###  Примечания

Если возвращаемый стиль изменен, стиль всех ячеек (которые ссылаются на этот стиль) также будет изменен.


###  Смотрите также

* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
