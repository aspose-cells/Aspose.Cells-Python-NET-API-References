---
title: custom_path属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/streamprovideroptions/custom_path/
is_root: false
---
## custom_path属性

用户自定义的路径（URL）保存在生成的 HTML 文件中，用于引用源。如果用户未定义，则使用 DefaultPath。
例如，用户将工作表数据保存到 d:/sheet001.htm，主 html 文件中使用的 url 应该是“d:/sheet001.htm”或其他可以被主 html 文件访问的有效相对路径。
### 定义：
```python
@property
def custom_path(self):
    ...
@custom_path.setter
def custom_path(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`StreamProviderOptions`](/cells/python-net/zh/aspose.cells/streamprovideroptions)
