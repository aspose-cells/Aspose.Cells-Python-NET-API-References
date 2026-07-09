---
title: HyperlinkLoadMode enumeration
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 2360
url: /aspose.cells/hyperlinkloadmode/
is_root: false
---

## HyperlinkLoadMode enumeration

Specifies how hyperlinks are handled when loading HTML.



The HyperlinkLoadMode type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NORMAL | Only the first hyperlink in a cell is loaded, subsequent ones are ignored. |
| ALLOW_MULTIPLE | All hyperlinks in a cell are added to [`Worksheet.hyperlinks`](/cells/python-net/aspose.cells/worksheet#hyperlinks).<br/>Note that MS Excel itself supports only one hyperlink per cell,<br/>so this option may produce files that Excel cannot fully render. |



### See Also
* module [`aspose.cells`](..)
