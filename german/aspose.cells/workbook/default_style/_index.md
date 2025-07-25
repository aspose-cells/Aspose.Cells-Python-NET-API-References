---
title: default_style Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 580
url: /de/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style Eigentum

Ruft das Standardobjekt [`Style`](/cells/python-net/de/aspose.cells/style) der Arbeitsmappe ab oder legt es fest.

###  Bemerkungen

Die DefaultStyle-Eigenschaft ist nützlich, um einen Stil für die gesamte Arbeitsmappe zu implementieren.

###  Beispiel

Der folgende Code erstellt und instanziiert eine neue Arbeitsmappe und legt für sie den Standardwert [`Style`](/cells/python-net/de/aspose.cells/style) fest.

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
###  Definition:
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Style`](/cells/python-net/de/aspose.cells/style)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
