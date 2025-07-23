---
title: auto_size fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells/comment/auto_size/
is_root: false
---
##  auto_size fastighet

Anger om kommentarens storlek justeras automatiskt enligt dess innehåll.
Obs: I vissa specialfall (t.ex. i Mac-miljö) kanske den här inställningen inte träder i kraft. Om inställningen inte träder i kraft, ersätt den med FitToTextSize().

###  Exempel

```python

if notcomment1.auto_size:
    # The size of the comment varies with the content
    comment1.auto_size = True

```
###  Definition:
```python
@property
def auto_size(self):
    ...
@auto_size.setter
def auto_size(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Comment`](/cells/python-net/sv/aspose.cells/comment)
