---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
添加一个新的数据透视表。


### 返回

新添加的缓存索引。


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | str |新数据透视表缓存的数据。|
| dest_cell_name | str |数据透视表目标范围左上角的单元格。|
| table_name | str |新数据透视表的名称。|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
根据另一个数据透视表添加一个新的数据透视表。


### 返回

新添加的数据透视表索引。


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/zh/aspose.cells.pivot/pivottable) |源数据透视表。|
| dest_cell_name | str |数据透视表目标范围左上角的单元格。|
| table_name | str |新数据透视表的名称。|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
添加一个新的数据透视表。


### 返回

新添加的缓存索引。


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | str |新数据透视表缓存的数据。|
| dest_cell_name | str |数据透视表目标范围左上角的单元格。|
| table_name | str |新数据透视表的名称。|
| use_same_source | bool |指示当另一个现有数据透视表已使用该数据源时是否使用相同的数据源。<br/>如果该属性为真，它将节省内存。|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
添加一个新的数据透视表。


### 返回

新添加的缓存索引。


```python

def add(self, source_data, row, column, table_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | str |新数据透视表的数据单元格范围。示例：Sheet1！A1：C8|
| row | int |数据透视表目标范围左上角单元格的行索引。|
| column | int |数据透视表目标范围左上角单元格的列索引。|
| table_name | str |新数据透视表的名称。|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
根据另一个数据透视表添加一个新的数据透视表。


### 返回

新添加的数据透视表索引。


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/zh/aspose.cells.pivot/pivottable) |源数据透视表。|
| row | int |数据透视表目标范围左上角单元格的行索引。|
| column | int |数据透视表目标范围左上角单元格的列索引。|
| table_name | str |新数据透视表的名称。|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
添加一个新的数据透视表。


### 返回

新添加的缓存索引。


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | str |新数据透视表的数据单元格范围。示例：Sheet1！A1：C8|
| row | int |数据透视表目标范围左上角单元格的行索引。|
| column | int |数据透视表目标范围左上角单元格的列索引。|
| table_name | str |新数据透视表的名称。|
| use_same_source | bool |指示当另一个现有数据透视表已使用该数据源时是否使用相同的数据源。<br/>如果该属性为真，它将节省内存。|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
添加一个新的数据透视表。


### 返回

新添加的缓存索引。


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | str |新数据透视表的数据单元格范围。示例：Sheet1！A1：C8|
| cell | str |数据透视表目标范围左上角的单元格。|
| table_name | str |新数据透视表的名称。|
| use_same_source | bool |指示当另一个现有数据透视表已使用该数据源时是否使用相同的数据源。<br/>如果该属性为真，它将节省内存。|
| is_xls_classic | bool |指示是否添加 Excel 97-2003 的经典数据透视表。|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
将新的数据透视表对象添加到具有多个合并范围作为数据源的集合中。


### 返回

新添加的数据透视表索引。


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | list |多个合并区域，例如 {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool |是否自动创建单页字段。<br/>如果为真，则以下参数 pageFields 将被忽略。|
| page_fields | [`PivotPageFields`](/cells/python-net/zh/aspose.cells.pivot/pivotpagefields) |数据透视页字段项。|
| dest_cell_name | str | destCellName 新数据透视表的名称。|
| table_name | str |新数据透视表的名称。|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
添加一个新的数据透视表。


### 返回

新添加的缓存索引。


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | str |新数据透视表的数据单元格范围。示例：Sheet1！A1：C8|
| row | int |数据透视表目标范围左上角单元格的行索引。|
| column | int |数据透视表目标范围左上角单元格的列索引。|
| table_name | str |新数据透视表的名称。|
| use_same_source | bool |指示当另一个现有数据透视表已使用该数据源时是否使用相同的数据源。<br/>如果该属性为真，它将节省内存。|
| is_xls_classic | bool |指示是否添加 Excel 97-2003 的经典数据透视表。|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
将新的数据透视表对象添加到具有多个合并范围作为数据源的集合中。


### 返回

新添加的数据透视表索引。


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_data | list |多个合并区域，例如 {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool |是否自动创建单页字段。<br/>如果为 true，则以下参数 pageFields 将被忽略|
| page_fields | [`PivotPageFields`](/cells/python-net/zh/aspose.cells.pivot/pivotpagefields) |数据透视页字段项。|
| row | int |数据透视表目标范围左上角单元格的行索引。|
| column | int |数据透视表目标范围左上角单元格的列索引。|
| table_name | str |新数据透视表的名称。|



### 也可以看看
* 模块[`aspose.cells.pivot`](../../)
* 类 [`PivotTableCollection`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection)
