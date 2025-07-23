---
title: sever_command属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 300
url: /zh/aspose.cells.externalconnections/dbconnection/sever_command/
is_root: false
---
## sever_command属性

指定在基于服务器的数据透视表时持久保存的第二个命令文本字符串
页面字段正在使用中。
对于 ODBC 连接，serverCommand 通常是一个比 command 更广泛的查询（无
前者存在 WHERE 子句）。基于这两个命令（Command 和 ServerCommand），
可以填充参数 UI 并构建参数化查询

### 注意事项

注意：此属性现已过时。取而代之的是
请使用 ExternalConnection.SecondCommand 属性。
该方法将于 2024 年 10 月起 12 个月后取消。
Aspose 对于您所遇到的不便深表歉意。
### 定义：
```python
@property
def sever_command(self):
    ...
@sever_command.setter
def sever_command(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.externalconnections`](../../)
* 类 [`DBConnection`](/cells/python-net/zh/aspose.cells.externalconnections/dbconnection)
