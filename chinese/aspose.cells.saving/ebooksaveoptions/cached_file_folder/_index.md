---
title: cached_file_folder属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells.saving/ebooksaveoptions/cached_file_folder/
is_root: false
---
## cached_file_folder属性

可用作数据缓存的临时文件的文件夹。

### 注意事项

如果未指定文件夹，
它的默认值是 [`CellsHelper.get_cache_folder`](/cells/python-net/zh/aspose.cells/cellshelper/get_cache_folder)。
如果其默认值为 null 或空，或者已指定为 null 或空，
那么保存工作簿时将不会使用缓存文件。
### 定义：
```python
@property
def cached_file_folder(self):
    ...
@cached_file_folder.setter
def cached_file_folder(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.saving`](../../)
* 类 [`EbookSaveOptions`](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions)
