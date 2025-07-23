---
title: process方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process（，选项）{#aspose.cells.lowcode.LowCodeSplitOptions}
将电子表格文件拆分为多个部分。



```python

@staticmethod
def process(options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesplitoptions) |拆分电子表格的选项|


##  process（，模板文件，结果文件）{#str-str}
将给定的模板文件拆分为多个部分。



```python

@staticmethod
def process(template_file, result_file):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| template_file | str |待拆分的模板文件|
| result_file | str |生成的文件（名称模式）|
### 注意事项

输出文件将由指定的结果文件构建
附加工作表和拆分部分的序列号。
例如，如果指定的输出文件是Split.xlsx，则生成的
文件将是 Split_0_0.xlsx、Split_0_1.xlsx、...、Split_1_0.xlsx、...


### 也可以看看
* 模块[`aspose.cells.lowcode`](../../)
* 类 [`SpreadsheetSplitter`](/cells/python-net/zh/aspose.cells.lowcode/spreadsheetsplitter)
