---
title: add_condition method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells/formatconditioncollection/add_condition/
is_root: false
---

## add_condition(self, type) {#aspose.cells.FormatConditionType}

Add a format condition.


### Returns 


Formatting condition object index;


```python

def add_condition(self, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | aspose.cells.FormatConditionType | Format condition type. |


## add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-System.String-System.String}

Adds a formatting condition.


### Returns 


Formatting condition object index;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | aspose.cells.FormatConditionType | The type of format condition. |
| operator_type | aspose.cells.OperatorType | The operator type |
| formula1 | System.String | The value or expression associated with conditional formatting.<br/>If the input value starts with '=', then it will be taken as formula.<br/>Otherwise it will be taken as plain value(text, number, bool).<br/>For text value that starts with '=', user may input it as formula in format: "=\"=...\"". |
| formula2 | System.String | The value or expression associated with conditional formatting.<br/>The input format is same with formula1 |



### See Also
* module [`aspose.cells`](../../)
* class [`FormatConditionCollection`](/cells/python-net/aspose.cells/formatconditioncollection)
