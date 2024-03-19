---
title: region属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 400
url: /zh/aspose.cells/workbooksettings/region/
is_root: false
---
## region属性

获取或设置工作簿的区域设置。

### 评论

1. Aspose.Cells 组件对从模板文件加载的工作簿使用的区域设置：
我）。对于 XLS 文件，存在为区域设置定义的字段，并且 MS Excel 在保存 XLS 文件时确实将区域设置数据保存到文件中。
因此，我们使用工作簿模板文件中保存的 region。
如果您不想使用XLS文件中保存的region，请在加载模板文件后将其重置为预期的值（例如CountryCode.Default）。
并且，在保存 XLS 文件时，我们也将用户指定的值（通过此方法）保存到文件中。
ii).对于其他文件格式，例如XLSX、XLSB...等，文件格式规范中没有为区域设置定义字段。
因此，我们对工作簿使用应用程序环境的区域设置。
并且，对于具有这些文件格式的生成文件，无法保留用户指定的值（通过此方法）。
2、MS Excel中查看效果：
此处应用的区域设置仅在使用 Aspose.Cells 组件运行时生效，而在使用 MS Excel 查看生成的文件时无效。
即使对于生成的保存了指定区域设置数据的 XLS 文件，当使用 MS Excel 查看/编辑它时，
MS Excel 用于执行格式化的 region 始终是 MS Excel 运行环境的默认区域设置，
不是保存在文件中的那个。这是 MS Excel 的行为，无法通过代码更改。
### 定义：
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CountryCode`](/cells/python-net/zh/aspose.cells/countrycode)
* 类 [`WorkbookSettings`](/cells/python-net/zh/aspose.cells/workbooksettings)
