---
title: multi_thread_reading недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1190
url: /ru/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading недвижимость

Получает или задает, должна ли модель данных ячеек поддерживать многопоточное чтение.
Значение этого свойства по умолчанию — false.

###  Примечания

Если существует несколько потоков для одновременного чтения объектов Row/Cell в этой коллекции,
это свойство должно быть установлено как true, в противном случае может быть получен неожиданный результат.
Поддержка многопоточного чтения может снизить производительность доступа к объектам Row/Cell из этой коллекции.
Обратите внимание: некоторые функции не поддерживают многопоточное чтение.
например значения форматирования (по [`Cell.string_value`](/cells/python-net/ru/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/ru/aspose.cells/cell#display_string_value) и т. д.).
Таким образом, даже если для этого свойства установлено значение true, эти API все равно могут давать неожиданный результат при многопоточном чтении.
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
