---
title: linked_data_sources недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources недвижимость

Указывает источники данных для внешних ссылок, используемых в формулах.

###  Примечания

Например, [`Workbook.update_linked_data_source`](/cells/python-net/ru/aspose.cells/workbook/update_linked_data_source), здесь вы можете указать
источники данных для внешних ссылок, используемых в формулах для расчета, особенно те,
Используется в функции ДВССЫЛ. Для внешних ссылок, используемых в функции ДВССЫЛ,
они не воспринимаются как часть внешних ссылок рабочей книги и не могут быть обновлены
по телефону [`Workbook.update_linked_data_source`](/cells/python-net/ru/aspose.cells/workbook/update_linked_data_source).
Соответствие этих рабочих книг внешним ссылкам определяется по [`Workbook.file_name`](/cells/python-net/ru/aspose.cells/workbook#file_name).
и [`ExternalLink.data_source`](/cells/python-net/ru/aspose.cells/externallink#data_source). Поэтому, пожалуйста, убедитесь, что у [`Workbook.file_name`](/cells/python-net/ru/aspose.cells/workbook#file_name) есть
было указано правильное значение (обычно оно должно совпадать с соответствующим
[`ExternalLink.data_source`](/cells/python-net/ru/aspose.cells/externallink#data_source)) для каждой рабочей книги, чтобы их можно было связать, как и ожидалось.
###  Определение:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions)
