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

Anger om radhöjden matchar arbetsbokens aktuella standardteckensnittsinställning.
Sant för den här egenskapen anger också att radhöjden är "automatisk" utan ett anpassat höjdvärde som anges av användaren.

###  Anmärkningar

När den här egenskapen är sann, om innehållet i den här raden ändras,
Generellt sett måste radhöjden beräknas om (t.ex. med [`Worksheet.auto_fit_rows`](/cells/python-net/sv/aspose.cells/worksheet/auto_fit_rows))
för att få samma resultat som det som visas i MS Excel när du öppnar arbetsboken i den.
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
