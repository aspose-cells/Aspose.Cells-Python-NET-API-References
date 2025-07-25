---
title: get_cache_folder方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 100
url: /zh/aspose.cells/cellshelper/get_cache_folder/
is_root: false
---
##  get_cache_folder() {#}
获取可用作数据缓存的临时文件的文件夹。


### 返回

已指定的缓存文件文件夹。
如果没有指定，则返回 null
并在需要时使用系统的临时路径。


```python

@staticmethod
def get_cache_folder():
    ...
```


### 注意事项

缓存文件通常用于某些功能，用于内存性能考虑，
例如将大型数据集保存到 xls 文件，
或者使用带有文件缓存的内存模式作为细胞模型。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CellsHelper`](/cells/python-net/zh/aspose.cells/cellshelper)
