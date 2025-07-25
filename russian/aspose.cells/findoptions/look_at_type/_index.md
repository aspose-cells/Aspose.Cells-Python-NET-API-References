---
title: look_at_type недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 90
url: /ru/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type недвижимость

Посмотрите на тип.

###  Примечания

Когда [`FindOptions.regex_key`](/cells/python-net/ru/aspose.cells/findoptions#regex_key) имеет значение true и пользователь указал точное правило для регулярного выражения,
Из соображений производительности это свойство следует установить как [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/ru/aspose.cells/lookattype#ENTIRE_CONTENT).
В противном случае мы изменим ключ поиска, чтобы обеспечить его соответствие определенному типу.
Например, если тип равен [`LookAtType.CONTAINS`](/cells/python-net/ru/aspose.cells/lookattype#CONTAINS) (это значение по умолчанию для этого свойства),
мы автоматически добавим подстановочные знаки в начало и конец поискового ключа.
В этом случае регулярные выражения станут сложнее, а производительность снизится.
###  Определение:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`FindOptions`](/cells/python-net/ru/aspose.cells/findoptions)
* класс [`LookAtType`](/cells/python-net/ru/aspose.cells/lookattype)
