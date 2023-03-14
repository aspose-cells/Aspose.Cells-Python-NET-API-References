---
title: keep_unparsed_data 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 200
url: /zh/aspose.cells/txtloadoptions/keep_unparsed_data/
is_root: false
---
## keep_unparsed_data 属性

从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认为真。

### 评论

对于用户只需要从模板文件中读取部分内容，不需要将工作簿存回的场景，
将此属性设置为 false 可能会提高性能，尤其是在与某种 LoadFilter 一起使用时，
### 定义：
```python
@property
def keep_unparsed_data(self):
    ...
@keep_unparsed_data.setter
def keep_unparsed_data(self, value):
    ...
```

### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [TxtLoadOptions](/cells/python-net/zh/aspose.cells/txtloadoptions)
