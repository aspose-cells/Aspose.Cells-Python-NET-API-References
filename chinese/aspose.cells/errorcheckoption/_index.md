---
title: ErrorCheckOption类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 550
url: /zh/aspose.cells/errorcheckoption/
is_root: false
---
## ErrorCheckOption类
错误检查设置应用于某些范围。



ErrorCheckOption 类型公开以下成员：

### 方法
|方法|描述|
| :- | :- |
| [is_error_check](/cells/python-net/zh/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.ErrorCheckType) |检查是否将检查给定的错误类型。|
| [set_error_check](/cells/python-net/zh/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.ErrorCheckType-bool) |设置是否检查给定的错误类型。|
| [get_count_of_range](/cells/python-net/zh/aspose.cells/errorcheckoption/get_count_of_range/#) |获取受此设置影响的范围计数。|
| [add_range](/cells/python-net/zh/aspose.cells/errorcheckoption/add_range/#aspose.cells.CellArea) |添加一个受此设置影响的范围。|
| [get_range](/cells/python-net/zh/aspose.cells/errorcheckoption/get_range/#int) |通过给定索引获取该设置的影响范围。|
| [remove_range](/cells/python-net/zh/aspose.cells/errorcheckoption/remove_range/#int) |按给定索引删除一个范围。|



### 例子

```python
from aspose.cells import CellArea, ErrorCheckType, Workbook

workbook = Workbook()
opts = workbook.worksheets[0].error_check_options
optionIdx = opts.add()
opt = opts[optionIdx]
opt.set_error_check(ErrorCheckType.INCONSIST_FORMULA, False)
opt.set_error_check(ErrorCheckType.INCONSIST_RANGE, False)
opt.set_error_check(ErrorCheckType.TEXT_DATE, False)
opt.set_error_check(ErrorCheckType.TEXT_NUMBER, False)
opt.set_error_check(ErrorCheckType.VALIDATION, False)
opt.add_range(CellArea.create_cell_area("A1", "B10"))
workbook.save(r"Book1.xlsx")

```

### 也可以看看
* 模块[`aspose.cells`](..)
