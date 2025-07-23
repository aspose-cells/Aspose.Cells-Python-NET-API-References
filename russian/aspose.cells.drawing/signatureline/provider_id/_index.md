---
title: provider_id недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells.drawing/signatureline/provider_id/
is_root: false
---
##  provider_id недвижимость

Получает или задает идентификатор поставщика подписи.

###  Примечания

Обычно это CLSID надстройки com-провайдера.

###  Пример

```python
from aspose.cells.drawing import SignatureLine
from uuid import uuid4

#  Create signature line object
s2 = SignatureLine()
s2.provider_id = uuid4("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx")

```
###  Определение:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`SignatureLine`](/cells/python-net/ru/aspose.cells.drawing/signatureline)
