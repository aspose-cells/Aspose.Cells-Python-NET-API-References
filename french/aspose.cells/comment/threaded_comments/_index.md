---
title: threaded_comments propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 230
url: /fr/aspose.cells/comment/threaded_comments/
is_root: false
---
##  threaded_comments propriété

Obtient la liste des commentaires en fil de discussion ;

###  Exemple

```python

threadedComments = comment1.threaded_comments
for i in range(len(threadedComments)):
    tc = threadedComments[i]
    note = tc.notes

```
###  Définition:
```python
@property
def threaded_comments(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Comment`](/cells/python-net/fr/aspose.cells/comment)
* classe [`ThreadedCommentCollection`](/cells/python-net/fr/aspose.cells/threadedcommentcollection)
