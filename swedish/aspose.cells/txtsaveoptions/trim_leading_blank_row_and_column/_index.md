---
title: trim_leading_blank_row_and_column fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 230
url: /sv/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column fastighet

Anger om inledande tomma rader och kolumner ska trimmas på samma sätt som i MS Excel.
Standardvärdet är sant.

###  Anmärkningar

Samma sak gäller i MS Excel, en rad/kolumn tas inte som tom om den har en anpassad stil,
även om den inte innehåller någon mobildata.
När du sparar med LightCells-läge har det här alternativet ingen effekt.
Användaren bör kontrollera utgångsområdet genom implementeringen av [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/sv/aspose.cells/txtsaveoptions).
eller genom att specificera [`TxtSaveOptions.export_area`](/cells/python-net/sv/aspose.cells/txtsaveoptions#export_area)
###  Definition:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`TxtSaveOptions`](/cells/python-net/sv/aspose.cells/txtsaveoptions)
