---
title: DigitalSignature 施工人员
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_（自身，证书，注意事项，签名时间）{#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
digitalSignature 的构造函数。使用 .Net 实现。



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 |用于签署文档的证书对象。|
| comments | str |签名的目的。|
| sign_time | DateTime |签署文件时的 UTC 时间。|


## \_\_init\_\_（自身，原始数据，密码，注意事项，签名时间）{#bytes-str-str-DateTime}
digitalSignature 的构造函数。使用 Bouncy Castle 实现。



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| raw_data | bytes |包含 X.509 证书数据的字节数组。|
| password | str |访问 X.509 证书数据所需的密码。|
| comments | str |签名的目的。|
| sign_time | DateTime |签署文件时的 UTC 时间。|



### 也可以看看
* 模块[`aspose.cells.digitalsignatures`](../../)
* 类 [`DigitalSignature`](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature)
