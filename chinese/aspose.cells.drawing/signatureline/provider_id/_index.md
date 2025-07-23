---
title: provider_id属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells.drawing/signatureline/provider_id/
is_root: false
---
## provider_id属性

获取或设置签名提供者的 ID。

### 注意事项

它通常是提供程序 com 插件的 CLSID。

### 例子

```python
from aspose.cells.drawing import SignatureLine
from uuid import uuid4

#  Create signature line object
s2 = SignatureLine()
s2.provider_id = uuid4("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx")

```
### 定义：
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`SignatureLine`](/cells/python-net/zh/aspose.cells.drawing/signatureline)
