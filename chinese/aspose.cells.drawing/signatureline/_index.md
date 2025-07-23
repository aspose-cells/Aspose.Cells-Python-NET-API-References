---
title: SignatureLine类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 610
url: /zh/aspose.cells.drawing/signatureline/
is_root: false
---
## SignatureLine类
代表签名行。



SignatureLine 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.drawing/signatureline/__init__/#) |构造一个新的 SignatureLine 实例|


### 属性
|属性|描述|
| :- | :- |
| [id](/cells/python-net/zh/aspose.cells.drawing/signatureline/id) |获取或设置此签名行的标识符。|
| [provider_id](/cells/python-net/zh/aspose.cells.drawing/signatureline/provider_id) |获取或设置签名提供者的 ID。|
| [signer](/cells/python-net/zh/aspose.cells.drawing/signatureline/signer) |获取或设置签名者。|
| [title](/cells/python-net/zh/aspose.cells.drawing/signatureline/title) |获取或设置歌手的称号。|
| [email](/cells/python-net/zh/aspose.cells.drawing/signatureline/email) |获取或设置歌手的电子邮件。|
| [is_line](/cells/python-net/zh/aspose.cells.drawing/signatureline/is_line) |指示是否为签名行。|
| [allow_comments](/cells/python-net/zh/aspose.cells.drawing/signatureline/allow_comments) |指示是否可以附加注意事项。|
| [show_signed_date](/cells/python-net/zh/aspose.cells.drawing/signatureline/show_signed_date) |指示是否显示签署日期。|
| [instructions](/cells/python-net/zh/aspose.cells.drawing/signatureline/instructions) |获取或设置签名时向用户显示的文本。|
| [signature_line_type](/cells/python-net/zh/aspose.cells.drawing/signatureline/signature_line_type) |获取或设置签名类型。<br/>Default - 设置默认值时，对应的ProviderId值固定为{0000000000-0000-0000-0000-0000000000}。<br/>Stamp - 当值为Stamp时，对应的ProviderId值通常为{000CD6A4-0000-0000-C000-000000000046}。<br/> Custom - 当值为Custom时，对应的ProviderId值通常需要用户设置，可以从提供商附带的文档中获取。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.drawing import SignatureLine

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
#  Create signature line object
s = SignatureLine()
s.signer = "Simon"
s.title = "Development"
s.email = "simon@aspose.com"
s.instructions = "Sign to confirm the excel content."
#  Adds a Signature Line to the worksheet.
signatureLine = worksheet.shapes.add_signature_line(0, 0, s)
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing`](..)
