---
title: add method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.pivot/pivottablecollection/add/
is_root: false
---

## add {#str-str-str}

Adds a new PivotTable.


### Returns 


The new added cache index.


```python
def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | str | The data for the new PivotTable cache. |
| dest_cell_name | str | The cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |


## add {#aspose.cells.pivot.PivotTable-str-str}

Adds a new PivotTable based on another PivotTable.


### Returns 


The new added PivotTable index.


```python
def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable) | The source pivotTable. |
| dest_cell_name | str | The cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |


## add {#str-str-str-bool}

Adds a new PivotTable.


### Returns 


The new added cache index.


```python
def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | str | The data for the new PivotTable cache. |
| dest_cell_name | str | The cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |
| use_same_source | bool | Indicates whether using same data source when another existing pivot table has used this data source.<br/>If the property is true, it will save memory. |


## add {#str-int-int-str}

Adds a new PivotTable.


### Returns 


The new added cache index.


```python
def add(self, source_data, row, column, table_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | str | The data cell range for the new PivotTable.Example : Sheet1!A1:C8 |
| row | int | Row index of the cell in the upper-left corner of the PivotTable report's destination range. |
| column | int | Column index of the cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |


## add {#aspose.cells.pivot.PivotTable-int-int-str}

Adds a new PivotTable based on another PivotTable.


### Returns 


The new added PivotTable index.


```python
def add(self, pivot_table, row, column, table_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable) | The source pivotTable. |
| row | int | Row index of the cell in the upper-left corner of the PivotTable report's destination range. |
| column | int | Column index of the cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |


## add {#str-int-int-str-bool}

Adds a new PivotTable.


### Returns 


The new added cache index.


```python
def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | str | The data cell range for the new PivotTable.Example : Sheet1!A1:C8 |
| row | int | Row index of the cell in the upper-left corner of the PivotTable report's destination range. |
| column | int | Column index of the cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |
| use_same_source | bool | Indicates whether using same data source when another existing pivot table has used this data source.<br/>If the property is true, it will save memory. |


## add {#str-str-str-bool-bool}

Adds a new PivotTable.


### Returns 


The new added cache index.


```python
def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | str | The data cell range for the new PivotTable.Example : Sheet1!A1:C8 |
| cell | str | The cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |
| use_same_source | bool | Indicates whether using same data source when another existing pivot table has used this data source.<br/>If the property is true, it will save memory. |
| is_xls_classic | bool | Indicates whether add classic pivot table of Excel 97-2003. |


## add {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}

Adds a new PivotTable Object to the collection with multiple consolidation ranges as data source.


### Returns 


The new added PivotTable index.


```python
def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | list | The multiple consolidation ranges,such as {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Whether auto create a single page field.<br/>If true,the following param pageFields will be ignored. |
| page_fields | [`PivotPageFields`](/cells/python-net/aspose.cells.pivot/pivotpagefields) | The pivot page field items. |
| dest_cell_name | str | destCellName The name of the new PivotTable report. |
| table_name | str | the name of the new PivotTable report. |


## add {#str-int-int-str-bool-bool}

Adds a new PivotTable.


### Returns 


The new added cache index.


```python
def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | str | The data cell range for the new PivotTable.Example : Sheet1!A1:C8 |
| row | int | Row index of the cell in the upper-left corner of the PivotTable report's destination range. |
| column | int | Column index of the cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |
| use_same_source | bool | Indicates whether using same data source when another existing pivot table has used this data source.<br/>If the property is true, it will save memory. |
| is_xls_classic | bool | Indicates whether add classic pivot table of Excel 97-2003. |


## add {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}

Adds a new PivotTable Object to the collection with multiple consolidation ranges as data source.


### Returns 


The new added PivotTable index.


```python
def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_data | list | The multiple consolidation ranges,such as {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Whether auto create a single page field.<br/>If true,the following param pageFields will be ignored |
| page_fields | [`PivotPageFields`](/cells/python-net/aspose.cells.pivot/pivotpagefields) | The pivot page field items. |
| row | int | Row index of the cell in the upper-left corner of the PivotTable report's destination range. |
| column | int | Column index of the cell in the upper-left corner of the PivotTable report's destination range. |
| table_name | str | The name of the new PivotTable report. |



### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotTableCollection`](/cells/python-net/aspose.cells.pivot/pivottablecollection)
