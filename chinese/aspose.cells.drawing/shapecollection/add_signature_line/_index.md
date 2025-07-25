---
title: add_signature_line方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 310
url: /zh/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
在工作表中添加签名行。


### 返回




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| signature_line | [`SignatureLine`](/cells/python-net/zh/aspose.cells.drawing/signatureline) |表示签名行对象。|

### 例子

```python
from aspose.cells.drawing import SignatureLine

wSignatureLine = SignatureLine()
wSignatureLine.allow_comments = True
wSignatureLine.email = "example@example.com"
wSignatureLine.instructions = "Sign to confirm the excel content."
wSignatureLine.is_line = True
wSignatureLine.show_signed_date = True
wSignatureLine.signer = "User"
wSignatureLine.title = "tester"
# wSignatureLine.SignatureLineType = SignatureType.Stamp;
signatureLine1 = shapes.add_signature_line(0, 0, wSignatureLine)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
