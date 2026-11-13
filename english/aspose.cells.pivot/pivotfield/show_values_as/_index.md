---
title: show_values_as method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 270
url: /aspose.cells.pivot/pivotfield/show_values_as/
is_root: false
---

## show_values_as(self, show_values_as_type, base_field, base_item) {#aspose.cells.pivot.PivotShowValuesAsType-int-int}

Sets the "Show Values As" calculation for this pivot field.



```python

def show_values_as(self, show_values_as_type, base_field, base_item):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| show_values_as_type | aspose.cells.pivot.PivotShowValuesAsType | Type of the "Show Values As" calculation. |
| base_field | int | Index of the base field used for the calculation. |
| base_item | int | Index of the base item for the calculation.<br/>Use [`PivotShowValuesSetting.PreviousPivotItem`](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting) (-1) for the preceding item,<br/>[`PivotShowValuesSetting.NextPivotItem`](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting) (-2) for the succeeding item;<br/>non‑negative values denote the ordinal index of a specific pivot item. |
### Remarks

Only for data field.

## show_values_as(self, show_values_as_type, base_field, base_item) {#aspose.cells.pivot.PivotShowValuesAsType-System.String-System.String}

Configures the "Show Values As" calculation for this data field.



```python

def show_values_as(self, show_values_as_type, base_field, base_item):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| show_values_as_type | aspose.cells.pivot.PivotShowValuesAsType | The calculation type for Show Values As. |
| base_field | System.String | The name of the base field used in the calculation. |
| base_item | System.String | Caption of a regular pivot item.<br/>Also accepts reserved literal keywords: `(previous)` for the previous item, `(next)` for the next item.<br/>Pass `null` if the selected calculation type does not require a base item. |


## show_values_as(self, display_format, base_field, base_item_position_type, base_item) {#aspose.cells.pivot.PivotFieldDataDisplayFormat-int-aspose.cells.pivot.PivotItemPositionType-int}

Shows values of data field as different display format when the ShowDataAs calculation is in use.



```python

def show_values_as(self, display_format, base_field, base_item_position_type, base_item):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| display_format | aspose.cells.pivot.PivotFieldDataDisplayFormat | The data display format type. |
| base_field | int | The index to the field which ShowDataAs calculation bases on. |
| base_item_position_type | aspose.cells.pivot.PivotItemPositionType | The position type of base iteam. |
| base_item | int | The index to the base item which ShowDataAs calculation bases on.<br/>Only works when baseItemPositionType is custom. |
### Remarks

NOTE: This property is now obsolete. Instead, 
please use PivotField.ShowValuesAs(PivotShowValuesAsType,int,int) method instead.
This method will be removed 12 months later since November 2026.
Aspose apologizes for any inconvenience you may have experienced.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
