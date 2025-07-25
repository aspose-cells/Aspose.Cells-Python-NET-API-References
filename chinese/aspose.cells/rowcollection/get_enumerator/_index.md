---
title: get_enumerator方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
获取一个遍历此集合中行的枚举器


### 返回

行枚举器


```python

def get_enumerator(self, reversed, sync):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| reversed | bool |是否以相反的顺序枚举行|
| sync | bool |返回的枚举器是否应该检查行集合的修改<br/>并与其保持同步。|
### 注意事项

如果行集合将被修改（通过可能导致新 Row 实例化的操作或
在使用枚举器进行遍历时（现有行被删除），
应使用同步枚举器代替普通枚举器，以便遍历可以继续
从上一次 MoveNext() 遍历的位置之后的位置开始。
然而，除了没有元素被跳过或重复遍历的优点之外，
同步枚举器的缺点是性能会稍微下降
与普通枚举器相比。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`RowCollection`](/cells/python-net/zh/aspose.cells/rowcollection)
