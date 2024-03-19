---
title: is_height_matched fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 190
url: /sv/aspose.cells/row/is_height_matched/
is_root: false
---
##  is_height_matched fastighet

Indikerar om radhöjden matchar nuvarande standardteckensnittsinställning för arbetsboken.
Sant för denna egenskap anger också att radhöjden är "automatisk" utan anpassat höjdvärde som ställts in av användaren.

###  Anmärkningar

När den här egenskapen är sann, om innehållet i den här raden ändras,
i allmänhet måste radhöjden beräknas om (t.ex. med [`Worksheet.auto_fit_rows`](/cells/python-net/sv/aspose.cells/worksheet/auto_fit_rows))
för att få samma resultat med det som visas i ms excel när du öppnar arbetsboken i den.
###  Definition:
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Row`](/cells/python-net/sv/aspose.cells/row)
