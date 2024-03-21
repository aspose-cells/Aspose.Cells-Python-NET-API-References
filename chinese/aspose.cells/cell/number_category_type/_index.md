---
title: number_category_type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 670
url: /zh/aspose.cells/cell/number_category_type/
is_root: false
---
## number_category_type属性

表示此单元格数字格式的类别类型。

### 评论

当单元格的格式模式与条件格式模式组合时，
那么返回的类型对应于该单元格当前值所使用的部分。
例如，如果此单元格的格式模式为“#,##0;(#,##0);”-“;@”，
那么当cell的值为数字且不为0时，返回类型为[`NumberCategoryType.NUMBER`](/cells/python-net/zh/aspose.cells/numbercategorytype#NUMBER)；
当单元格值为0或非数值时，返回类型为[`NumberCategoryType.TEXT`](/cells/python-net/zh/aspose.cells/numbercategorytype#TEXT)。
### 定义：
```python
@property
def number_category_type(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
* 类 [`NumberCategoryType`](/cells/python-net/zh/aspose.cells/numbercategorytype)
