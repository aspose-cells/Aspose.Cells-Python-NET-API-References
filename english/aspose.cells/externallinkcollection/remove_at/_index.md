---
title: remove_at method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells/externallinkcollection/remove_at/
is_root: false
---

## remove_at(self, index) {#int}

Removes the specified external link from the workbook.



```python

def remove_at(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | the index of the external link to be removed. |
### Remarks

When removing the external link, all formulas that reference to it will be removed too because
the references become invalid.

## remove_at(self, index, update_references_as_local) {#int-bool}

Removes the specified external link from the workbook.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | the index of the external link to be removed. |
| update_references_as_local | bool | Whether update all references of given external link to reference of current workbook itself.<br/>Check [`ExternalLinkCollection.clear`](/cells/python-net/aspose.cells/externallinkcollection/clear) to get more details about this parameter. |



### See Also
* module [`aspose.cells`](../../)
* class [`ExternalLinkCollection`](/cells/python-net/aspose.cells/externallinkcollection)
