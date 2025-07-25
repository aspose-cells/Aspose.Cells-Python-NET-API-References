---
title: DigitalSignature类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
## DigitalSignature类
文件中的签名。



DigitalSignature 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | digitalSignature 的构造函数。使用 .Net 实现。|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |digitalSignature 的构造函数。使用 Bouncy Castle 实现。|


### 属性
|属性|描述|
| :- | :- |
| [certificate](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/certificate) |用于签署文档的证书对象。|
| [comments](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/comments) |签名的目的。|
| [sign_time](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/sign_time) |文件签署的时间。|
| [id](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/id) |指定一个 GUID，该 GUID 可以与文档内容中存储的签名行的 GUID 交叉引用。<br/>默认值为空（全零）Guid。|
| [text](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/text) |指定数字签名中实际签名的文本。<br/>默认值为空。|
| [image](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/image) |指定数字签名的图像。<br/>默认值为空。|
| [provider_id](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/provider_id) |指定签名提供者的类 ID。<br/>默认值为空（全零）Guid。|
| [is_valid](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/is_valid) |如果该数字签名有效且文档未被篡改，<br/>这个值将为真。|
| [x_ad_es_type](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | XAdES 类型。<br/>默认值为无（XAdES 关闭）。|



### 也可以看看
* 模块[`aspose.cells.digitalsignatures`](..)
