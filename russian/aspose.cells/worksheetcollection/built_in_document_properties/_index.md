---
title: built_in_document_properties недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 280
url: /ru/aspose.cells/worksheetcollection/built_in_document_properties/
is_root: false
---
##  built_in_document_properties недвижимость

Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.

###  Примечания

Добавить новое свойство в список встроенных свойств документа невозможно. Можно только получить встроенное свойство и изменить его значение.
Ниже приведен список имен встроенных свойств:

Заголовок


Предмет


Автор


Ключевые слова


Комментарии


Шаблон


Последний автор


Номер редакции


Имя приложения


Дата последней печати


Дата создания


Время последнего сохранения


Общее время редактирования


Количество страниц


Количество слов


Количество символов


Безопасность


Категория


Формат


Менеджер


Компания


Количество байтов


Количество строк


Количество абзацев


Количество слайдов


Количество нот


Количество скрытых слайдов


Количество мультимедийных клипов

###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.worksheets.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Определение:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`BuiltInDocumentPropertyCollection`](/cells/python-net/ru/aspose.cells.properties/builtindocumentpropertycollection)
* класс [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
