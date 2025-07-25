---
title: memory_setting属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1160
url: /zh/aspose.cells/cells/memory_setting/
is_root: false
---
## memory_setting属性

获取或设置此单元格的内存使用选项。

### 注意事项

某些模式的显著限制和建议操作：
|模式|注意事项|支持|
| :- | :- | :- |
|
以降低内存成本。另一方面，紧凑的数据也可能
导致更高的时间成本，特别是在更新细胞数据时，
或随机访问单元格/行| v8.0.0 |
|
当此模式用于一个工作簿中的任意工作表时，|
应在工作结束时调用以释放所有资源，例如临时文件。
            | 
随机访问单元格会导致性能不佳，因为数据需要
随机且重复地读取/更新（因此文件中的指针将
相应地改变并且需要重复进行IO操作）。
如果可能，请始终按顺序（逐行）访问数据。
            | 
当某一行/单元格的数据发生变化时，其他单元格/行的数据
也可能受到影响（例如数据被转移/移动到其他地方
为更改的数据分配足够的空间）。
因此每个数据的每次更改都需要同步其他现有对象（
例如 Row 或 Cell 对象）。
因此，为了获得更好的性能，请不要维护多个 Rows/Cells
同时处理。逐个处理会降低数据同步
对他们来说，这样性能就可以稍微提高一些。
 | v25.7 |
### 定义：
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
* 类 [`MemorySetting`](/cells/python-net/zh/aspose.cells/memorysetting)
