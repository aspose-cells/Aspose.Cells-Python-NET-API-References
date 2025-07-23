---
title: group_by方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 140
url: /zh/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
自动将字段与内部字段分组



```python

def group_by(self, interval, new_field):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| interval | float |团体内部。<br/>如果为零，则将分配自动值，|
| new_field | bool |指示是否向数据透视表添加新字段。|


##  group_by(self, custom_group_items, new_field) {#list-bool}
自定义分组字段。


### 返回

False 表示该字段不能按日期时间分组。


```python

def group_by(self, custom_group_items, new_field):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| custom_group_items | list |自定义组项目。|
| new_field | bool |指示是否向数据透视表添加新字段|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
按编号对文件进行分组。


### 返回

False 表示该字段不能按日期时间分组。


```python

def group_by(self, start, end, interval, new_field):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| start | float |起始值|
| end | float |价值的终结|
| interval | float |间隔|
| new_field | bool |指示是否向数据透视表添加新字段|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
按日期组类型对文件进行分组。


### 返回

False 表示该字段不能按日期时间分组。


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| start | DateTime |开始日期时间|
| end | DateTime |日期时间的结束|
| groups | list |组类型|
| interval | float |间隔|
| first_as_new_field | bool |指示是否向数据透视表添加新字段。<br/>仅适用于第一组项目。|



### 也可以看看
* 模块[`aspose.cells.pivot`](../../)
* 类 [`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield)
