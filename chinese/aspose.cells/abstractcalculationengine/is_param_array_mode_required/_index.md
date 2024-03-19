---
title: is_param_array_mode_required属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
## is_param_array_mode_required属性

表示该引擎是否需要以数组方式计算参数。默认值为 false。
如果计算定制时需要[`CalculationData.get_param_value_in_array_mode`](/cells/python-net/zh/aspose.cells/calculationdata/get_param_value_in_array_mode)
函数和用户尚未更新它们的定义
([`Workbook.update_custom_function_definition`](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition)),
该属性需要设置为 true。

### 评论

如果这个自定义计算引擎需要参数以数组方式计算，
需要更多的堆栈来缓存参数树
可以递归调用Calculate()方法来计算参数的值。
出于性能考虑，请保留该属性为默认值(false)
如果没有特殊要求。
### 定义：
```python
@property
def is_param_array_mode_required(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`AbstractCalculationEngine`](/cells/python-net/zh/aspose.cells/abstractcalculationengine)
