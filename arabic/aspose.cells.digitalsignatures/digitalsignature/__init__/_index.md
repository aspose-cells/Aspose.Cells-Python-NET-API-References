---
title: DigitalSignature منشئ
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(الذات، الشهادة، التعليقات، وقت التوقيع){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
منشئ التوقيع الرقمي. يستخدم تطبيق .Net.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | كائن الشهادة الذي تم استخدامه لتوقيع المستند.|
| comments | str | الغرض من التوقيع.|
| sign_time | DateTime | الوقت المحدد بالتوقيت العالمي المنسق عندما تم توقيع المستند.|


## \_\_init\_\_(الذات، البيانات الخام، كلمة المرور، التعليقات، وقت التوقيع){#bytes-str-str-DateTime}
مُنشئ التوقيع الرقمي. يستخدم تطبيق Bouncy Castle.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| raw_data | bytes | مجموعة بايتات تحتوي على بيانات من شهادة X.509.|
| password | str | كلمة المرور المطلوبة للوصول إلى بيانات شهادة X.509.|
| comments | str | الغرض من التوقيع.|
| sign_time | DateTime | الوقت المحدد بالتوقيت العالمي المنسق عندما تم توقيع المستند.|



###  أنظر أيضا
* الوحدة [`aspose.cells.digitalsignatures`](../../)
* فئة [`DigitalSignature`](/cells/python-net/ar/aspose.cells.digitalsignatures/digitalsignature)
