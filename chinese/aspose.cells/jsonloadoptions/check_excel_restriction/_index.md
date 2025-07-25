---
title: check_excel_restriction属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/jsonloadoptions/check_excel_restriction/
is_root: false
---
## check_excel_restriction属性

当用户修改单元格相关对象时是否检查Excel文件的限制。
例如，excel不允许输入长度超过32K的字符串值。
当您输入一个长度超过 32K 的值（例如 Cell.PutValue(string)）时，如果此属性为真，您将收到异常。
如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后
您可以输出其他文件格式的完整字符串值，例如 CSV。
但是，如果您设置了对 Excel 文件格式无效的值，
请勿将工作簿保存为 Excel 文件格式。否则，生成的 Excel 文件可能会出现意外错误。
### 定义：
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`JsonLoadOptions`](/cells/python-net/zh/aspose.cells/jsonloadoptions)
