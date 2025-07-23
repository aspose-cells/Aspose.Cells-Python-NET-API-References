---
title: RowCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1240
url: /ru/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection класс
Собирает объекты [`Row`](/cells/python-net/ru/aspose.cells/row), представляющие отдельные строки на рабочем листе.



Тип RowCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [count](/cells/python-net/ru/aspose.cells/rowcollection/count) | Получает количество строк в этой коллекции.|



Получает объект [`Row`](/cells/python-net/ru/aspose.cells/row) по указанному индексу строки. Объект Row с указанным индексом строки будет создан, если он ранее не существовал.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] |  |


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/ru/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Получает перечислитель, который перебирает строки в этой коллекции.|
| [`get_row_by_index(self, index)`](/cells/python-net/ru/aspose.cells/rowcollection/get_row_by_index/#int) | Получает объект строки по позиции в списке.|
| [`clear(self)`](/cells/python-net/ru/aspose.cells/rowcollection/clear/#) | Очистить все строки и ячейки.|
| [`remove_at(self, index)`](/cells/python-net/ru/aspose.cells/rowcollection/remove_at/#int) | Удалить элемент строки по указанному индексу (позиции) в этой коллекции.|



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
