---
title: update_linked_data_source method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 440
url: /aspose.cells/workbook/update_linked_data_source/
is_root: false
---

## update_linked_data_source(self, external_workbooks) {#list}

If this workbook contains external links to other data source,
Aspose.Cells will attempt to retrieve the latest data from give sources.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| external_workbooks | list | Workbooks that will be used to update data of external links referenced by this workbook.<br/>The match of those workbooks with external links is determined by [`Workbook.file_name`](/cells/python-net/aspose.cells/workbook#file_name)<br/>and [`ExternalLink.data_source`](/cells/python-net/aspose.cells/externallink#data_source). So please make sure [`Workbook.file_name`](/cells/python-net/aspose.cells/workbook#file_name) has<br/>been specified with the proper value for every workbook so they can be linked to corresponding external link. |
### Remarks

If corresponding external link cannot be found for one workbook, then this workbook will be ignored.
So when you set a formula later with one new external link which you intend to make the ignored workbook
be linked to it, the link cannot be performed until you call this this method again with those workbooks.


### See Also
* module [`aspose.cells`](../../)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
