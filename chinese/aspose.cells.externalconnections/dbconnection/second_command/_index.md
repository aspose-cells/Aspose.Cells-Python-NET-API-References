---
title: second_command属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 290
url: /zh/aspose.cells.externalconnections/dbconnection/second_command/
is_root: false
---
## second_command属性

指定在基于服务器的数据透视表时持久保存的第二个命令文本字符串
页面字段正在使用中。
对于 ODBC 连接，serverCommand 通常是一个比 command 更广泛的查询（无
前者存在 WHERE 子句）。基于这两个命令（Command 和 ServerCommand），
可以填充参数 UI 并构建参数化查询
### 定义：
```python
@property
def second_command(self):
    ...
@second_command.setter
def second_command(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.externalconnections`](../../)
* 类 [`DBConnection`](/cells/python-net/zh/aspose.cells.externalconnections/dbconnection)
