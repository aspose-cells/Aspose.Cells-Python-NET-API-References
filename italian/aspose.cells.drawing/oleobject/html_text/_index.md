---
title: html_text proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 570
url: /it/aspose.cells.drawing/oleobject/html_text/
is_root: false
---
##  html_text proprietà

Ottiene e imposta la stringa html che contiene dati e alcuni formati in questa casella di testo.

###  Esempio

```python

html = shape.html_text
if html == null  or html == "":
    shape.html_text = "<Font Style='FONT-FAMILY: Calibri;FONT-SIZE: 11pt;COLOR: #0000ff;TEXT-ALIGN: left;'>This is a <b>test</b>.</Font>"

```
###  Definizione:
```python
@property
def html_text(self):
    ...
@html_text.setter
def html_text(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`OleObject`](/cells/python-net/it/aspose.cells.drawing/oleobject)
