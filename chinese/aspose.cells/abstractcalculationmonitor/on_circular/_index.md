---
title: on_circular方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
实现这个方法可以在计算带有循环引用的公式时做业务。


### 退货

公式引擎是否需要在此调用后计算循环中的那些单元格。
真正让公式引擎继续为他们做计算。
如果让公式引擎仅将这些单元格标记为已计算，则为 False。


```python
def on_circular(self, circular_cells_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator |IEnumerator 具有 [`CalculationCell`](/cells/python-net/zh/aspose.cells/calculationcell) 项，代表单元格<br/>依赖于循环引用。|
### 评论

在实现中用户也可以将期望值设置为计算结果
对于部分/全部这些单元格，因此公式引擎不会递归计算它们。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`AbstractCalculationMonitor`](/cells/python-net/zh/aspose.cells/abstractcalculationmonitor)
* 类 [`CalculationCell`](/cells/python-net/zh/aspose.cells/calculationcell)
