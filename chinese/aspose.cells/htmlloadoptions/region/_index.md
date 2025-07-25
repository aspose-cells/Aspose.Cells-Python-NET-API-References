---
title: region属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 330
url: /zh/aspose.cells/htmlloadoptions/region/
is_root: false
---
## region属性

获取或设置将要加载的工作簿所使用的区域设置。

### 注意事项

区域设置可用于初始化工作簿的某些功能
例如字体、主题等等。
对于基于文本的文件格式，例如 CSV、HTML，...，区域设置
还将用于检测数字格式并将文本值解析为数字
或单元格的日期时间值。
此设置稍后将保留用于实例化的工作簿，即
工作簿的 [`WorkbookSettings.region`](/cells/python-net/zh/aspose.cells/workbooksettings#region) 将使用相同的 region
具有此属性。
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
* 类 [`HtmlLoadOptions`](/cells/python-net/zh/aspose.cells/htmlloadoptions)
