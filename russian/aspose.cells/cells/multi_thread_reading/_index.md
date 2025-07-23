---
title: multi_thread_reading недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1220
url: /ru/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading недвижимость

Возвращает или задает, должна ли модель данных ячеек поддерживать многопоточное чтение.
Значение этого свойства по умолчанию — false.

###  Примечания

Если в этой коллекции есть несколько потоков для одновременного чтения объектов Row/Cell,
это свойство должно быть установлено как true, в противном случае может быть получен неожиданный результат.
Поддержка многопоточного чтения может снизить производительность доступа к объектам Row/Cell из этой коллекции.
Обратите внимание, что некоторые функции не поддерживают многопоточное чтение.
такие как форматирование значений (по [`Cell.string_value`](/cells/python-net/ru/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/ru/aspose.cells/cell#display_string_value) и т. д.).
Таким образом, даже если это свойство установлено как true, эти API все равно могут выдавать неожиданный результат для многопоточного чтения.
###  Определение:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
