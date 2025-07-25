---
title: user_password недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 130
url: /ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password недвижимость

Возвращает или задает пароль пользователя, необходимый для открытия зашифрованного документа PDF.

###  Примечания

Для открытия зашифрованного документа PDF для просмотра потребуется пароль владельца или пароль пользователя.


Пароль пользователя может быть нулевым или пустой строкой, в этом случае при открытии документа PDF от пользователя не потребуется ввод пароля.


Открытие документа с правильным паролем владельца обеспечивает полный доступ к документу.


 Открытие документа с правильным паролем пользователя (или открытие документа, не имеющего пароля пользователя)
обеспечивает ограниченный доступ в соответствии с указанными разрешениями.
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
