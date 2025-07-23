---
title: auto_size Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells/comment/auto_size/
is_root: false
---
##  auto_size Eigentum

Gibt an, ob die Größe des Kommentars automatisch an seinen Inhalt angepasst wird.
Hinweis: In einigen Sonderfällen (z. B. in einer Mac-Umgebung) ist diese Einstellung möglicherweise nicht wirksam. Falls diese Einstellung nicht wirksam ist, ersetzen Sie sie bitte durch FitToTextSize().

###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Comment`](/cells/python-net/de/aspose.cells/comment)
