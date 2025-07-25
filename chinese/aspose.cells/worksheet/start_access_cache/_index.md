---
title: start_access_cache方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 320
url: /zh/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
启动使用缓存访问此工作表中的数据的会话。



```python

def start_access_cache(self, opts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/zh/aspose.cells/accesscacheoptions) |数据访问选项|
### 注意事项

完成数据访问后，[`Worksheet.close_access_cache`](/cells/python-net/zh/aspose.cells/worksheet/close_access_cache) 应该
使用相同选项调用来清除所有缓存并恢复正常访问模式。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
