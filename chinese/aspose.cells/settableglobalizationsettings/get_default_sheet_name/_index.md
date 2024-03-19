---
title: get_default_sheet_name方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name {#}
获取自动添加工作表的默认工作表名称。
默认为“工作表”。


### 退货

自动添加工作表的默认工作表名称


```python
def get_default_sheet_name(self):
    ...
```


### 评论

自动添加（如[`WorksheetCollection.add`](/cells/python-net/zh/aspose.cells/worksheetcollection/add)）
工作表的名称将是指定的名称加上序列号。
例如，对于德国用户可能希望工作表名称为“Tabellenblatt2”而不是“Sheet2”。
然后用户可以实现此方法以返回“Tabellenblatt”。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`SettableGlobalizationSettings`](/cells/python-net/zh/aspose.cells/settableglobalizationsettings)
