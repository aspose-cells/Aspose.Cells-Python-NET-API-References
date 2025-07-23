---
title: empty_formula_value_as_blank fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank fastighet

Om en cell ska tas som tom när den är en formel och det beräknade resultatet är null eller en tom sträng.
Standardvärdet är falskt.

###  Anmärkningar

Generellt sett bör användaren se till att formlerna har beräknats innan en operation med den här egenskapen som sann tas bort.
Annars kommer alla nyligen skapade formler av vanliga API:er, såsom [`Cell.formula`](/cells/python-net/sv/aspose.cells/cell#formula), att tas som tomma och kan raderas.
eftersom före beräkningen är alla deras beräknade resultat noll.
###  Definition:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`DeleteBlankOptions`](/cells/python-net/sv/aspose.cells/deleteblankoptions)
