---
title: add_identify метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.pivot/pivotpagefields/add_identify/
is_root: false
---
##  add_identify(self, range_index, page_item_index) {#int-list}
Устанавливает, какую метку элемента в каждом поле страницы использовать для определения диапазона данных.
PageItemIndex.Length должен быть равен PageFieldCount, поэтому сначала добавьте поле страницы.



```python

def add_identify(self, range_index, page_item_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| range_index | int | Индекс диапазона консолидированных данных.|
| page_item_index | list | Индекс элемента страницы в каждом поле страницы.<br/>pageItemIndex[2] = 1 означает второй элемент в третьем поле, используемый для идентификации этого диапазона.<br/> pageItemIndex[1] = -1 означает, что во втором поле нет элемента, который можно использовать для идентификации этого диапазона.<br/> и MS автоматически создаст «пустой» элемент во втором поле для определения этого диапазона.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotPageFields`](/cells/python-net/ru/aspose.cells.pivot/pivotpagefields)
