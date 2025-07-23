---
title: remove_at метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Удаляет указанную внешнюю ссылку из книги.



```python

def remove_at(self, index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int | индекс внешней ссылки, подлежащей удалению.|
###  Примечания

При удалении внешней ссылки все формулы, ссылающиеся на нее, также будут удалены, потому что
ссылки становятся недействительными.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Удаляет указанную внешнюю ссылку из книги.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int | индекс внешней ссылки, подлежащей удалению.|
| update_references_as_local | bool | Обновлять ли все ссылки заданной внешней ссылки на ссылку самой текущей рабочей книги.<br/> Более подробную информацию об этом параметре можно получить по номеру [`ExternalLinkCollection.clear`](/cells/python-net/ru/aspose.cells/externallinkcollection/clear).|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`ExternalLinkCollection`](/cells/python-net/ru/aspose.cells/externallinkcollection)
