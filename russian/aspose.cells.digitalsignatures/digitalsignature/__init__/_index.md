---
title: DigitalSignature конструктор
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(сам, сертификат, комментарии, время_подписания){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
Конструктор digitalSignature. Использует реализацию .Net.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Объект сертификата, который был использован для подписи документа.|
| comments | str | Цель подписания.|
| sign_time | DateTime | Время UTC, когда документ был подписан.|


## \_\_init\_\_(self, raw_data, password, comments, sign_time){#bytes-str-str-DateTime}
Конструктор digitalSignature. Использует реализацию Bouncy Castle.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| raw_data | bytes | Массив байтов, содержащий данные из сертификата X.509.|
| password | str | Пароль, необходимый для доступа к данным сертификата X.509.|
| comments | str | Цель подписания.|
| sign_time | DateTime | Время UTC, когда документ был подписан.|



###  Смотрите также
* модуль [`aspose.cells.digitalsignatures`](../../)
* класс [`DigitalSignature`](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature)
