---
title: process方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process（，load_options，save_options，提供者）{#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
使用指定的设置锁定电子表格文件。



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodeloadoptions) |输入和加载选项|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions) |输出和保存选项|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/zh/aspose.cells.lowcode/abstractlowcodeprotectionprovider) |实施提供保护设置|


## process（，模板文件，结果文件，打开密码，写入密码）{#str-str-str-str}
使用指定的设置锁定电子表格文件。



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| template_file | str |需要锁定的模板文件|
| result_file | str |生成的文件|
| open_password | str |文件加密的密码|
| write_password | str |修改电子表格的保护密码|


## process（，加载选项，保存选项，打开密码，写入密码）{#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
使用指定的设置锁定电子表格文件。



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodeloadoptions) |输入和加载选项|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions) |输出和保存选项|
| open_password | str |文件加密的密码|
| write_password | str |修改电子表格的保护密码|


##  process（，load_options，save_options，open_password，write_password，workbook_password，workbook_type）{#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
使用指定的设置锁定电子表格文件。



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodeloadoptions) |输入和加载选项|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptions) |输出和保存选项|
| open_password | str |文件加密的密码|
| write_password | str |修改电子表格的保护密码|
| workbook_password | str |保护工作簿的密码|
| workbook_type | [`ProtectionType`](/cells/python-net/zh/aspose.cells/protectiontype) |保护工作簿的保护类型|



### 也可以看看
* 模块[`aspose.cells.lowcode`](../../)
* 类 [`SpreadsheetLocker`](/cells/python-net/zh/aspose.cells.lowcode/spreadsheetlocker)
