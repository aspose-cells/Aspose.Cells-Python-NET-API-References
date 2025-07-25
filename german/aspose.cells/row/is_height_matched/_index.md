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

Gibt an, ob die Zeilenhöhe der aktuellen Standardschriftarteinstellung der Arbeitsmappe entspricht.
Der Wert „True“ dieser Eigenschaft bedeutet auch, dass die Zeilenhöhe „automatisch“ ist, ohne dass der Benutzer einen benutzerdefinierten Höhenwert festlegen muss.

###  Bemerkungen

Wenn diese Eigenschaft wahr ist und sich der Inhalt dieser Zeile ändert,
generell muss die Zeilenhöhe neu berechnet werden (z.B. nach [`Worksheet.auto_fit_rows`](/cells/python-net/de/aspose.cells/worksheet/auto_fit_rows))
um dasselbe Ergebnis zu erhalten, das in MS Excel angezeigt wird, wenn Sie die Arbeitsmappe darin öffnen.
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
