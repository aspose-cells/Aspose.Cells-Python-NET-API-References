---
title: set_metered_key方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key {#str-str}
设置计量公钥和私钥。
如果您购买了计量许可证，那么在开始应用时，应该调用这个API，通常情况下，这就足够了。
但如果始终无法上传消费数据且超过24小时，许可证将被设置为评估状态，
为了避免这种情况，您应该定期检查许可证状态，如果是评估状态，请再次拨打API。



```python
def set_metered_key(self, public_key, private_key):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| public_key | str |公钥|
| private_key | str |私钥|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Metered`](/cells/python-net/zh/aspose.cells/metered)
