---
title: delete_blank_rows метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 210
url: /ru/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Удалите все пустые строки, не содержащие никаких данных или других объектов.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Удалите все пустые строки, которые не содержат никаких данных или специальных объектов, таких как видимые комментарии, сводная таблица.



```python

def delete_blank_rows(self, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/ru/aspose.cells/deleteoptions) | Варианты удаления диапазона.|
###  Примечания

Для пустых строк, которые будут удалены, требуется не только, чтобы значение [`Row.is_blank`](/cells/python-net/ru/aspose.cells/row#is_blank) было истинным,
но также не должно быть никаких видимых комментариев, определенных для любой ячейки в этих строках,
и нет сводной таблицы, диапазон которой пересекается с ними.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
