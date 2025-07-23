---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/hyperlinkcollection/add/
is_root: false
---
##  add(self, cell_name, total_rows, total_columns, address) {#str-int-int-str}
将超链接添加到指定单元格或单元格区域。


### 返回

[`Hyperlink`](/cells/python-net/zh/aspose.cells/hyperlink) 对象索引。


```python

def add(self, cell_name, total_rows, total_columns, address):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_name | str | Cell 名称。|
| total_rows | int |此超链接范围内的行数。|
| total_columns | int |此超链接范围的列数。|
| address | str |超链接的地址。|


##  add(self, first_row, first_column, total_rows, total_columns, address) {#int-int-int-int-str}
将超链接添加到指定单元格或单元格区域。


### 返回

[`Hyperlink`](/cells/python-net/zh/aspose.cells/hyperlink) 对象索引。


```python

def add(self, first_row, first_column, total_rows, total_columns, address):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| first_row | int |超链接范围的第一行。|
| first_column | int |超链接范围的第一列。|
| total_rows | int |此超链接范围内的行数。|
| total_columns | int |此超链接范围的列数。|
| address | str |超链接的地址。|

### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
excel = Workbook()
worksheet = excel.worksheets[0]
worksheet.hyperlinks.add("A4", 1, 1, "http://www.aspose.com")
worksheet.hyperlinks.add("A5", 1, 1, "c:\\book1.xls")

```


##  add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip) {#str-str-str-str-str}
将超链接添加到指定单元格或单元格区域。


### 返回

[`Hyperlink`](/cells/python-net/zh/aspose.cells/hyperlink) 对象索引。


```python

def add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| start_cell_name | str |范围的左上角单元格。|
| end_cell_name | str |范围的右下角单元格。|
| address | str |超链接的地址。|
| text_to_display | str |为指定超链接显示的文本。|
| screen_tip | str |指定超链接的屏幕提示文本。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Hyperlink`](/cells/python-net/zh/aspose.cells/hyperlink)
* 类 [`HyperlinkCollection`](/cells/python-net/zh/aspose.cells/hyperlinkcollection)
