---
title: export_object метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/iexportobjectlistener/export_object/
is_root: false
---
##  export_object(e) {#ExportObjectEvent}
Экспорт одного объекта.


###  Возвращает

Информация о результате экспорта объекта.

* Для экспорта объектов при экспорте книги в формат HTML,
результатом является строка URL для доступа к сохраненному изображению из файла html, который содержит этот экспортированный объект.


```python
def export_object(self, e):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| e | [ExportObjectEvent](/cells/python-net/ru/aspose.cells/exportobjectevent) | Событие срабатывает, когда необходимо экспортировать один объект.|



###  Смотрите также
* модуль [aspose.cells](../../)
* класс [IExportObjectListener](/cells/python-net/ru/aspose.cells/iexportobjectlistener)
