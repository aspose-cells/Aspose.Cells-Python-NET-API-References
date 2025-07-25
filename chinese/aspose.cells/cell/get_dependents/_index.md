---
title: get_dependents方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
获取公式直接引用该单元格的所有单元格。



```python

def get_dependents(self, is_all):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| is_all | bool |指示是否检查其他工作表中的公式|
### 注意事项

* 如果包含此单元格的引用出现在一个单元格的公式中，则该单元格将被视为

此单元格的依赖项，无论计算时是否使用参考或此单元格。
例如，虽然公式“=IF(TRUE,A1,A2)”在计算时没有使用单元格 A2，
此公式仍作为A2的从项。
要获取那些计算结果依赖于该单元格的公式，请使用 [`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)。当追踪一个单元格的依赖项时，工作簿或工作表中的所有公式都将被分析和检查。
所以这是一个耗时的过程。如果用户需要追踪大量细胞的依赖关系，使用此方法将
会导致性能不佳。出于性能考虑，用户应改用 [`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)。
或者，用户可以先通过 [`Cell.get_precedents`](/cells/python-net/zh/aspose.cells/cell/get_precedents) 收集所有单元格的先例图，
然后根据先例图构建家属图。

* 如果包含此单元格的引用出现在一个单元格的公式中，则该单元格将被视为
此单元格的依赖项，无论计算时是否使用参考或此单元格。
例如，虽然公式“=IF(TRUE,A1,A2)”在计算时没有使用单元格 A2，
此公式仍作为A2的从项。
要获取那些计算结果依赖于该单元格的公式，请使用 [`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)。当追踪一个单元格的依赖项时，工作簿或工作表中的所有公式都将被分析和检查。
所以这是一个耗时的过程。如果用户需要追踪大量细胞的依赖关系，使用此方法将
会导致性能不佳。出于性能考虑，用户应改用 [`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)。
或者，用户可以先通过 [`Cell.get_precedents`](/cells/python-net/zh/aspose.cells/cell/get_precedents) 收集所有单元格的先例图，
然后根据先例图构建家属图。

* 如果包含此单元格的引用出现在一个单元格的公式中，则该单元格将被视为
此单元格的依赖项，无论计算时是否使用参考或此单元格。
例如，虽然公式“=IF(TRUE,A1,A2)”在计算时没有使用单元格 A2，
此公式仍作为A2的从项。
要获取那些计算结果依赖于该单元格的公式，请使用 [`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)。当追踪一个单元格的依赖项时，工作簿或工作表中的所有公式都将被分析和检查。
所以这是一个耗时的过程。如果用户需要追踪大量细胞的依赖关系，使用此方法将
会导致性能不佳。出于性能考虑，用户应改用 [`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)。
或者，用户可以先通过 [`Cell.get_precedents`](/cells/python-net/zh/aspose.cells/cell/get_precedents) 收集所有单元格的先例图，
然后根据先例图构建家属图。
### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
