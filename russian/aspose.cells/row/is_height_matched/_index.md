---
title: is_height_matched недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 190
url: /ru/aspose.cells/row/is_height_matched/
is_root: false
---
##  is_height_matched недвижимость

Указывает, соответствует ли высота строки текущей настройке шрифта по умолчанию в книге.
Значение true для этого свойства также означает, что высота строки является «автоматической» без специального значения высоты, установленного пользователем.

###  Примечания

Если это свойство имеет значение true, если содержимое в этой строке изменится,
обычно высоту строки необходимо пересчитать (например, [`Worksheet.auto_fit_rows`](/cells/python-net/ru/aspose.cells/worksheet/auto_fit_rows))
чтобы получить тот же результат, что и в MS Excel, когда вы открываете в нем книгу.
###  Определение:
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Row`](/cells/python-net/ru/aspose.cells/row)
