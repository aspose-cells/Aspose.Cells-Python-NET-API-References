---
title: ReConnectionMethodType枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 130
url: /zh/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
## ReConnectionMethodType枚举
指定当连接失败时电子表格应用程序应该做什么。



ReConnectionMethodType 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| REQUIRED |刷新时使用现有的连接信息，如果最终无效<br/>然后获取更新的连接信息（如果可从外部连接文件获得）。|
| ALWAYS |每次刷新时从外部连接文件获取更新的连接信息，<br/>如果可用，并使用它来代替现有的连接信息。<br/>在这种情况下，如果外部连接文件不可用，数据刷新将失败。|
| NEVER |永远不要从外部连接文件获取更新的连接信息<br/>即使可用，即使现有的连接信息无效|



### 也可以看看
* 模块[`aspose.cells.externalconnections`](..)
