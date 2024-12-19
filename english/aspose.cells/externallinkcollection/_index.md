---
title: ExternalLinkCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 640
url: /aspose.cells/externallinkcollection/
is_root: false
---

## ExternalLinkCollection class

Represents external links collection in a workbook.



The ExternalLinkCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [count](/cells/python-net/aspose.cells/externallinkcollection/count) | Gets the number of elements actually contained in the collection. |



Gets the [`ExternalLink`](/cells/python-net/aspose.cells/externallink) element at the specified index.
### Indexer
| Name | Description |
| :- | :- |
| [index] | The zero based index of the element. |


### Methods
| Method | Description |
| :- | :- |
| [add](/cells/python-net/aspose.cells/externallinkcollection/add/#str-list) | Adds an external link. |
| [add](/cells/python-net/aspose.cells/externallinkcollection/add/#aspose.cells.DirectoryType-str-list) | Add an external link . |
| [clear](/cells/python-net/aspose.cells/externallinkcollection/clear/#) | Removes all external links. |
| [clear](/cells/python-net/aspose.cells/externallinkcollection/clear/#bool) | Removes all external links. |
| [remove_at](/cells/python-net/aspose.cells/externallinkcollection/remove_at/#int) | Removes the specified external link from the workbook. |
| [remove_at](/cells/python-net/aspose.cells/externallinkcollection/remove_at/#int-bool) | Removes the specified external link from the workbook. |



### Example 


```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

### See Also
* module [`aspose.cells`](..)
* class [`ExternalLink`](/cells/python-net/aspose.cells/externallink)
