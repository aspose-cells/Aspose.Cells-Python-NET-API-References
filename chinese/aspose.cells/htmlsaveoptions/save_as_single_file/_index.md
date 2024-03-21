---
title: save_as_single_file属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 620
url: /zh/aspose.cells/htmlsaveoptions/save_as_single_file/
is_root: false
---
## save_as_single_file属性

指示是否将 html 保存为单个文件。
默认值为 false。

### 评论

如果工作簿中有多个工作表或其他所需资源（例如工作簿中的图片），
通常，这些工作表和其他资源需要保存到单独的文件中。
对于某些场景，用户可能只需要获取一个结果文件，例如为了方便传输。
如果是这样，用户可以将此属性设置为 true。
### 定义：
```python
@property
def save_as_single_file(self):
    ...
@save_as_single_file.setter
def save_as_single_file(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`HtmlSaveOptions`](/cells/python-net/zh/aspose.cells/htmlsaveoptions)
