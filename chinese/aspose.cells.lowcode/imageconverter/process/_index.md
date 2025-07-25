---
title: process方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process（，模板文件，结果文件）{#str-str}
将模板文件转换为图像。



```python

@staticmethod
def process(template_file, result_file):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| template_file | str |要转换为图像的模板文件。|
| result_file | str |生成图像的结果文件（名称模式）。|
### 注意事项

输出文件将从指定的结果文件构建
通过附加工作表和拆分部分的序列号。
例如，如果指定的输出文件是Image.png，那么生成的图像
文件将是 Image_0_0.png、Image_0_1.png、...、Image_1_0.png、...

## process（，加载选项，保存选项）{#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
将模板文件转换为图像



```python

@staticmethod
def process(load_options, save_options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodeloadoptions) |输入和加载选项|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions) |输出和保存选项|
### 注意事项

当转换为支持多页格式的图像（例如 tiff）时，
指定的[`LowCodeSaveOptions.output_file`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions#output_file)
或 [`LowCodeSaveOptions.output_stream`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions#output_stream) 将直接用于结果图像。


对于其他类型的图像，如果保存选项已指定 Stream 作为输出，
那么所有结果图像将保存到同一个流中。
否则，输出文件将从指定的输出文件构建
通过附加工作表和拆分部分的序列号来保存选项。
例如，如果指定的输出文件是Image.png，那么生成的图像
文件将是 Image_0_0.png、Image_0_1.png、...、Image_1_0.png、...

##  process（，load_options，save_options，提供者）{#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



### 也可以看看
* 模块[`aspose.cells.lowcode`](../../)
* 类 [`ImageConverter`](/cells/python-net/zh/aspose.cells.lowcode/imageconverter)
