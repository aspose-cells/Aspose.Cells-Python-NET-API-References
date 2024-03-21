---
title: html_note недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 150
url: /ru/aspose.cells/comment/html_note/
is_root: false
---
##  html_note недвижимость

Получает и устанавливает строку HTML, содержащую данные и некоторые форматы в этом комментарии.

###  Примечания

Если это цепочный комментарий, примечание нельзя изменить, иначе MS Excel не сможет обработать его как цепочный комментарий.

###  Пример

```python

comment1.html_note = "<Font Style='FONT-FAMILY: Calibri;FONT-SIZE: 11pt;COLOR: #0000ff;TEXT-ALIGN: left;'>This is a <b>test</b>.</Font>"

```
###  Определение:
```python
@property
def html_note(self):
    ...
@html_note.setter
def html_note(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Comment`](/cells/python-net/ru/aspose.cells/comment)
