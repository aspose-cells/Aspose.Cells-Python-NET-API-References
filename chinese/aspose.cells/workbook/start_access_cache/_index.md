---
title: start_access_cache方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 400
url: /zh/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
启动使用缓存访问数据的会话。



```python

def start_access_cache(self, opts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/zh/aspose.cells/accesscacheoptions) |数据访问选项|
### 注意事项

如果指定数据访问的缓存要求工作表中某些数据模型为“只读”，
那么此工作簿中每个工作表中的相应数据模型将被视为“只读”
用户不应该改变其中任何一个。


完成数据访问后，[`Workbook.close_access_cache`](/cells/python-net/zh/aspose.cells/workbook/close_access_cache) 应该
使用相同选项调用来清除所有缓存并恢复正常访问模式。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
