---
title: clear метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Удаляет все внешние ссылки.



```python

def clear(self):
    ...
```


###  Примечания

При удалении внешних ссылок все формулы, ссылающиеся на них, также будут удалены, потому что
ссылки становятся недействительными.

##  clear(self, update_references_as_local) {#bool}
Удаляет все внешние ссылки.



```python

def clear(self, update_references_as_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| update_references_as_local | bool |Обновлять ли все ссылки внешних ссылок в формулах на ссылки самой текущей книги.|
###  Примечания

Если требуется обновить ссылки, то необходимо обновить ссылки на внешние ссылки в формулах.
будет изменен на текущую рабочую книгу, когда это станет возможным.
Например, исходная формула одной ячейки: «='externalsource.xlam'!customfunction()»,
после удаления внешних ссылок формула примет вид "=customfunction()";
Если исходная формула — «='[externalsource.xlam]Sheet1'!$A$1»,
в зависимости от того, есть ли в текущей книге лист с именем «Лист1»:
если true, формула примет вид "=Sheet1!$A$1";
если ложно, формула примет вид «=#REF!$A$1».

Если ссылки не требуют обновления, все формулы со ссылками на внешние ссылки
будут также удалены, поскольку эти ссылки станут недействительными.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`ExternalLinkCollection`](/cells/python-net/ru/aspose.cells/externallinkcollection)
