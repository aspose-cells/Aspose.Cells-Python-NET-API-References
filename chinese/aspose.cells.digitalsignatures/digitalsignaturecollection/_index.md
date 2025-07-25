---
title: DigitalSignatureCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.digitalsignatures/digitalsignaturecollection/
is_root: false
---
## DigitalSignatureCollection类
提供附加到文档的数字签名集合。



DigitalSignatureCollection 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignaturecollection/__init__/#) | DigitalSignatureCollection 的构造函数。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, digital_signature)`](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignaturecollection/add/#aspose.cells.digitalsignatures.digitalsignature) |向 DigitalSignatureCollection 添加一个签名。|



### 例子

以下示例显示如何验证数字签名。

```python
from aspose.cells import Workbook

# workbook from a signed source file
signedWorkbook = Workbook(r"signedFile.xlsx")
# wb.IsDigitallySigned is true when the workbook is signed already.
print(signedWorkbook.is_digitally_signed)
# get digitalSignature collection from workbook
existingDsc = signedWorkbook.get_digital_signature()
for existingDs in existingDsc:
    print(existingDs.comments)
    print(existingDs.sign_time)
    print(existingDs.is_valid)

```

### 也可以看看
* 模块[`aspose.cells.digitalsignatures`](..)
