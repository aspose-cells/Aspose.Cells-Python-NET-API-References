---
title: RowCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1350
url: /ru/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection класс
Собирает объекты [`Row`](/cells/python-net/ru/aspose.cells/row), представляющие отдельные строки на листе.



Тип RowCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [count](/cells/python-net/ru/aspose.cells/rowcollection/count) | Получает количество строк в этой коллекции.|



Получает объект [`Row`](/cells/python-net/ru/aspose.cells/row) по заданному индексу строки. Будет создан экземпляр объекта Row с заданным индексом строки, если он не существовал ранее.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] |  |


###  Методы
| Метод| Описание|
| :- | :- |
| [get_enumerator](/cells/python-net/ru/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Получает перечислитель, который перебирает строки в этой коллекции.|
| [get_row_by_index](/cells/python-net/ru/aspose.cells/rowcollection/get_row_by_index/#int) | Получает объект строки по позиции в списке.|
| [clear](/cells/python-net/ru/aspose.cells/rowcollection/clear/#) | Очистите все строки и ячейки.|
| [remove_at](/cells/python-net/ru/aspose.cells/rowcollection/remove_at/#int) | Удалите элемент строки по указанному индексу (позиции) в этой коллекции.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Row`](/cells/python-net/ru/aspose.cells/row)
