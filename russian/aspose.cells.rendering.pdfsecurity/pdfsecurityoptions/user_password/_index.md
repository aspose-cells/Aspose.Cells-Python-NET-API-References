---
title: user_password недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 130
url: /ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password недвижимость

Получает или задает пароль пользователя, необходимый для открытия зашифрованного документа PDF.

###  Примечания

Для открытия зашифрованного документа PDF для просмотра потребуется пароль владельца или пароль пользователя.


Пароль пользователя может быть нулевым или пустой строкой, в этом случае пароль от пользователя не будет требоваться при открытии документа PDF.


Открытие документа с правильным паролем владельца обеспечивает полный доступ к документу.


 Открытие документа с правильным паролем пользователя (или открытие документа без пароля пользователя)
разрешает ограниченный доступ в соответствии с указанными разрешениями.
###  Определение:
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.rendering.pdfsecurity`](../../)
* класс [`PdfSecurityOptions`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
