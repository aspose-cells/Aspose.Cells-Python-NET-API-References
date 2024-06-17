﻿---
title: get_threaded_comments method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---

## get_threaded_comments {#str}

Gets the threaded comments by cell name.


### Returns 





```python
def get_threaded_comments(self, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cell_name | str | The name of the cell. |

### Example 


```python

threadedComments2 = comments.get_threaded_comments("B2")
for i in range(len(threadedComments2)):
    tc = threadedComments2[i]
    note = tc.notes

```


## get_threaded_comments {#int-int}

Gets the threaded comments by row and column index.


### Returns 





```python
def get_threaded_comments(self, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row | int | The row index. |
| column | int | The column index. |

### Example 


```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



### See Also
* module [`aspose.cells`](../../)
* class [`CommentCollection`](/cells/python-net/aspose.cells/commentcollection)
