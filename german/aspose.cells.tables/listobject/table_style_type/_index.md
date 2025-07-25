---
title: table_style_type Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 300
url: /de/aspose.cells.tables/listobject/table_style_type/
is_root: false
---
##  table_style_type Eigentum

Ruft den integrierten Tabellenstil ab.

###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.tables import TableStyleType

workbook = Workbook("Book1.xlsx")
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.table_style_type = TableStyleType.TABLE_STYLE_DARK2
workbook.save("TableStyle.xlsx")

```
###  Definition:
```python
@property
def table_style_type(self):
    ...
@table_style_type.setter
def table_style_type(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.tables`](../../)
* Klasse [`ListObject`](/cells/python-net/de/aspose.cells.tables/listobject)
* Klasse [`TableStyleType`](/cells/python-net/de/aspose.cells.tables/tablestyletype)
