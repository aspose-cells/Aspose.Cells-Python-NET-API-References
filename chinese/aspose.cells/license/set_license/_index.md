---
title: set_license方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/license/set_license/
is_root: false
---
##  set_license(self, license_name) {#str}
许可该组件。



```python

def set_license(self, license_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| license_name | str |  |
### 注意事项

尝试在以下位置查找许可证：


1. 明确路径。


2. 包含Aspose组件的文件夹。


3. 包含客户端调用程序集的文件夹。


4. 包含入口（启动）程序集的文件夹。


5. 客户端调用程序集中的嵌入资源。


**笔记：**在 .NET Compact Framework 上，尝试仅在以下位置查找许可证：


1. 明确路径。


2. 客户端调用程序集中的嵌入资源。
### 例子


在此示例中，将尝试查找名为 MyLicense.lic 的许可证文件
在包含的文件夹中


包含调用程序集的文件夹中的组件，
在入口程序集的文件夹中，然后在调用程序集的嵌入资源中。

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```
可以是完整或短文件名或嵌入资源的名称。
使用空字符串切换到评估模式。


##  set_license(self, stream) {#io.RawIOBase}
许可该组件。



```python

def set_license(self, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |包含许可证的流。|
### 注意事项

使用此方法从流加载许可证。
### 例子


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`License`](/cells/python-net/zh/aspose.cells/license)
