---
title: user_password属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 130
url: /zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
## user_password属性

获取或设置打开加密的 PDF 文档所需的用户密码。

### 注意事项

需要所有者密码或用户密码才能打开加密的 PDF 文档进行查看。


用户密码可以为空或空字符串，在这种情况下，打开 PDF 文档时不需要用户输入密码。


使用正确的所有者密码打开文档可以完全访问该文档。


使用正确的用户密码打开文档（或打开没有用户密码的文档）
允许按照指定的权限进行有限访问。
### 定义：
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.rendering.pdfsecurity`](../../)
* 类 [`PdfSecurityOptions`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
