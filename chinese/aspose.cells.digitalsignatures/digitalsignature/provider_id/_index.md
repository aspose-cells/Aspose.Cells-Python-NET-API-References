---
title: provider_id属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells.digitalsignatures/digitalsignature/provider_id/
is_root: false
---
## provider_id属性

指定签名提供者的类 ID。
默认值为空（全零）Guid。

### 注意事项

加密服务提供者 (CSP) 是一个独立的软件模块，实际上执行用于身份验证、编码和加密的密码算法。
Microsoft Office 为其默认签名提供商保留值 {00000000-0000-0000-0000-000000000000}，
并将其作为东亚签名提供商的{000CD6A4-0000-0000-C000-000000000046}。

应从提供程序附带的文档中获取附加安装的提供程序的 GUID。
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
* 模块[`aspose.cells.digitalsignatures`](../../)
* 类 [`DigitalSignature`](/cells/python-net/zh/aspose.cells.digitalsignatures/digitalsignature)
