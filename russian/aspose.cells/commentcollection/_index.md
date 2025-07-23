---
title: CommentCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 270
url: /ru/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection класс
Инкапсулирует коллекцию из [`Comment`](/cells/python-net/ru/aspose.cells/comment) объектов.



Тип CommentCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/commentcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/ru/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Добавляет древовидный комментарий.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/ru/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Добавляет древовидный комментарий.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/ru/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Получает связанные комментарии по индексу строки и столбца.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/ru/aspose.cells/commentcollection/get_threaded_comments/#str) | Получает связанные комментарии по имени ячейки.|
| [`add(self, row, column)`](/cells/python-net/ru/aspose.cells/commentcollection/add/#int-int) | Добавляет комментарий в коллекцию.|
| [`add(self, cell_name)`](/cells/python-net/ru/aspose.cells/commentcollection/add/#str) | Добавляет комментарий в коллекцию.|
| [`get(self, row, column)`](/cells/python-net/ru/aspose.cells/commentcollection/get/#int-int) | Добавьте API for Python через .Net.since this[int, int] не поддерживается|
| [`get(self, index)`](/cells/python-net/ru/aspose.cells/commentcollection/get/#int) | Получает элемент [`Comment`](/cells/python-net/ru/aspose.cells/comment) по указанному индексу.|
| [`get(self, cell_name)`](/cells/python-net/ru/aspose.cells/commentcollection/get/#str) | Получает элемент [`Comment`](/cells/python-net/ru/aspose.cells/comment) в указанной ячейке.|
| [`remove_at(self, cell_name)`](/cells/python-net/ru/aspose.cells/commentcollection/remove_at/#str) | Удаляет комментарий к определенной ячейке.|
| [`remove_at(self, row, column)`](/cells/python-net/ru/aspose.cells/commentcollection/remove_at/#int-int) | Удаляет комментарий к определенной ячейке.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/commentcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Comment`](/cells/python-net/ru/aspose.cells/comment)
