---
title: is_height_matched Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 190
url: /de/aspose.cells/row/is_height_matched/
is_root: false
---
##  is_height_matched Eigentum

Gibt an, ob die Zeilenhöhe mit der aktuellen Standardschriftarteinstellung der Arbeitsmappe übereinstimmt.
„True“ dieser Eigenschaft bedeutet auch, dass die Zeilenhöhe „automatisch“ ist, ohne dass vom Benutzer ein benutzerdefinierter Höhenwert festgelegt wird.

###  Bemerkungen

Wenn diese Eigenschaft wahr ist und sich der Inhalt dieser Zeile ändert,
Im Allgemeinen muss die Zeilenhöhe neu berechnet werden (z. B. bis [`Worksheet.auto_fit_rows`](/cells/python-net/de/aspose.cells/worksheet/auto_fit_rows)).
um das gleiche Ergebnis wie in MS Excel zu erhalten, wenn Sie die darin enthaltene Arbeitsmappe öffnen.
###  Definition:
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Row`](/cells/python-net/de/aspose.cells/row)
