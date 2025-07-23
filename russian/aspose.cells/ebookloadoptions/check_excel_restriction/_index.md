---
title: check_excel_restriction недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 90
url: /ru/aspose.cells/ebookloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction недвижимость

Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.
Например, Excel не позволяет вводить строковое значение длиной более 32К.
При вводе значения длиной более 32 КБ, например Cell.PutValue(string), если это свойство имеет значение true, вы получите исключение.
Если это свойство ложно, мы примем ваше входное строковое значение как значение ячейки, чтобы позже
вы можете вывести полное строковое значение для других форматов файлов, например CSV.
Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,
Не сохраняйте книгу в формате Excel. В противном случае при создании файла Excel может возникнуть непредвиденная ошибка.
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
