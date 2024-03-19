---
title: html_note proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 150
url: /it/aspose.cells/comment/html_note/
is_root: false
---
##  html_note proprietà

Ottiene e imposta la stringa html che contiene i dati e alcuni formati in questo commento.

###  Osservazioni

Se si tratta di un commento in thread, la nota non potrà essere modificata, altrimenti MS Excel non potrebbe elaborarla come commento in thread.

###  Esempio

```python

comment1.html_note = "<Font Style='FONT-FAMILY: Calibri;FONT-SIZE: 11pt;COLOR: #0000ff;TEXT-ALIGN: left;'>This is a <b>test</b>.</Font>"

```
###  Definizione:
```python
@property
def html_note(self):
    ...
@html_note.setter
def html_note(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Comment`](/cells/python-net/it/aspose.cells/comment)
