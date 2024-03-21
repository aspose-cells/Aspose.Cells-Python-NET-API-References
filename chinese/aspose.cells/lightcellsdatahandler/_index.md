---
title: LightCellsDataHandler类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1030
url: /zh/aspose.cells/lightcellsdatahandler/
is_root: false
---
## LightCellsDataHandler类
表示用于在轻量级模式下读取大型电子表格文件的单元格数据处理程序。



LightCellsDataHandler 类型公开以下成员：

### 方法
|方法|描述|
| :- | :- |
| [start_sheet](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) |开始处理工作表。|
| [start_row](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_row/#int) |准备处理一行。|
| [process_row](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) |开始处理一行。|
| [start_cell](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_cell/#int) |准备处理细胞。|
| [process_cell](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) |开始处理一个细胞。|



### 评论

通过该模式读取工作簿时，读取工作簿中的每个工作表时都会检查[`LightCellsDataHandler.start_sheet`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_sheet)。
对于一张工作表，如果 [`LightCellsDataHandler.start_sheet`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_sheet) 给出 true，则将检查该工作表的行/单元格的所有数据和属性
并由该接口的实现进行处理。对于每一行，都会调用[`LightCellsDataHandler.start_row`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_row)来检查是否需要处理。
如果需要处理一行，则首先读取该行的属性，用户可以通过[`LightCellsDataHandler.process_row`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/process_row)访问其属性。
如果行的单元格也需要处理，那么 [`LightCellsDataHandler.process_row`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/process_row) 应该返回 true，然后 [`LightCellsDataHandler.start_cell`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/start_cell) 将是
调用该行中的每个现有单元格来检查是否有一个单元格需要处理。如果需要处理一个细胞，
然后通过该接口的实现将调用[`LightCellsDataHandler.process_cell`](/cells/python-net/zh/aspose.cells/lightcellsdatahandler/process_cell)来处理cell。


请注意，用户只能对相应方法提供的当前 Row/Cell 对象的值和属性进行操作。
由于单元格数据是以流方式从模板文件中读取的，因此大多数其他对象可能会在以后重置/更新
加载单元格数据后。所以当用户在这个实现中操作其他对象时，
这些操作可能无法影响工作簿中现有的对象。或者更糟糕的是，这些操作可能
导致工作簿中的数据不一致，然后导致以后出现意外问题或异常。
因此，对于所有其他对象，例如形状、列宽和样式、条件格式等，
请不要在此实现的任何方法中操作它们。
相反，请在构建工作簿后管理它们。

### 也可以看看
* 模块[`aspose.cells`](..)
