---
title: LightCellsDataProvider类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1040
url: /zh/aspose.cells/lightcellsdataprovider/
is_root: false
---
## LightCellsDataProvider类
代表用于以轻量级模式保存大型电子表格文件的数据提供者。



LightCellsDataProvider 类型公开以下成员：

### 方法
|方法|描述|
| :- | :- |
| [start_sheet](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_sheet/#int) |开始保存工作表。|
| [next_row](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/next_row/#) |获取要保存的下一行。|
| [start_row](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) |开始保存一行数据。|
| [next_cell](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/next_cell/#) |获取下一个要保存的单元格。|
| [start_cell](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) |开始保存一个单元格的数据。|
| [is_gather_string](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/is_gather_string/#) |检查cell当前的字符串值是否需要聚集到全局池中。|



### 评论

通过该模式保存工作簿时，保存工作簿中的每个工作表时都会检查[`LightCellsDataProvider.start_sheet`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_sheet)。
对于一张工作表，如果 [`LightCellsDataProvider.start_sheet`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_sheet) 给出 true，则要保存该工作表的行/单元格的所有数据和属性
将由该接口的实现提供。
首先，将调用 [`LightCellsDataProvider.next_row`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/next_row) 来获取要保存的下一行索引。
如果返回有效的行索引（行索引必须按升序排列才能保存行），
那么 [`LightCellsDataProvider.start_row`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_row) 将提供一个代表该行的 Row 对象，供实现设置其属性。
对于一行，将首先检查 [`LightCellsDataProvider.next_cell`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/next_cell)。
如果返回有效的列索引（当前行的所有单元格的列索引必须按升序排列），
那么 [`LightCellsDataProvider.start_cell`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_cell) 将提供代表该单元格的 Cell 对象来实现设置其数据和属性。
[`LightCellsDataProvider.start_cell`](/cells/python-net/zh/aspose.cells/lightcellsdataprovider/start_cell) 之后，单元格将直接保存到生成的电子表格文件中。
然后将检查并处理下一个单元格。


请注意，用户应该只更新相应方法提供的当前 Row/Cell 对象的值和属性。
由于单元数据以流方式写入结果文件，因此大多数其他对象可能已被写入
到结果文件中，或者已经为它们收集并写入了一些全局数据。所以当用户更新其他对象时
在保存单元格数据时，这些操作可能无法影响已保存的数据。或者更糟糕的是，这些操作可能
导致结果文件中保存的数据不一致，最终导致文件损坏。
因此，对于所有其他对象，例如形状、列宽和样式、条件格式等，
请不要在此实现的任何方法中操作它们。
相反，请在调用工作簿的“保存”方法之前管理它们并将它们调整到最终状态。

### 也可以看看
* 模块[`aspose.cells`](..)
