---
title: auto_size недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells/comment/auto_size/
is_root: false
---
##  auto_size недвижимость

Указывает, регулируется ли размер комментария автоматически в соответствии с его содержанием.
Примечание: В некоторых особых случаях (например, в среде Mac) этот параметр может не действовать. Если этот параметр не действует, замените его на FitToTextSize().

###  Пример

```python

if notcomment1.auto_size:
    # The size of the comment varies with the content
    comment1.auto_size = True

```
###  Определение:
```python
@property
def auto_size(self):
    ...
@auto_size.setter
def auto_size(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Comment`](/cells/python-net/ru/aspose.cells/comment)
