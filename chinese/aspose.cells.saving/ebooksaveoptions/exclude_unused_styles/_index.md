---
title: exclude_unused_styles属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles/
is_root: false
---
## exclude_unused_styles属性

指示是否排除未使用的样式。
对于生成的html文件，排除未使用的样式可以使文件体积更小
不影响视觉效果。所以这个属性的默认值为true。
如果用户需要为生成的html保留工作簿中的所有样式（例如用户的场景）
稍后需要从生成的 html 恢复工作簿），请将此属性设置为 false。
### 定义：
```python
@property
def exclude_unused_styles(self):
    ...
@exclude_unused_styles.setter
def exclude_unused_styles(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.saving`](../../)
* 类 [`EbookSaveOptions`](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions)
