---
title: add_active_x_control Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
Erstellt ein ActiveX-Steuerelement.


###  Kehrt zurück




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | Der Typ des Steuerelements.|
| top_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Form von ihrer linken Zeile in Pixeleinheiten dar.|
| left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der Form von ihrer linken Spalte in Pixeleinheiten dar.|
| width | int | Stellt die Breite der Form in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Form in Pixeleinheiten dar.|

###  Beispiel

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
