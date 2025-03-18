---
title: delete_blank_rows method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 210
url: /aspose.cells/cells/delete_blank_rows/
is_root: false
---

## delete_blank_rows(self) {#}

Delete all blank rows which do not contain any data or other object.



```python

def delete_blank_rows(self):
    ...
```




## delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}

Delete all blank rows which do not contain any data or some special objects such as visible comment, pivot table.



```python

def delete_blank_rows(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/aspose.cells/deleteoptions) | The options of deleting range. |
### Remarks

For blank rows that will be deleted, it is not only required that [`Row.is_blank`](/cells/python-net/aspose.cells/row#is_blank) should be true,
but also there should be no visible comment defined for any cell in those rows,
and no pivot table whose range intersects with them.


### See Also
* module [`aspose.cells`](../../)
* class [`Cells`](/cells/python-net/aspose.cells/cells)
