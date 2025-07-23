---
title: major_unit_scale Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 320
url: /de/aspose.cells.charts/axis/major_unit_scale/
is_root: false
---
##  major_unit_scale Eigentum

Stellt die Haupteinheitenskala für die Kategorieachse dar.

###  Beispiel

```python
from aspose.cells.charts import CategoryType, TimeUnit

chart.category_axis.category_type = CategoryType.TIME_SCALE
chart.category_axis.major_unit_scale = TimeUnit.MONTHS
chart.category_axis.major_unit = 2.0

```
###  Definition:
```python
@property
def major_unit_scale(self):
    ...
@major_unit_scale.setter
def major_unit_scale(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`Axis`](/cells/python-net/de/aspose.cells.charts/axis)
* Klasse [`TimeUnit`](/cells/python-net/de/aspose.cells.charts/timeunit)
