---
title: VbaProject类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.vba/vbaproject/
is_root: false
---
## VbaProject类
代表 VBA 项目。



VbaProject 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [is_valid_signed](/cells/python-net/zh/aspose.cells.vba/vbaproject/is_valid_signed) |指示 VBA 项目的签名是否有效。|
| [cert_raw_data](/cells/python-net/zh/aspose.cells.vba/vbaproject/cert_raw_data) |如果此 VBA 项目已签名，则获取证书原始数据。|
| [encoding](/cells/python-net/zh/aspose.cells.vba/vbaproject/encoding) |获取和设置 VBA 项目的编码。|
| [name](/cells/python-net/zh/aspose.cells.vba/vbaproject/name) |获取并设置 VBA 项目的名称。|
| [is_signed](/cells/python-net/zh/aspose.cells.vba/vbaproject/is_signed) |指示 VBAcode 是否已签名。|
| [is_protected](/cells/python-net/zh/aspose.cells.vba/vbaproject/is_protected) |指示此 VBA 项目是否受保护。|
| [islocked_for_viewing](/cells/python-net/zh/aspose.cells.vba/vbaproject/islocked_for_viewing) |指示此 VBA 项目是否被锁定以供查看。|
| [modules](/cells/python-net/zh/aspose.cells.vba/vbaproject/modules) |获取所有 [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) 对象。|
| [references](/cells/python-net/zh/aspose.cells.vba/vbaproject/references) |获取 VBA 项目的所有引用。|


### 方法
|方法|描述|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/zh/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) |使用数字签名对此 VBA 项目进行签名|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/zh/aspose.cells.vba/vbaproject/protect/#bool-str) |保护或取消保护此 VBA 项目。|
| [`copy(self, source)`](/cells/python-net/zh/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) |从其他文件复制 VBA 项目。|
| [`validate_password(self, password)`](/cells/python-net/zh/aspose.cells.vba/vbaproject/validate_password/#str) |验证保护密码。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

### 也可以看看
* 模块[`aspose.cells.vba`](..)
* 类 [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule)
