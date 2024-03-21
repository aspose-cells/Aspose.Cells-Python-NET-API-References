---
title: to_printer方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells.rendering/workbookrender/to_printer/
is_root: false
---
##  to_printer {#str}
将工作簿渲染到打印机



```python
def to_printer(self, printer_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| printer_name | str |打印机的名称，例如：“Microsoft Office Document Image Writer”|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings}
将工作簿渲染到打印机



```python
def to_printer(self, printer_settings):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings |打印机的设置，例如打印机名称、双面打印|


##  to_printer {#str-str}
将工作簿渲染到打印机



```python
def to_printer(self, printer_name, job_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| printer_name | str |打印机的名称，例如：“Microsoft Office Document Image Writer”|
| job_name | str |设置打印作业名称|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings-str}
将工作簿渲染到打印机



```python
def to_printer(self, printer_settings, job_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings |打印机的设置，例如打印机名称、双面打印|
| job_name | str |设置打印作业名称|


##  to_printer {#str-int-int}
将工作簿渲染到打印机



```python
def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| printer_name | str |打印机的名称，例如：“Microsoft Office Document Image Writer”|
| print_page_index | int |要打印的第一页从 0 开始的索引，它必须在范围 [0, WorkbookRender.PageCount-1] 内|
| print_page_count | int |要打印的页数，它必须大于零|
### 评论

注意：此方法现已过时。
相反，请使用 ToPrinter(string PrinterName) 和 ImageOrPrintOptions.PageIndex, PageCount 来设置首页和要打印的页数。
该房产将于 2021 年 12 月起 12 个月后被移除。
Aspose 对于给您带来的任何不便，我们深表歉意。


### 也可以看看
* 模块[`aspose.cells.rendering`](../../)
* 类 [`WorkbookRender`](/cells/python-net/zh/aspose.cells.rendering/workbookrender)
