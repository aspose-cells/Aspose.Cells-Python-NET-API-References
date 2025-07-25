---
title: LookInType枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2270
url: /zh/aspose.cells/lookintype/
is_root: false
---
## LookInType枚举
代表外观类型。



LookInType 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| FORMULAS |如果单元格是公式，则从公式（[`Cell.formula`](/cells/python-net/zh/aspose.cells/cell#formula)）中查找搜索的对象，<br/>否则从单元格的原始值中找到（与 [`LookInType.ORIGINAL_VALUES`](/cells/python-net/zh/aspose.cells/lookintype#ORIGINAL_VALUES) 相同）。|
| VALUES |从单元格的原始值中查找对象（[`Cell.value`](/cells/python-net/zh/aspose.cells/cell#value)）<br/>和格式化的值（[`Cell.string_value`](/cells/python-net/zh/aspose.cells/cell#string_value)）。|
| VALUES_EXCLUDE_FORMULA_CELL |忽略包含公式的单元格。对于不包含公式的单元格，<br/>与[`LookInType.VALUES`](/cells/python-net/zh/aspose.cells/lookintype#VALUES)相同。|
| COMMENTS |仅根据单元格的注释查找对象。忽略没有注释的单元格。|
| ONLY_FORMULAS |忽略非公式的单元格。对于公式单元格，<br/>从公式 ([`Cell.formula`](/cells/python-net/zh/aspose.cells/cell#formula)) 中找到搜索的对象。|
| ORIGINAL_VALUES |仅从单元格的原始值中查找对象。|
| FORMATTED_VALUES |仅从单元格的格式化值（[`Cell.string_value`](/cells/python-net/zh/aspose.cells/cell#string_value)）中查找对象。|



### 也可以看看
* 模块[`aspose.cells`](..)
