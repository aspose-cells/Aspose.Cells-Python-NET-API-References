﻿---
title: TxtValueQuoteType enumeration
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 2660
url: /aspose.cells/txtvaluequotetype/
is_root: false
---

## TxtValueQuoteType enumeration

Specifies the type of using quotation marks for values in text format files.



The TxtValueQuoteType type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NORMAL | All values that contain special characters such as quotation mark, separator character will be quoted.<br/>Same with the behavior of ms excel for exporting text file. |
| ALWAYS | All values will be quoted always. |
| MINIMUM | Only quote values when needed. Such as, if one value contains quotation mark but the quotation mark is not at the begin of this value, this value will not be quoted. |
| NEVER | All values will not be quoted. The exported text file with this type may not be read back correctly because the needed quotation marks being absent. |



### See Also
* module [`aspose.cells`](..)
