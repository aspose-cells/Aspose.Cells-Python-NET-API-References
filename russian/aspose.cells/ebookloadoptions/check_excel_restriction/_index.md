---
title: check_excel_restriction недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 90
url: /ru/aspose.cells/ebookloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction недвижимость

Проверьте, ограничено ли использование файла Excel при изменении пользователем объектов, связанных с ячейками.
Например, Excel не позволяет вводить строковое значение длиной более 32 КБ.
Когда вы вводите значение длиной более 32 КБ, например Cell.PutValue(string), если это свойство истинно, вы получите исключение.
Если это свойство имеет значение false, мы примем значение входной строки в качестве значения ячейки, чтобы позже
вы можете вывести полное строковое значение для файлов других форматов, например CSV.
Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,
вам не следует сохранять книгу в формате файла Excel позже. В противном случае в созданном файле Excel может возникнуть непредвиденная ошибка.
###  Определение:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`EbookLoadOptions`](/cells/python-net/ru/aspose.cells/ebookloadoptions)
