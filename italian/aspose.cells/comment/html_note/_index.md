---
title: html_note proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 150
url: /it/aspose.cells/comment/html_note/
is_root: false
---
##  html_note proprietà

Ottiene e imposta la stringa HTML che contiene dati e alcuni formati in questo commento.

###  Osservazioni

Se si tratta di un commento concatenato, la nota non potrà essere modificata, altrimenti MS Excel non potrà elaborarla come commento concatenato.

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
