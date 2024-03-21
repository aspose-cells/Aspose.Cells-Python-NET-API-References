---
title: preferred_parsers недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 350
url: /ru/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers недвижимость

Получает и задает анализаторы предпочтительных значений для загрузки текстового файла.

###  Примечания

parsers[0] — анализатор будет использоваться для первого столбца в файле текстового шаблона,
parsers[1] — парсер будет использоваться для второго столбца и т. д.
Последний (parsers[parsers.length-1]) будет использоваться для всех остальных столбцов, начиная с parsers.length-1.
Если один элемент имеет значение NULL, соответствующий столбец будет анализироваться анализатором по умолчанию Aspose.Cells.
###  Определение:
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`TxtLoadOptions`](/cells/python-net/ru/aspose.cells/txtloadoptions)
