---
title: CommentCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 300
url: /ru/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection класс
Инкапсулирует коллекцию из [`Comment`](/cells/python-net/ru/aspose.cells/comment) объектов.



Тип CommentCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/commentcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add_threaded_comment](/cells/python-net/ru/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | Добавляет цепочный комментарий.|
| [add_threaded_comment](/cells/python-net/ru/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | Добавляет цепочный комментарий.|
| [get_threaded_comments](/cells/python-net/ru/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Получает цепочки комментариев по индексу строки и столбца.|
| [get_threaded_comments](/cells/python-net/ru/aspose.cells/commentcollection/get_threaded_comments/#str) |Получает цепочки комментариев по имени ячейки.|
| [add](/cells/python-net/ru/aspose.cells/commentcollection/add/#int-int) | Добавляет комментарий в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/commentcollection/add/#str) | Добавляет комментарий в коллекцию.|
| [remove_at](/cells/python-net/ru/aspose.cells/commentcollection/remove_at/#str) | Удаляет комментарий конкретной ячейки.|
| [remove_at](/cells/python-net/ru/aspose.cells/commentcollection/remove_at/#int-int) | Удаляет комментарий конкретной ячейки.|
| [copy_to](/cells/python-net/ru/aspose.cells/commentcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [binary_search](/cells/python-net/ru/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Comment`](/cells/python-net/ru/aspose.cells/comment)
