---
title: License类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 930
url: /zh/aspose.cells/license/
is_root: false
---
## License类
提供许可组件的方法。



License 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/license/__init__/#) |初始化此类的新实例。|


### 方法
|方法|描述|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/zh/aspose.cells/license/set_license/#str) |许可该组件。|
| [`set_license(self, stream)`](/cells/python-net/zh/aspose.cells/license/set_license/#io.rawiobase) |许可该组件。|



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

### 也可以看看
* 模块[`aspose.cells`](..)
