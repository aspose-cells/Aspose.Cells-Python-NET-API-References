---
title: Metered类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 980
url: /zh/aspose.cells/metered/
is_root: false
---
## Metered类
提供设置计量键的方法。



Metered 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/metered/__init__/#) |初始化此类的新实例。|


### 方法
|方法|描述|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/zh/aspose.cells/metered/set_metered_key/#str-str) |设置计量的公钥和私钥。<br/>如果您购买了计量许可证，则在启动应用程序时应该调用此 API，通常这就足够了。<br/>但如果始终无法上传消费数据且超过24小时，许可证将被设置为评估状态，<br/>为了避免这种情况，您应该定期检查许可证状态，如果是评估状态，请再次拨打API。|
| [`get_consumption_quantity()`](/cells/python-net/zh/aspose.cells/metered/get_consumption_quantity/#) |获取消费文件大小|
| [`get_consumption_credit()`](/cells/python-net/zh/aspose.cells/metered/get_consumption_credit/#) |获得消费信贷|
| [`get_product_name(self)`](/cells/python-net/zh/aspose.cells/metered/get_product_name/#) |获取产品名称|
| [`is_metered_licensed()`](/cells/python-net/zh/aspose.cells/metered/is_metered_licensed/#) |检查计量是否已获得许可|



### 例子

在此示例中，将尝试设置计量公钥和私钥


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

### 也可以看看
* 模块[`aspose.cells`](..)
