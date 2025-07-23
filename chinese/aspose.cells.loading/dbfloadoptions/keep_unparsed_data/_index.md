---
title: keep_unparsed_data属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells.loading/dbfloadoptions/keep_unparsed_data/
is_root: false
---
## keep_unparsed_data属性

从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认值为 true。

### 注意事项

对于用户只需要从模板文件中读取部分内容，而不需要保存工作簿的情况，
将此属性设置为 false 可能会提高性能，尤其是与某种 LoadFilter 一起使用时，
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
* 模块[`aspose.cells.loading`](../../)
* 类 [`DbfLoadOptions`](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions)
