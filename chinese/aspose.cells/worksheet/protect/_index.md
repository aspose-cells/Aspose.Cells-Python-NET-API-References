---
title: protect方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 220
url: /zh/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(self, type) {#aspose.cells.ProtectionType}
保护工作表。



```python

def protect(self, type):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/zh/aspose.cells/protectiontype) |防护类型。|
### 注意事项

此方法无需密码即可保护工作表。它适用于所有版本的 Excel 文件中的 protect 工作表。

##  protect(self, type, password, old_password) {#aspose.cells.ProtectionType-str-str}

保护工作表。



```python

def protect(self, type, password, old_password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/zh/aspose.cells/protectiontype) |防护类型。|
| password | str |密码。|
| old_password | str |如果工作表已受密码保护，请提供旧密码。<br/>否则，您可以为此参数设置空值或空白字符串。|
### 注意事项

此方法适用于所有版本的 Excel 文件中的 protect 工作表。
### 例子


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
