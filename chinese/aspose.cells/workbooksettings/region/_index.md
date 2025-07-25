---
title: region属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 440
url: /zh/aspose.cells/workbooksettings/region/
is_root: false
---
## region属性

获取或设置工作簿的区域设置。

### 注意事项

1. Aspose.Cells 组件用于从模板文件加载的工作簿的区域设置：
i). 对于 XLS 文件，其中定义了区域设置字段，并且 MS Excel 在保存 XLS 文件时会将区域设置数据保存到文件中。
因此，我们在工作簿的模板文件中使用已保存的 region。
如果您不想使用 XLS 文件中保存的 region，请在加载模板文件后将其重置为预期的值（例如，CountryCode.Default）。
并且，在保存 XLS 文件时，我们也将用户指定的值（通过此方法）保存到文件中。
ii). 对于其他文件格式，例如 XLSX、XLSB...等，文件格式规范中没有为区域设置定义字段。
因此，我们对工作簿使用应用程序环境的区域设置。
并且，对于使用这些文件格式生成的文件，无法保留用户指定的值（通过此方法）。
2.在MS Excel中查看效果：
此处应用的区域设置仅在使用 Aspose.Cells 组件运行时生效，而不在使用 MS Excel 查看生成的文件时生效。
即使对于已保存指定区域设置数据的生成的 XLS 文件，在使用 MS Excel 查看/编辑它时，
用于通过 MS Excel 执行格式化的 region 始终是 MS Excel 运行环境的默认区域设置，
而不是文件中保存的那个。这是 MS Excel 的行为，无法通过代码更改。
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
