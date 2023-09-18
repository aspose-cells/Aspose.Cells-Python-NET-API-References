﻿---
title: HtmlCrossType enumeration
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 2220
url: /aspose.cells/htmlcrosstype/
is_root: false
---

## HtmlCrossType enumeration

Represents five types of html cross string.



The HtmlCrossType type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| DEFAULT | Display like MS Excel,depends on the next cell. <br/>If the next cell is null,the string will cross,or it will be truncated |
| MS_EXPORT | Display the string like MS Excel exporting html. |
| CROSS | Display HTML cross string, this performance for creating large html files will be more than ten times faster than setting the value to Default or FitToCell. |
| CROSS_HIDE_RIGHT | Display HTML cross string and hide the right string when the texts overlap. |
| FIT_TO_CELL | Only displaying the string within the width of cell. |



### See Also
* module [`aspose.cells`](..)
