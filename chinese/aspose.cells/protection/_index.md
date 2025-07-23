---
title: Protection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1150
url: /zh/aspose.cells/protection/
is_root: false
---
## Protection类
代表工作表可用的各种类型的保护选项。



Protection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [allow_deleting_column](/cells/python-net/zh/aspose.cells/protection/allow_deleting_column) |表示是否允许在受保护的工作表上删除列。|
| [allow_deleting_row](/cells/python-net/zh/aspose.cells/protection/allow_deleting_row) |表示是否允许在受保护的工作表上删除行。|
| [allow_filtering](/cells/python-net/zh/aspose.cells/protection/allow_filtering) |表示是否允许用户使用在工作表受到保护之前创建的自动筛选器。|
| [allow_formatting_cell](/cells/python-net/zh/aspose.cells/protection/allow_formatting_cell) |表示是否允许在受保护的工作表上设置单元格格式。|
| [allow_formatting_column](/cells/python-net/zh/aspose.cells/protection/allow_formatting_column) |表示是否允许在受保护的工作表上设置列的格式|
| [allow_formatting_row](/cells/python-net/zh/aspose.cells/protection/allow_formatting_row) |表示是否允许在受保护的工作表上设置行格式|
| [allow_inserting_column](/cells/python-net/zh/aspose.cells/protection/allow_inserting_column) |表示是否允许在受保护的工作表上插入列|
| [allow_inserting_hyperlink](/cells/python-net/zh/aspose.cells/protection/allow_inserting_hyperlink) |表示是否允许在受保护的工作表上插入超链接|
| [allow_inserting_row](/cells/python-net/zh/aspose.cells/protection/allow_inserting_row) |表示是否允许在受保护的工作表上插入行|
| [allow_sorting](/cells/python-net/zh/aspose.cells/protection/allow_sorting) |表示是否允许在受保护的工作表上使用排序选项。|
| [allow_using_pivot_table](/cells/python-net/zh/aspose.cells/protection/allow_using_pivot_table) |表示是否允许用户操作受保护工作表上的数据透视表。|
| [allow_editing_content](/cells/python-net/zh/aspose.cells/protection/allow_editing_content) |表示是否允许用户编辑受保护工作表上锁定单元格的内容。|
| [allow_editing_object](/cells/python-net/zh/aspose.cells/protection/allow_editing_object) |表示是否允许用户操作受保护的工作表上的绘图对象。|
| [allow_editing_scenario](/cells/python-net/zh/aspose.cells/protection/allow_editing_scenario) |表示是否允许用户在受保护的工作表上编辑场景。|
| [allow_selecting_locked_cell](/cells/python-net/zh/aspose.cells/protection/allow_selecting_locked_cell) |表示是否允许用户选择受保护的工作表上的锁定单元格。|
| [allow_selecting_unlocked_cell](/cells/python-net/zh/aspose.cells/protection/allow_selecting_unlocked_cell) |表示是否允许用户选择受保护工作表上未锁定的单元格。|
| [password](/cells/python-net/zh/aspose.cells/protection/password) |表示保护工作表的密码。|
| [is_protected_with_password](/cells/python-net/zh/aspose.cells/protection/is_protected_with_password) |指示工作表是否受密码保护。|


### 方法
|方法|描述|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/zh/aspose.cells/protection/copy/#aspose.cells.protection) |复制保护信息。|
| [`verify_password(self, password)`](/cells/python-net/zh/aspose.cells/protection/verify_password/#str) |验证密码。|
| [`get_password_hash(self)`](/cells/python-net/zh/aspose.cells/protection/get_password_hash/#) |获取当前密码的哈希值。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

### 也可以看看
* 模块[`aspose.cells`](..)
